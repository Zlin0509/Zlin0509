# MIT 6.S081: Operating System Engineering

开发内核时，注意操作系统要具有防御性
利用硬件来进行防御：user/kernel mode和虚拟内存

### 宏内核

所有操作系统和服务都在kernel mode中
优点：一个操作系统的所有子模块都在内核中运行，运行速度快，性能好
缺点：操作系统的每个bug都会成为漏洞，代码越多，出现严重漏洞的可能性越大

### 微内核

在kernel mode中运行尽可能少的代码
