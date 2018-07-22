# setMapLocation

` setMapLocation(图块/ID：Node/Number，X：Number，Y：Number，图层名(选添)：String)返回：Array`

** 描述：**

 移动地图图块，参数1可以是图块Node，也可以是图块ID，但是建议用图块ID。

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);        
this.mapjs.setMapLocation(n,10,15);  
```
