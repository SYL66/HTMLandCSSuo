>1.图片与文字对齐
- 当图文混排时，在底部水平方向上图文往往是不对齐的，这是因为图片与文字默认是基线对齐(vertical-align:baselne)
- 实现图片与文字底部对齐的方式：  
(1) 使用"vertical-align:text-bottom"  
(2) 使用兼容性较好的负margin技术：在CSS中添加"img{margin:0 3px -3px 0}"  

>2.自适应两列布局
- 自适应两列布局是指在左右两列中，其中一列的宽度固定，另一列的宽度为自适应
- 使用float一般只能实现固定的左右两列布局  

>3.元素垂直居中
- 万能的方法：使用position结合负margin来实现,万能值该方法对3种元素皆有效
- 首先给父元素写上"position:relative",这样做是为了给子元素添加"position:absolute"的时候不会被定位到"外太空"去
- 然后给子元素添加如下属性:  
position:abslute;  
top:50%;  
left:50%;  
margin-top:"height值一半的负值";  
margin-left:"width值一半的负值";

>4.tab选项卡
- 关键是使用"margin-top:-1px"来解决选项卡下边框显示问题