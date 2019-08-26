一、绝对单位
- 绝对单位一般多用于传统平面印刷，极少用于前端开发  

二、相对单位  

>1.px
- 像素，计算机屏幕中最小的点
- 可以将px说成是绝对单位
- 计算机浏览器默认字体大小是16px

>2.%
- width、height、font-size的百分比是相对于<span style="color:deepskyblue">父元素</span>“相同元素”的值来计算的
- line-height的百分比是相对于<span style="color:deepskyblue">父元素</span>的“font-size”值来计算的
- vertical-align的百分比是相对于<span style="color:deepskyblue">当前元素</span>的line-height的值来计算的

>3.em
- em是相对于<span style="color:deepskyblue">当前元素</span>的<span style="color:deepskyblue">字体大小</span>而言的
- 如果当前元素的字体大小没有定义，则当前元素会继承父元素的font-size。如果当前元素的所有祖先元素都没有定义font-size，当前元素会继承浏览器默认的font-size
- 使用em的小技巧：  
(1) 首行缩进使用text-indet:2em来实现；  
(2) 使用em作为统一单位  
    在CSS中提前声明“body{font-size:62.5%}”,使默认字体大小变为10px  
(3) 使用em作为字体大小的单位

>4.rem
- rem是相对于<span style="color:deepskyblue">根元素(html元素)</span>的<span style="color:deepskyblue">字体大小</span>而言的

>5.推荐使用px作为单位，因为px作为单位非常方便计算长度