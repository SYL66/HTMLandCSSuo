>1.私用overflow可以定义当内容溢出元素边框时会发生的事情
- visible：默认值，若内容溢出，则溢出内容可见
- hidden：若内容溢出，则溢出内容隐藏
- scroll：若内容溢出，则显示滚动条
- auto：auto和scroll很相似，不同的是auto只在盒子需要的时候给它一个滚动条  

>2.overflow的作用
- 使用"overflow:scroll"显示滚动条
- 使用"overflow:hidden"来隐藏内容，以免影响布局
- 使用"overflow:hidden"来<span style="color:deepskyblue">清除浮动</span> 
  
>3.overflow:hidden的优缺点
- 优点：使得内容超出时不会影响页面整体布局
- 缺点：会使得超出的内容自动隐藏，可能会造成这部分的内容显示不完全，比如图片只显示一部分