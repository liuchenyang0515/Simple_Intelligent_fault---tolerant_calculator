看了一些网上的代码，感觉多少有点问题，有的不能计算浮点数，有的不能计算多位数，或者没办法保证乘除法在加减法的前面，或者不能与负数进行混合运算。
我实现的如下：

特点是：在按“=”之前智能预算结果显示，点击按钮，按钮颜色变化；

思路是：将输入的中缀表达式转换成后缀表达式进行计算

难点是：带负数的四则混合运算

当然最后要记得负0的处理还是为0，除以0提示不能除以0

我的博客记录了效果演示图：https://blog.csdn.net/qq_34115899/article/details/83718437
