# getNodeParentByName

`getNodeParentByName(图块：Node)返回:Node`

** 描述：**

 通过名字得到图块的地图父节点，但需要地图父节点必须在场景加载过，否则返回null。

** 示例：**

```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);          
var n=this.mapjs.getNodeParentByName(‘房子’);                
```
