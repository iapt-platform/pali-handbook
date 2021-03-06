# 变格词典查询法

## 第1步 直接查询
**词典系统**会依照语尾变格规则自动**去除格位语尾**，**还原**可能的**词典原型**进行查询，手动**还原词典原型**的方法参见**方法2**。
 如果运气好可能可以查到原生词典的结果或在[wikipāḷi](https://www.wikipali.org/app/dict/ "wikipāḷi在线巴利语词典")社区字典中找到**用户贡献**的数据。

很多巴利语词典软件已经集成了格位猜测功能，如wikipali(在线网页), DPR(离线), TPP(离线)等，在直接查询的时候可以给出可能的**词典原型**。这些可能的词典原型如何判断，参考**第2步**。

## 第2步 去格位查询

如果直接查询失败，则去掉格位语尾再次查询，索引列表中会显示可能的拼写，找出以**元音结尾**的且**词典收录数最多**的那个拼写。
 $$原词 \ce{->[去除格位语尾][粘入词典查询框]} 单词列表_{拼写-收录数} \ce{->[词典收录数多][拼写差异小]} 靠谱结果$$
这里在粘入词典查询输入框之后，**不要按回车键**，**词典系统**会很快给出拼写符合的**备选词列表**，每个词后面的数字就是**词典收录数**。
如果这个数字大于5，那往往结果可以直接用，如果这个数字小于5，往往结果不太好用。
这一步要用可以显示**词典收录数**的软件才可以进行，如[wikipāḷi](https://www.wikipali.org/app/dict/ "wikipāḷi在线巴利语词典")。
例如：
$$kāyena\ce{->[去除格位特征ena][粘入词典查询框]} kāy备选词列表\ce{->[18本典收录][kāya与kāy差异最小]}kāya靠谱$$

如果查询结果找不到汉语含义，则需要进行**第3步**。

## 第3步 非中文词典的利用

如果用户是可以阅读英文，会使用英文词典，可以用英文词典查词。
然而由于目前世界上最权威，收词量最大的词典要数巴缅词典，笔者在实际翻译过程中，发现大量的词往往其他词典没有的时候，两部巴缅词典都会有。

这里就需要用到网页划词翻译工具。据笔者了解，可以翻译缅文的网页划词翻译工具主要是百度翻译和谷歌翻译。

而在chrome浏览器有一个扩展插件叫做“**划词翻译**”，可以自动调用多家翻译工具，方便大家**兼听则明**。而且中国大陆的用户也可以通过**划词翻译**插件调用**谷歌翻译**。