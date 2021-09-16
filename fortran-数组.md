#数组赋值  
使用data,不需要加括号和等号，例如:  
integer A(5)  
data A  /1,2,3,4,5/  

直接赋值，需要等号和括号  
integer:: A(5) = (/1,2,3,4,5/)  

隐含式循环  
integer:: I  
integer:: A(5) = (/(I,I=1,5)/)  
表示I从1到5, 分别赋值为I  
