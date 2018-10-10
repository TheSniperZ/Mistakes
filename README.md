# Mistakes
编程中出现过的错误统计和编程技巧~
只有void类型函数体可以不带返回值
类的大括号}后要加；
调用函数体时要记得加上（），否则，编译器无法查出错误但是输出结果会出错。
while(cin.get(c)) //输入ctrl+z时，while(cin.get(c))判断为假，跳出循环。

vs代码时突然出现错误： cout 不明确
环境： 
各种头文件没问题。直接声明名称空间 using namespace std；
解决方法： 
然后把using namespace std;这句给注释掉，等出现一片片错误提示，再取消注释。
然后就好了
