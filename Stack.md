
# Stack 提出背景
Friedrich L. Bauer 、德国、在慕尼黑大学深造期间，为命题公式演算设计了一台名为STANISLAUS的并行计算机。
在STANISLAUS的开发中，鲍尔和沙默尔松(Klaus Samelson)一起为命题表达式的演算发明了“堆栈法”(stack method)。

> Sidenote 命题演算在开关理论和计算机逻辑设计等领域都有十分重要的应用。
# Stack 应用到计算机
# Stack 存储结构
Robert Barton 、1959年最早提出堆栈计算机设想。
在高级程序设计语言出现之初，计算机的设计者们常常希望计算机的内部结构和高级语言的指令相对应，以使高级语言命令能由计算机硬件直接执行。堆栈计算机就是在这种背景下产生的。
据说是为了解决递归（recursive）问题 ：
> 当时，Algol语言定义了“递归”(recursive)功能。所谓递归，就是一个过程在执行中出现调用其自身的情况，这在解决某些类型的问题(如“梵塔问题”，即Hanoi Tower Problem)中非常有用和有效。为了实现递归调用，必须在内存中保留返回地址。这样问题来了：如果递归的层次极大(理论上可以无限)，那么在内存中就要保留极大(甚至无限)的存储区域以保存返回地址，这当然是不现实的。正是巴登，提出了堆栈(stack)这样一种存储结构，解决了这个问题，而具有堆栈存储器的计算机也就被称为堆栈式计算机.

其实我也没明白, /捂脸

有了堆栈这种结构，多重嵌套递归、子程序的多重调用、中断服务等功能就很容易实现了。
堆栈的这种组成结构，对于计算法采用反向波兰表示法(reverse polish notation,RPN)编写的算术表达式十分有效。


http://www.techcn.com.cn/index.php?doc-view-131751.html 

http://www.techcn.com.cn/index.php?doc-view-130902.html 

https://zhuanlan.zhihu.com/p/65110137

https://www.cnblogs.com/xiaomin/archive/2011/01/17/1937033.html
