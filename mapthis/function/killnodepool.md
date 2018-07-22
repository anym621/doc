# killNodePool

`killNodePool(上次使用时间/图块名：Number/String)`

 **描述：**

 销毁Node池，参数可以是时间，也可以是指定图块名。

 **示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.killNodePool(60);//清除一分钟内没有使用的池
this.mapjs.killNodePool(“土地”);//清除叫土地的图块
```