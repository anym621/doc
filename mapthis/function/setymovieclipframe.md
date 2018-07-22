# setYMovieClipFrame

`setYMovieClipFrame(ID：Number，帧：Number，播放Bo：Boolean)`

**描述：**

* 用于控制动画跳帧，此方法不管动画对象是否在显示区域中，都可以使用。
* 第三个参数如果为true，将执行跳到并播放，否则执行跳到并停止。 
* 注意：如果使用此方法控制某个从未加载的动画，那么该动画的onLoadYMovieClip方法中的，第一次加载Bo将为false。

** 示例：**

```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.setYMovieClipFrame(id，10，false);
//将某一动画跳第十帧并停止
```



