>1.line-height的含义
- line-height指行高，即一行的高度，在CSS中更准确的定义为<span style="color:deepskyblue">两行文字基线之间的距离</span>
- line-height不指行间距，行间距是两行文本之间的距离  

>2.line-height的取值
- 百分值、em值  
该两种取值皆为相对于<span style="color:deepskyblue">父元素的font-size值</span>来计算  
line-heigt=(父元素font-size)×(百分比)  
line-heigt=(父元素font-size)×(em值)  
- 无单位数字  
<span style="color:deepskyblue">在CSS中只有line-height属性支持无数字单位</span>  
实际行高是<span style="color:deepskyblue">相对于当前元素的font-size值</span>来计算  