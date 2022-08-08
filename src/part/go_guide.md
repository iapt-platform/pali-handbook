# 编辑数据

<a href="http://47.108.158.109:8050/samples/navigation.html" target="_blank">在这里编辑</a>
好数据后点保存，得到数据文件


# 编辑展示页面

调整好div的高度等样式，

把数据文件里面的内容替换textarea里面的内容，

可以修改节点选中后的高亮样式，改radio控件的id值即可，可改的值参考编辑数据页面右边的radio控件的id值

```html
<div id="myDiagramDiv" style="background-color:white;height:800px;width:100%">

</div>

<textarea id="mySavedModel" style="display:none">
{ "class": "GraphLinksModel",
  "nodeDataArray": [
{"key":1,"info":[{"type":"text","text":"some text"},{"type":"button","text":"Click me!","handler":"alert"}]},
{"key":2,"text":"B","location":{"class":"go.Point","x":420,"y":270}},
{"key":3,"text":"C","group":9,"location":{"class":"go.Point","x":270,"y":215},"url":"http://baidu.com"},
{"key":4,"text":"D","group":11,"location":{"class":"go.Point","x":270,"y":325}},
{"key":5,"text":"E","group":10,"location":{"class":"go.Point","x":120,"y":225}},
{"key":6,"text":"F","group":11,"location":{"class":"go.Point","x":200,"y":350}},
{"key":7,"text":"G","location":{"class":"go.Point","x":180,"y":450}},
{"key":8,"text":"Chi","isGroup":true},
{"key":9,"text":"Psi","isGroup":true,"group":8},
{"key":10,"text":"Phi","isGroup":true,"group":9},
{"key":11,"text":"Omega","isGroup":true,"group":9}
],
  "linkDataArray": [
{"from":1,"to":2},
{"from":1,"to":3},
{"from":2,"to":2},
{"from":2,"to":3},
{"from":2,"to":11},
{"from":2,"to":1},
{"from":2,"to":9},
{"from":3,"to":4},
{"from":4,"to":5,"text":"hello","url":"https://baidu.com"},
{"from":5,"to":6},
{"from":6,"to":7}
]}
</textarea>
<input type="radio" name="highlight" id="nodesReach" checked="checked" style="display:none">
```

# 效果

<div id="myDiagramDiv" style="background-color: white; height: 800px;  width:100%">

</div>

<textarea id="mySavedModel" style="display:none">
{ "class": "GraphLinksModel",
  "nodeDataArray": [
{"key":1,"info":[{"type":"text","text":"some text"},{"type":"button","text":"Click me!","handler":"alert"}]},
{"key":2,"text":"B","location":{"class":"go.Point","x":420,"y":270}},
{"key":3,"text":"C","group":9,"location":{"class":"go.Point","x":270,"y":215},"url":"http://baidu.com"},
{"key":4,"text":"D","group":11,"location":{"class":"go.Point","x":270,"y":325}},
{"key":5,"text":"E","group":10,"location":{"class":"go.Point","x":120,"y":225}},
{"key":6,"text":"F","group":11,"location":{"class":"go.Point","x":200,"y":350}},
{"key":7,"text":"G","location":{"class":"go.Point","x":180,"y":450}},
{"key":8,"text":"Chi","isGroup":true},
{"key":9,"text":"Psi","isGroup":true,"group":8},
{"key":10,"text":"Phi","isGroup":true,"group":9},
{"key":11,"text":"Omega","isGroup":true,"group":9}
],
  "linkDataArray": [
{"from":1,"to":2},
{"from":1,"to":3},
{"from":2,"to":2},
{"from":2,"to":3},
{"from":2,"to":11},
{"from":2,"to":1},
{"from":2,"to":9},
{"from":3,"to":4},
{"from":4,"to":5,"text":"hello","url":"https://baidu.com"},
{"from":5,"to":6},
{"from":6,"to":7}
]}
</textarea>
<input type="radio" name="highlight" id="nodesReach" checked="checked" style="display:none">


<div id="myDiagramDiv" style="background-color: white; height: 800px;  width:100%">

</div>

<textarea id="mySavedModel" style="display:none">
{ "class": "GraphLinksModel",
  "nodeDataArray": [
{"key":1,"info":[{"type":"text","text":"some text"},{"type":"button","text":"Click me!","handler":"alert"}]},
{"key":2,"text":"B","location":{"class":"go.Point","x":420,"y":270}},
{"key":3,"text":"C","group":9,"location":{"class":"go.Point","x":270,"y":215},"url":"http://baidu.com"},
{"key":4,"text":"D","group":11,"location":{"class":"go.Point","x":270,"y":325}},
{"key":5,"text":"E","group":10,"location":{"class":"go.Point","x":120,"y":225}},
{"key":6,"text":"F","group":11,"location":{"class":"go.Point","x":200,"y":350}},
{"key":7,"text":"G","location":{"class":"go.Point","x":180,"y":450}},
{"key":8,"text":"Chi","isGroup":true},
{"key":9,"text":"Psi","isGroup":true,"group":8},
{"key":10,"text":"Phi","isGroup":true,"group":9},
{"key":11,"text":"Omega","isGroup":true,"group":9}
],
  "linkDataArray": [
{"from":1,"to":2},
{"from":1,"to":3},
{"from":2,"to":2},
{"from":2,"to":3},
{"from":2,"to":11},
{"from":2,"to":1},
{"from":2,"to":9},
{"from":3,"to":4},
{"from":4,"to":5,"text":"hello","url":"https://baidu.com"},
{"from":5,"to":6},
{"from":6,"to":7}
]}
</textarea>
<input type="radio" name="highlight" id="nodesReach" checked="checked" style="display:none">