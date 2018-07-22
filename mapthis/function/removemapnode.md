# removeMapNode

`removeMapNode(图块：Node)`

**描述：**

  清除地图信息。此方法只是清除该图块在地图中的显示信息，并不会摧毁图块Node，且该图块的其他信息也会被保留下来，必要时可以通过addMapNode方法，进行增加更改。但是，动画图块除外，因为被清除的动画图块，无法独立运行，所以一旦被清除，会将其摧毁。

**示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);
this.mapjs.removeMapNode(n);
```
