# addMapNode

`addMapNode(图块：Node，图层名：String)返回:Boolean`

** 描述：**

 向地图添加图块信息。注意：第一个参数的Node，并不是随意增加的Node，而是从地图取出带有特殊标记的Node。当Node增加成功时，实际是增加了一串地图信息，同时原Node会被销毁。

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.addMapNode(n,”图 层 2”);
```
