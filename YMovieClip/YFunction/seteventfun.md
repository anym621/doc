# setEventFun

`setEventFun(帧：Number，要更改的事件名：String，事件方法：Function)`

** 描述：**

  更改事件，前提是该帧上必须有事件，包括用黑小孩加的事件（这里有区别，用黑小孩加的事件，其实就是相当于，动画执行到某一帧之后dispatchEvent事件，用户只需要得到动画对象，然后ymc.on\(“事件名”,Fun\)，就可得到事件。但是使用setEventFun更改，或addEventFun增加事件，都是相当于将某一方法插入到某一帧上。弹出与插入式不同的，但是他们都能实现同一个目标，该怎么做取决于你）。

** 示例：**
```javascript
ymc.setEventFun(5,”ADC”,function(){
    //内容
});
```
