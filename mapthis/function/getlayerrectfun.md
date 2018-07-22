# getLayerRectFun

`getLayerRectFun\(图层名：String\)返回:cc.Rect`

 **描述：**

  获得图层距离中心点的实际像素区域，注意getLayerRectFun返回为正常坐标系。即Y坐标向下为正，向上为负。如果要改成CC坐标，只需将Y\*=-1即可，其他不变。

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
var rect=this.mapjs.getLayerRectFun(“图 层 1”);
```