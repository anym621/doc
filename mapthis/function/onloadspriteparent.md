# onLoadSpriteParent

 `onLoadSpriteParent(父节点：Node，图层名：String，是否第一次加载：bool)`



** 描述：**

 每次父节点添加到舞台时调用，第三个参数为是否第一次加载。



** 示例：**

```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.onLoadSpriteParent=function(n,LayerName,bo){
     //要处理的内容
}
```

