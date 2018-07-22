# getNodeParentBySprite

` getNodeParentBySprite(图块：Node)返回:Node`

** 描述：**
 通过图块得到其地图父节点，如果图块没有地图父节点，则返回null，如果你确定该图块一定有地图父节点，也可以直接n.parent得到。


** 示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);          
var arr=this.mapjs.getNodeParentBySprite(n);                        
```
