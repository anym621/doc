# onLoadSprite



`
 onLoadSprite(图块：Node，图层名：String)
`
  


 **描述：**

 每次图块添加到舞台时调用。

  


** 示例：**
```javascript
this.mapjs=this.MapNode.getComponent(this.MapStr);            
this.mapjs.onLoadSprite=function(n,LayerName){                    
     //要处理的内容                    
}  
```
