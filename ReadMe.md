# 常见的HTML事件
`onchange`-HTML元素改变  
`onclick`-用户点击HTML元素  
`onmouseover`-用户在一个HTML元素上移动鼠标
`onmouseout`-用户在一个HTML元素上移开鼠标   
`onkeydown`-用户按下键盘按键   
`onload`-浏览器已完成页面的加载   
# 字符串中的引号不要与字符串的引号相同
字符串长度 `.length`  
# 转义字符
`\b`-退格  
`\f`-换页  
`\r`-回车  
`\n`-换行  
`\t`-tab  
`\"`-”  
# 字符串属性
1. constructor-返回创建字符串属性的函数,constructor属性返回变量或对象的构造函数  
2. length-返回字符串的长度
3. prototype-允许向对象添加属性和方法
# 逻辑运算符
* &&-and   
* ||-or  
* !-not  

# 循环
for/in-循环遍历对象的属性

# typeof操作符
检测变量的数据类型   
`typeof null`返回object；  
`null==undefined`-true;  
数组是一种特殊的对象类型；  
# Javascript类型转换
* `Number()`转换为数字
* `String()`转换为字符串
* `Boolean()`转换为布尔值
# Javascript数据类型
### 5种数据类型
1. string
2. number
3. boolean
4. object
5. function
### 3种对象类型
1. Object
2. Date
3. Array    
### 2个不含任何值的数据类型
1. null
2. undefined
# 使用constructor属性来查看对象是否为数组
`function isArray(myArray){
	return myArray.constructor.toString().indexof("Array")>-1;
}`
# Javascript正则表达式(Regular Expression),简写regex，regexp或者RE
使用单个字符串来描述，匹配一系列符合某个句法规则的字符串搜索模式。  
搜索模式可用于文本搜索（search(),返回起始位置）和文本替换（replace()）   
### 语法
/正则表达式主体/修饰符(可选)
### 正则表达式修饰符
`i`-执行对大小写不敏感的匹配
`g`-执行全局匹配（查找所有的匹配）
`m`-执行多行匹配
