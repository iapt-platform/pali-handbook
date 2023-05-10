# 18. 多重同类修饰的用法

当使用多个做同类修饰的形容词来修饰单个名词时，
有时可以理解为前面的修饰词对后面的词依次以原因状语的方式来修饰，
即进行抽象衍生的来源格形式，并与后面的修饰词构成因果关系。

例句： abhirūpā visutā manavanti kaññā āgacchati.<br>
那个美丽、著名且骄傲的女孩来了。

<div class="mermaid">
flowchart LR;
A("abhirūpā<br>高颜值")
B("visutā<br>著名")
C("manavanti<br>骄傲")
D("kaññā<br>女孩")
E("āgacchati<br>来")
A--"IAD<br>同类修饰"-->D--"ASV<br>施动者→动词"-->E
B--"IAD<br>同类修饰"-->D
C--"IAD<br>同类修饰"-->D
</div>

例句：kaññāya abhirūpattā visutattā manavanti kaññā āgacchati.<br>
那个以美丽而著称并引以为傲的女孩来了。

<div class="mermaid">
flowchart LR;
A("abhirūpattā<br>[因]高颜值")
B("visutattā<br>[因]著名")
C("manavanti<br>骄傲")
D("kaññā<br>女孩")
E("āgacchati<br>来")
D1("kaññāya<br>女孩[的]")
D1--"POS<br>所有者→所属物"-->A
D1--"POS<br>所有者→所属物"-->B
A--"CAU<br>因→果"-->B
B--"CAU<br>因→果"-->C
C--"IAD<br>同类修饰"-->D--"ASV<br>施动者→动词"-->E
</div>
