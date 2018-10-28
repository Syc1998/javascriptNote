
JavaScript第一章
==
####javascript是一种基于对象和事件驱动的脚本语言  
####javascript是一种弱类型语言 不需要编译 javascript语言相对来说比较安全  动态   
      ``<script type=‘'text/javascript''>
          //脚本内容
        </script>  
      alert 弹出框 语法 alert（’弹出 内容‘）  
        onload 加载
        `` 
javascript是区分大小写的语言 html并不区分大小写  
单行注释//  
多行注释/* */  
javascript标识符必须以字母 下划线（_）或美元符（$）开始  
标识符用来对变量 document.write

####var声明一个变量function 声明一个函数
`break`            退出循环  
`continue`       退出本轮循环  
`return`           函数返回值/结果函数执行  
`new`              创造一个新的对象  
`this`               代指当前对象  
####基本数据类型
`boolean`         布尔  
`undefinde`      未定义  
`null`                空  
`number`          数字  
`string`             字符串  
####JavaScript的数据类型分为两类
1.原始类型 `primitive type`
2.对象类型 `object  type`
#####原始类型包括数字 字符串 布尔值
`&nbsp` 空格  
 常见的转义字符  
`\t`    水平制表符  
`\n`   换行符  
`\r`    回车符  
`\'`    单引号  
`\"`   双引号  
`\\`   反斜线  
###`null`和`undefined`
####1表示一个未声明的变量 
####2 已声明但没有赋值的变量
####3一个并不存在的对象属性
####变量名不能有空格
####关键字不能作为变量名
####变量名是严格区分大小写的
####变量声明的格式  var 变量名;


###使用`typeof`操作符的语法
#####typeof需检测类型的值或变量或者typeof（需检测类型的值或变量）

将字符串转换为数字类型
parselnt函数将字符串转换为整数，parsefloat将字符串转换成实数
nan 该值的类型属于数字类型 

强制转换
number函数可以将给定的值转换为数字

###`boolean`函数
通过boolean函数可以将其他类型转化为布尔类型
通过Boolean函数转换的值至少有一个字符的字符串，非0数字或对象时，返回ture ;  
如果该值时空字符串，数字0，undefned或null 将返回false

