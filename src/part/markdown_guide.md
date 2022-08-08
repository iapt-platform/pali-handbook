# 译文输入范例指南
[详细范例](https://www.markdownguide.org/basic-syntax/)
## 文本样式
|输入|显示|
|-|-|
|`[[pāḷi]]`|[术语<sub>1</sub>]()(pāḷi, 术语<sub>2</sub>)|
|`**粗体**`|**粗体**|
|`*斜体*`|*斜体*|
|`***粗斜体***`|***粗斜体***|
|`~~校对删除~~`|~~校对删除~~|
|`[链接标题](www.wikipali.org "注&#10;释")`|[链接标题](www.wikipali.org "注&#10;释")|
|`![图片链接](https://www-hk.wikipali.org/app/public/images/svg/wikipali_logo.svg#wikipali_logo)`|![图片链接](https://www-hk.wikipali.org/app/public/images/svg/wikipali_logo.svg#wikipali_logo)|

## 段落样式


<div style="display:flex;">

<div style="flex:1;margin-right:1em;">

### **输入**


```
单回车不折行
双回车

真换行

---
分割线---前需要双回车
```
</div>
<div style="flex:1;">

### **显示**

单回车不折行
双回车

真换行

---
分割线---前需要双回车
</div></div>


## 表格


<div style="display:flex;">

<div style="flex:1;margin-right:1em;">

### **输入**


```
|表头1|表头2|表头3|
|:-|:-:|-:|
|右对齐|居中|左对齐|
|具体内容A1|具体内容A2|具体内容A3|
```
</div>
<div style="flex:1;">

### **显示**

|表头1|表头2|表头3|
|:-|:-:|-:|
|右对齐|居中|左对齐|
|具体内容A1|具体内容A2|具体内容A3|

</div></div>

## 高级分割线(仅限语法书编辑)

```
\{{#include ../part/line.md}}
```
{{#include ../part/line.md}}


```
\{{#include ../part/line.md:1}}
我是分割线
\{{#include ../part/line.md:2}}
```

{{#include ../part/line.md:1}}
我是分割线
{{#include ../part/line.md:2}}

