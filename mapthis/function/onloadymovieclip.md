# onLoadYMovieClip

`
onLoadYMovieClip(动画：YMovieClip，图层名：String，是否第一次加载：bool)
`

**描述：**

每次动画加载时调用，第三个参数为第一次调用，也就是只有在该动画第一次出现在舞台时才为true,其他时间为false。

**示例：**

```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr); 
this.mapjs.onLoadYMovieClip=function(ymc,LayerName,bo){      
     //要处理的内容                                                            
}                                                                                            
```



