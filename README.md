# LiBai AI Composer

> An ai powered automatically generats poems in Chinese.

很久以來，我們都想讓機器自己創作詩歌，當無數作家、編輯還沒有抬起筆時，AI已經完成了數千篇文章。現在，這裡是第一步....


# Updates

#### 2018-8-16

We are now officially announced a new project started: **StrangeAI School** - An artificial intelligence learning school and advanced algorithm exchange platform! What we believed in is: AI should made to change people's life, rather than controlled by Gaint Companies.
Here you can get some previews about our projects: http://ai.loliloli.pro (strangeai.pro availiable soon)



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


LSTM

1.	

c:\~\git clone https://github.com/jinfagang/tensorflow_poems

2.	

c:\~\conda create -n tensorflow_cpu pip python=3.6

3.	

c:\~\activate tensorflow_cpu

4.	

c:\~\pip install --ignore-installed --upgrade tensorflow==1.9

5.	

#change hardcode
#edit train.py

tf.app.flags.DEFINE_integer('epochs',2,'train how many epochs.')

c:\~\python train.py

c:\~\python compose_poem.py


###




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

