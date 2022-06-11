[TOC]

# 1.程序注释

- 单行注释        //

- 多行注释     /* ....................../*

  

# 2.关键字

如邮箱中的@

特点：

1. 完全小写的字母
2. 在增加版的记事本中（例如notepad++）有特殊颜色

# 3.标识符

硬性要求：

1. 标识符包含英文数字美元符号和下划线
2. 不能以数字开头
3. 不能为关键字

软性要求：

1. 首字母大写       Hello  World

2. 首字母小写       helloWorld

   

# 4.常量

概念：程序运行中，固定不变的量

分类：

1. 字符串常量：双引号引起来的部分
2. 整数常量：直接写上的数字，没有小数点
3. （小数）浮点数常量：直接写上的数字，有小数点
4. 字符常量：凡是用单引号连接起来的单个子符
5. 布尔常量：ture false 只有两种数值
6. 空常量：null待表没有任何数据  注意：空常量不能直接打印输出

# 5.变量

- 概念：程序运行期间，内容可以改变的量

- 创建变量使用的格式：  数据类型 变量名称;

  ​                                            变量名称=数据值;

  或                                        数据类型 变量名称=数据值;

  注意：

  1.当打印输出变量名称时，显示变量的内容

  2.数据值不可超出数据范围

- 变量的注意事项:

  1. 如果创建多个变量，那么变量之间的名称不可重复。

  2. 对于float和long类型来说，字母后缀F和L不要去掉。

  3. 如果使用byte和short类型的变量，那么右侧数据范围不可超过左侧。

  4. 没有进行赋值的变量，不能直接使用。

  5. 变量使用不能超过作用域范围。<!--作用域-->从定义变量的一行开始，知道所属的大括号结束为止。

  6. 可以通过一个语句来创建多个变量，但是一般情况不推荐使用    

     `int a，b，c;`

     `a=10,b=20,c=30;`

     `或`

     `int x=100,y=200,z=300;`

​                                                    

# 6.ASCII码表

记住 '0'=48   'A'=65   'a'=97

如果遗忘 可

```java
char zifu='A';
System.out.println(zifu);
```