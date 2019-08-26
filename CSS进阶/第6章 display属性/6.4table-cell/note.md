>3种功能
- 图片垂直居中于元素
- 等高布局
- 自动平均划分元素，并且在一行显示  

>1.图片垂直居中于元素
- 可以使用display:table-cell和vertical-align:center来实现大小不同的图片垂直居中效果
- 语法  
父元素  
\{  
	display:table-cell;  
	vertical-align:middle;  
\}  
子元素   
\{  
	vertical-align:middle;  
\}  

>2.等高布局
- 同一行的单元格td元素高度时相等的，table-cell也具有这个特点  

>3.自动平均划分元素
- 语法：  
父元素\{display:tabel}  
子元素\{display:tabel-cell}