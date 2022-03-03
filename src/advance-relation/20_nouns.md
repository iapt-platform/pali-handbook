# 20. 分词/名词DEF关系的用法

- 巴利：lakkhaṇa → lakkhya
- 中文：限定从句 → 限定动词
- 英文：Definitive Relation

**a.** 在某些上下文中，一个分词或名词与另一个词具有 DEF 关系的动词可以升级为在*ablative*情况下的*abstract derivative*形式，并在与*因果*关系中相同。
如果一个*相对*或*绝对*的从句是由分词/名词所引导的，则该分词的*施动者/主语*或*受动者/宾语*做*属格*变化，并且是衍生的*causal possessor*。

**a.** In some contexts, a participle, or a noun, which has a **DEF** relation to another 
verb can be upgraded to its *abstract derivative* form in *ablative* case and related to the 
same in *causal* relation. If the clause governed by the participle / noun is a *relative* or 
*absolute* one, the *active subject* or *active object* of the participle comes to have the 
*genitive case* and be the *causal possessor* of the derivative. 

### 例句： Puriso gacchanto magge bhikkhum passati. 
- 当那个男人去的时候，（他）在路上看到比库。
- When the man goes (*because of the man’s act of going*), (he) sees the monk on the way.

<div class="mermaid">
flowchart LR
A("puriso")
B("gacchanto")
C("passati")
D("magge")
E("bhikkhuṃ")
A--"ASV<br>施动者<sub>主</sub> → 动词"-->B
A--"ASV<br>施动者<sub>主</sub> → 动词"-->C
B--"lakkhaṇa → lakkhya<br>限定从句 → 限定动词"-->C
D--"LOV"-->C
E--"IOV"-->C
</div>

### 例句： purisassa gacchantattā magge bhikkhum passati.
- 因为男人的前往而在路上看到比库。
- Because of the man’s act of going, (he) sees the monk on the way.
<div class="mermaid">
flowchart LR
A("purisassa")
B("gacchantattā")
C("passati")
D("magge")
E("bhikkhuṃ")
A--"POS"-->B
B--"CAU"-->C
D--"LOV"-->C
E--"IOV"-->C
</div>

### 例句：Pitari kāle putto kāḷo hoti.
- *既然/正如* 父亲是黝黑的，儿子 *就* 是黝黑的。
- *As / When* (the) father is dark, (the) son is dark.


<div class="mermaid">
flowchart LR
A("pitari<br>父亲<br>单·处")
B("kāle")
C("putto")
D("kāḷo")
E("hoti")
A--"NIO"-->B
B--"当……"-->E
C--"DASO-P"-->E
D--"DASO-S"-->E
</div>

### 例句：pituno kālattā putto kāḷo hoti 
- 因为父亲的黝黑（肤色），所以儿子是黝黑的（肤色）。
- because of the father's darkness, (the) son is dark.
<div class="mermaid">
flowchart LR
A("pituno<br>父亲[的]")
B("kālattā")
C("putto")
D("kāḷo")
E("hoti")
A--"POS<br>属 → 从"-->B
B--"CAU<br>因 → 果"-->E
C--"DASO-P<br>主 → 系"-->E
D--"DASO-S<br>表 → 系"-->E
</div>


**b**. Sometimes, a *present participle* may imply a wish, a desire. 

**b**. 有时，*现在分词*可能意味着一个祝福，一个愿望。

 ### 例句： Puriso gacchanto āha, “ācariya, ahaṃ gacche”ti. 
 
 **译**. 当那个男人（*希望*）离开时，（他）说："老师啊！我可以走吗？"

 **Trs.** When the man (*wishes to*) go, (he) said, “O Teacher! May I go? “