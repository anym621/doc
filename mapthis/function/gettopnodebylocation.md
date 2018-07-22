# getTopNodeByLocation

`getTopNodeByLocation(图层名：Node，X：Number，Y：Number)返回:Node`

** 描述：**

  通过坐标返回某块区域内的最顶部的Node，这里坐标并不是以实际像素进行匹配，而是和图层高宽行列有关。比如图层地形是100\*乘100的，通过坐标得到，就是100\*乘100的某行某列图块（注意：不管是地形图块，还是自由图块，都会占用一个或多个行列信息。）

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);            
var n=this.mapjs.getTopNodeByLocation(“图 层 1”,50,50);        
```
