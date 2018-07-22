# getShowNode

`getShowNode(ID：Number)`

 **描述：**
 除了得到图块Node，用此方法，也可以判断图块ID是否在显示界面之中，如果不在会返回null。

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
var n=this.mapjs.getShowNode(id);
```
