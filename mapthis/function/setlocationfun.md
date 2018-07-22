# setLocationFun

`setLocationFun(X：Number=null，Y：Number=null，图层名：String=’this‘)`



** 描述：**

*  更改主Node的XY，可以单纯
  填
  写X或Y之一属性，默认为null，代表不会更改。
*  第三个参数代表要移动的图层名，要与黑小孩中所设置的图层名一
  致
  （注意黑小孩默认的图层名为“图\[空格\]层\[空格\]1”），如果不填写默认为“this”，代表整个移动。
*  此方法只能在Init方法之后才能生效，如果想在之前更改XY属性，可以在
  黑小孩中设置坐标旗，或者直接更改主Node属性。



**示例：**

```javascript
   setLocationFun(0,0,'图层1');                
```



