##环境: 
本程序运行环境：
*  1.  Ubuntu12.04 32位
*  2.  LLVM 3.5
*  3.  gcc 4.6.3

- - - - - - - - - - - - - - - - - - - - - - - - - -
##说明
这是上海交通大学计算机系编译原理课程设计大作业。
要求做一个Simple C的编译器，编程成LLVM的汇编语言。

我的进度：
*	第一天，12个小时，完成：
   	*	表达式
	* 	变量定义
	* 	函数定义
	* 	函数调用
*	第二天， 6个小时，完成：
	*	控制逻辑，也就是if, for什么的
*	第三天，6个小时，完成：
	*	结构体类型
	*	结构提嵌套
	*	支持8进制、16进制整数
	*	语义检查：变量重复定义
	*	语义检查：各种TYPE ERROR
 
如果有小伙伴，参考了我的程序，希望能够在改进之后继续开源，
给之后更多的小伙伴一些参考～～

祝愿大家顺利搞定编译作业！

- - - - - - - - - - - - - - - - - - - - - - - - - - - 
##command to run:
```
$ make
$ ./sc (input file) (output file)
$ ./lli (output file)
```
