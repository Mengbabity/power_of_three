# power_of_three

给定一个数，判断其是否是3的x次幂。

首先用到log函数的性质。如果x=log10(n)/log10(3),既有3的x幂为n。若为3的x次幂，x应为正整数，x%1==0返回true，否则返回false。

用到fmod函数。其第一个参数为double或long，计算结果为第一个参数%第二个参数。
