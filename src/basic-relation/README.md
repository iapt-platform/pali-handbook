# 基础语法basic-relation

<div class="mermaid">
flowchart TD
C("找到次要动词")
C0{"动词<br>类型"}
C1("动词不变词")
C2("分词")
C3("找到主语")
subgraph 确定从句结构
C-->C0
C0--"固定变化"-->C1
C0--"有性数格变化"-->C2
C1--"不考虑一致性"-->C3
C2--"数格一致"-->C3
end
A("找到主要动词")
A0{"动词<br>类型"}
A1("变位动词")
A2("分词")
A3("找到主语")
subgraph 确定主句结构
A-->A0
A0--"有人数态变化"-->A1
A0--"有性数格变化"-->A2
A1--"数一致"-->A3
A2--"数格一致"-->A3
end
B0{"判断一致性"}
B1("常见")
B2("少见")
A3-->B0
C3-->B0
B0--"一致"-->B1
B0--"不一致"-->B2
</div>
<div class="mermaid">
pie
    title 主句与从句主语一致性情况（大致）
    "一致" : 200
    "不一致" : 5
</div>

<div class="mermaid">
flowchart LR
subgraph 名词与动词
direction LR
A1("名词")
B1("动词")
C1("名词")
A1 --> B1 --x C1
end
subgraph 主要动词与次要动词
direction LR
A2("主要动词")
B2("次要动词1<br>连续体")
C2("次要动词2<br>连续体")
D2("次要动词3<br>分词")
E2("次要动词4<br>连续体")
F2("次要动词5<br>不定体")
B2--"ADV<br>形式先 → 后"-->C2
C2--"ADV<br>实际先 → 后"-->A2
E2--"CAU<br>原因状语 → 结果"-->A2
D2--"DEF<br>时间状语 → 动词"-->A2
F2--"PUR<br>目的状语 → 动词"-->A2
end
subgraph 名词与名词
direction LR
A3("名词1<br>性数格")
B3("名词2<br>性数格")
C3("名词<br>属格")
D3("名词<br>某格")
E3("名词<br>复·属/处")
F3("名词<br>某格")
G3("名词<br>源")
H3("形容词<br>比较级")
I3("名词<br>单·处")
J3("名词<br>某格")
K3("名词A<br>主格")
L3("名词B<br>主格")
K3--"NIO<br>主 → 表"-->L3
A3--"IAD<br>同格位修饰"-->B3
C3--"POS<br>所有者 → 所属物"-->D3
E3--"COI<br>群体 → 个体"-->F3
I3--"WHP<br>整体 → 局部"-->J3
G3--"COC<br>比 → 较"-->H3
end
</div>