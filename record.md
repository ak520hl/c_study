# C学习笔记
## 储存类

定义变量/函数的可见性和生命周期

有四种储存类auto register static extern

- auto。auto是默认的变量的储存类，大部分的变量都是用这种来定义。作用域是局部环境中。
- register。register是寄存器变量。默认是储存在寄存器中。
- static。static是静态变量，分为全局和非全局。(@todo 全局和非全局静态变量的区别)
- extern。extern变量，可以提供访问其他文件的声明的变量。
