# setSpriteFrame

`setSpriteFrame(路径：String，贴图名：String，贴图：SpriteFrame)`

**描述：**

将地图中某一贴图替换成相关贴图。注意：此方法只会改变地图中的图块贴图，并不会适配贴图大小，所以更改的贴图尽量与原贴图大小保持一致。

**示例：**

```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);                
//替换Image文件夹下的d1贴图                                            
this.mapjs.setSpriteFrame(“image”,”d1”,spriteFrame);                  
//替换Image文件夹下Tile图集中的d1贴图                            
this.mapjs.setSpriteFrame(“image/Tile”,”d1”,spriteFrame);
```



