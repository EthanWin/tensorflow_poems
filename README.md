# LiBai AI Composer

> An ai powered automatically generats poems in Chinese.

很久以來，我們都想讓機器自己創作詩歌，當無數作家、編輯還沒有抬起筆時，AI已經完成了數千篇文章。現在，這裡是第一步....


# Updates

#### 2018-8-16

We are now officially announced a new project started: **StrangeAI School** - An artificial intelligence learning school and advanced algorithm exchange platform! What we believed in is: AI should made to change people's life, rather than controlled by Gaint Companies.
Here you can get some previews about our projects: http://ai.loliloli.pro (strangeai.pro availiable soon)

#### 2018-3-12

**tensorflow_poems**來詐屍了，許久沒有更新這個項目，不知不覺已經有了上千個star，感覺大家對這個還是很感興趣，在這裡我非常榮幸大家關注這個項目，但是我們不能因此而停止不前，這也是我來詐屍的目的。我會向大家展示一下我最新的進展，首先非常希望大家關注一下我傾心做的知乎專欄，人工智慧從入門到逆天殺神以及每週一個黑科技，我們不僅僅要關注人工智慧，還有區塊鏈等前沿技術：

- 人工智慧從入門到逆天殺神(知乎專欄)： https://zhuanlan.zhihu.com/ai-man
- 每週一專案黑科技-TrackTech(知乎專欄):  https://zhuanlan.zhihu.com/tracktech
If you want talk about AI, visit our website (for now):  http://ai.loliloli.pro (strangeai.pro availiable soon)
 , **subscribe** our WeChat channel: 奇異人工智慧學院

#### 2017-11-8

貌似距離上一次更新這個repo已經很久了，這段時間很多童鞋通過微信找到了我，甚至包括一些大佬。當時這個項目只是一個練手的東西，那個時候我的手法還不是非常老道。讓各位踩坑了。現在**李白**強勢歸來。在這次的更新中增加了這些改進：

- 對資料預處理腳本進行了前所未有的簡化，現在連小學生都能瞭解了
- 訓練只需要運行train.py，資料和預訓練模型都已經備好
- 可以直接compose_poem.py 作詩，這次不會出現閉環的情況了。

#### 2017-6-1 ~~可能是最後一次更新~~

我決定有時間的時候重構這個項目了，古詩，源自在下骨子裡的文藝之風，最近搞得東西有點亂，所以召集大家，對這個項目感興趣的歡迎加入扣扣群：
```
 292889553
```


#### 2017-3-22 重磅更新，推出藏頭詩功能

一波小更新，下面的問題已經解決了：
* 訓練完成作詩時出現一直不出現的情況，實際上是陷入了一直作詩的閉環，已修復
* 新增pretty print功能，列印出的古詩標準，接入協力廠商APP或者其他平臺可以直接獲取到標準格式的詩詞
* Ternimal disable了tensorflow預設的debug信息
  最後最後最重要的是： **我們的作詩機器人（暫且叫李白）已經可以根據你的指定的字作詩了哦！！**
  歡迎大家繼續來踩，沒有star的快star！！保持更新！！永遠開源！！！
  讓我們來看看李白做的藏頭詩吧：

```
# 最近一直下雨，就作一首雨字開頭的吧
雨霽開門中，山聽淮水流。
落花遍霜霰，金壺橫河湟。
年年忽息世，徑遠誰論吟。
驚舟望秋月，應柳待晨圍。
人處山霜月，蕭蕭廣野虛。

# 李白人工智慧作詩機器人的作者長得比較帥，以帥開頭做一首吧
帥主何幸化，自日兼春連。
命錢犯夕興，職餘玄賞聖。
君有不知益，浮於但神衍。
（濃濃的懷才不遇之風...）
```

![PicName](http://ofwzcunzi.bkt.clouddn.com/VMBUVeqLjlXA6cUJ.png)


# Quick Start

using **LiBai** is very simple:

```
git clone https://github.com/jinfagang/tensorflow_poems
# train on poems
python3 train.py
# compose poems
python3 compose_poem.py
```

LSTM
https://github.com/jinfagang/tensorflow_poems

1.	git clone https://github.com/jinfagang/tensorflow_poems

2.	conda create -n tensorflow_cpu pip python=3.6

3.	activate tensorflow_cpu

4.	pip install --ignore-installed --upgrade tensorflow==1.9

5.	change hardcode

tf.app.flags.DEFINE_integer('epochs',2,'train how many epochs.')

c:\~\python train.py
c:\~\python compose_poem.py







# Copyright

This repo implement by Jin Fagang. Using this under Apache License.

```
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
```

