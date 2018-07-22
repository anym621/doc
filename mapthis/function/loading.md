# Loading



 `Loading(已加载的贴图数：Number，总贴图数：Number)`

  


** 描述：**

 加载素材的进度。

  


** 示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.Loading=function(Loaded,Total){
     cc.log(Loaded/Total*100);
}
```


