---
layout: archive
title: "Organization and Architecture"
permalink: /oaa/
author_profile: true
---

| Field            |                                                              |
| ---------------- | ------------------------------------------------------------ |
| 计算机系统概述   | 计算机发展历程<br />计算机系统层次结构<br />计算机的性能指标 |
| 数据的表示和运算 | 数制与编码<br />运算方法和运算电路<br />浮点数的表示与运算   |
| 存储系统         | 存储器概述<br />主存储器<br />主存储器与CPU的连接<br />外部存储器<br />高速缓冲存储器<br />虚拟存储器 |
| 指令系统         | 指令系统<br />指令的寻址方式<br />程序的机器级代码表示<br />CISC和RISC的基本概念 |
| 中央处理器       | CPU的功能和基本结构<br />指令执行过程<br />数据通路的功能和基本结构<br />控制器的功能和工作原理<br />异常和中断机制<br />指令流水线<br />多处理器的基本概念 |
| 总线             | 总线概述<br />总线事务和定时                                 |
| 输入/输出系统    | I/O系统基本概念<br />I/O接口<br />I/O方式                    |

| 计算机系统概述     |                                                              |
| ------------------ | ------------------------------------------------------------ |
| 计算机发展历程     | [计算机硬件的发展](http://zengbaocheng-996.github.io/files/oaa/1-1-1.pdf)<br />[计算机软件的发展](http://zengbaocheng-996.github.io/files/oaa/1-1-2.pdf) |
| 计算机系统层次结构 | [计算机系统的组成](http://zengbaocheng-996.github.io/files/oaa/1-2-1.pdf)<br />[计算机硬件](http://zengbaocheng-996.github.io/files/oaa/1-2-2.pdf)<br />[计算机软件](http://zengbaocheng-996.github.io/files/oaa/1-2-3.pdf)<br />[计算机系统的层次结构](http://zengbaocheng-996.github.io/files/oaa/1-2-4.pdf)<br />[计算机系统的工作原理](http://zengbaocheng-996.github.io/files/oaa/1-2-5.pdf) |
| 计算机的性能指标   | [计算机的主要性能指标](http://zengbaocheng-996.github.io/files/oaa/1-3-1.pdf)<br />[几个专业术语](http://zengbaocheng-996.github.io/files/oaa/1-3-2.pdf) |

| 数据的表示和运算   |                                                              |
| ------------------ | ------------------------------------------------------------ |
| 数制与编码         | [进位计数制及其相互转换](http://zengbaocheng-996.github.io/files/oaa/2-1-1.pdf)<br />[定点数的编码表示](http://zengbaocheng-996.github.io/files/oaa/2-1-2.pdf)<br />[整数的表示](http://zengbaocheng-996.github.io/files/oaa/2-1-3.pdf)<br />[C语言中的整数类型及类型转换](http://zengbaocheng-996.github.io/files/oaa/2-1-4.pdf) |
| 运算方法和运算电路 | [基本运算部件](http://zengbaocheng-996.github.io/files/oaa/2-2-1.pdf)<br />[定点数的移位运算](http://zengbaocheng-996.github.io/files/oaa/2-2-2.pdf)<br />[定点数的加减运算](http://zengbaocheng-996.github.io/files/oaa/2-2-3.pdf)<br />[定点数的乘除运算](http://zengbaocheng-996.github.io/files/oaa/2-2-4.pdf) |
| 浮点数的表示与运算 | [浮点数的表示](http://zengbaocheng-996.github.io/files/oaa/2-3-1.pdf)<br />[浮点数的加减运算](http://zengbaocheng-996.github.io/files/oaa/2-3-2.pdf)<br />[C语言中的浮点数类型](http://zengbaocheng-996.github.io/files/oaa/2-3-3.pdf)<br />[数据的大小端和对齐存储](http://zengbaocheng-996.github.io/files/oaa/2-3-4.pdf) |

| 存储系统            |                                                              |
| ------------------- | ------------------------------------------------------------ |
| 存储器概述          | [存储器的分类](http://zengbaocheng-996.github.io/files/oaa/3-1-1.pdf)<br />[存储器的性能指标](http://zengbaocheng-996.github.io/files/oaa/3-1-2.pdf)<br />[多级层次的存储系统](http://zengbaocheng-996.github.io/files/oaa/3-1-3.pdf) |
| 主存储器            | [SRAM芯片和DRAM芯片](http://zengbaocheng-996.github.io/files/oaa/3-2-1.pdf)<br />[只读存储器](http://zengbaocheng-996.github.io/files/oaa/3-2-2.pdf)<br />[主存储器的基本组成](http://zengbaocheng-996.github.io/files/oaa/3-2-3.pdf)<br />[多模块存储器](http://zengbaocheng-996.github.io/files/oaa/3-2-4.pdf) |
| 主存储器与CPU的连接 | [连接原理](http://zengbaocheng-996.github.io/files/oaa/3-3-1.pdf)<br />[主存容量的扩展](http://zengbaocheng-996.github.io/files/oaa/3-3-2.pdf)<br />[存储芯片的地址分配和片选](http://zengbaocheng-996.github.io/files/oaa/3-3-3.pdf)<br />[存储器与CPU的连接](http://zengbaocheng-996.github.io/files/oaa/3-3-4.pdf) |
| 外部存储器          | [磁盘存储器](http://zengbaocheng-996.github.io/files/oaa/3-4-1.pdf)<br />[固态硬盘](http://zengbaocheng-996.github.io/files/oaa/3-4-2.pdf) |
| 高速缓冲存储器      | [程序访问的局部性原理](http://zengbaocheng-996.github.io/files/oaa/3-5-1.pdf)<br />[Cache的基本工作原理](http://zengbaocheng-996.github.io/files/oaa/3-5-2.pdf)<br />[Cache和主存的映射方式](http://zengbaocheng-996.github.io/files/oaa/3-5-3.pdf)<br />[Cache中主存块的替换算法](http://zengbaocheng-996.github.io/files/oaa/3-5-4.pdf)<br />[Cache的一致性问题](http://zengbaocheng-996.github.io/files/oaa/3-5-5.pdf) |
| 虚拟存储器          | [虚拟存储器的基本概念](http://zengbaocheng-996.github.io/files/oaa/3-6-1.pdf)<br />[页式虚拟存储器](http://zengbaocheng-996.github.io/files/oaa/3-6-2.pdf)<br />[段页式虚拟存储器](http://zengbaocheng-996.github.io/files/oaa/3-6-3.pdf)<br />[虚拟存储器与Cache的比较](http://zengbaocheng-996.github.io/files/oaa/3-6-4.pdf) |

| 指令系统             |                                                              |
| -------------------- | ------------------------------------------------------------ |
| 指令系统             | [指令集体系结构](http://zengbaocheng-996.github.io/files/oaa/4-1-1.pdf)<br />[指令的基本格式](http://zengbaocheng-996.github.io/files/oaa/4-1-2.pdf)<br />[定长操作码指令格式](http://zengbaocheng-996.github.io/files/oaa/4-1-3.pdf)<br />[扩展操作码指令格式](http://zengbaocheng-996.github.io/files/oaa/4-1-4.pdf)<br />[指令的操作类型](http://zengbaocheng-996.github.io/files/oaa/4-1-5.pdf) |
| 指令的寻址方式       | [指令寻址和数据寻址](http://zengbaocheng-996.github.io/files/oaa/4-2-1.pdf)<br />[常见的数据寻址方式](http://zengbaocheng-996.github.io/files/oaa/4-2-2.pdf) |
| 程序的机器级代码表示 | [常用汇编指令介绍](http://zengbaocheng-996.github.io/files/oaa/4-3-1.pdf)<br />[选择语句的机器级表示](http://zengbaocheng-996.github.io/files/oaa/4-3-2.pdf)<br />[循环语句的机器级表示](http://zengbaocheng-996.github.io/files/oaa/4-3-3.pdf)<br />[过程调用的机器级表示](http://zengbaocheng-996.github.io/files/oaa/4-3-4.pdf) |
| CISC和RISC的基本概念 | [复杂指令系统计算机（CISC）](http://zengbaocheng-996.github.io/files/oaa/4-4-1.pdf)<br />[精简指令系统计算机（RISC）](http://zengbaocheng-996.github.io/files/oaa/4-4-2.pdf)<br />[CISC和RISC的比较](http://zengbaocheng-996.github.io/files/oaa/4-4-3.pdf) |

| 中央处理器               |                                                              |
| ------------------------ | ------------------------------------------------------------ |
| CPU的功能和基本结构      | [CPU的功能](http://zengbaocheng-996.github.io/files/oaa/5-1-1.pdf)<br />[CPU的基本结构](http://zengbaocheng-996.github.io/files/oaa/5-1-2.pdf)<br />[CPU的寄存器](http://zengbaocheng-996.github.io/files/oaa/5-1-3.pdf) |
| 指令执行过程             | [指令周期](http://zengbaocheng-996.github.io/files/oaa/5-2-1.pdf)<br />[指令周期的数据流](http://zengbaocheng-996.github.io/files/oaa/5-2-2.pdf)<br />[指令执行方案](http://zengbaocheng-996.github.io/files/oaa/5-2-3.pdf) |
| 数据通路的功能和基本结构 | [数据通路的功能](http://zengbaocheng-996.github.io/files/oaa/5-3-1.pdf)<br />[数据通路的组成](http://zengbaocheng-996.github.io/files/oaa/5-3-2.pdf)<br />[数据通路的基本结构](http://zengbaocheng-996.github.io/files/oaa/5-3-3.pdf)<br />[数据通路的操作举例](http://zengbaocheng-996.github.io/files/oaa/5-3-4.pdf) |
| 控制器的功能和工作原理   | [控制器的结构和功能](http://zengbaocheng-996.github.io/files/oaa/5-4-1.pdf)<br />[硬布线控制器](http://zengbaocheng-996.github.io/files/oaa/5-4-2.pdf)<br />[微程序控制器](http://zengbaocheng-996.github.io/files/oaa/5-4-3.pdf) |
| 异常和中断机制           | [异常和中断的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-5-1.pdf)<br />[异常和中断的分类](http://zengbaocheng-996.github.io/files/oaa/5-5-2.pdf)<br />[异常和中断响应过程](http://zengbaocheng-996.github.io/files/oaa/5-5-3.pdf) |
| 指令流水线               | [指令流水线的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-6-1.pdf)<br />[流水线的基本实现](http://zengbaocheng-996.github.io/files/oaa/5-6-2.pdf)<br />[流水线的冒险与处理](http://zengbaocheng-996.github.io/files/oaa/5-6-3.pdf)<br />[流水线的性能指标](http://zengbaocheng-996.github.io/files/oaa/5-6-4.pdf)<br />[高级流水线技术](http://zengbaocheng-996.github.io/files/oaa/5-6-5.pdf) |
| 多处理器的基本概念       | [SISD、SIMD、MIMD的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-7-1.pdf)<br />[硬件多线程的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-7-2.pdf)<br />[多核处理器的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-7-3.pdf)<br />[共享内存多处理器的基本概念](http://zengbaocheng-996.github.io/files/oaa/5-7-4.pdf) |

| 总线           |                                                              |
| -------------- | ------------------------------------------------------------ |
| 总线概述       | [总线基本概念](http://zengbaocheng-996.github.io/files/oaa/6-1-1.pdf)<br />[总线的分类](http://zengbaocheng-996.github.io/files/oaa/6-1-2.pdf)<br />[系统总线的结构](http://zengbaocheng-996.github.io/files/oaa/6-1-3.pdf)<br />[常见的总线标准](http://zengbaocheng-996.github.io/files/oaa/6-1-4.pdf)<br />[总线的性能指标](http://zengbaocheng-996.github.io/files/oaa/6-1-5.pdf) |
| 总线事务和定时 | [总线事务](http://zengbaocheng-996.github.io/files/oaa/6-2-1.pdf)<br />[总线定时](http://zengbaocheng-996.github.io/files/oaa/6-2-2.pdf) |

| 输入/输出系统   |                                                              |
| --------------- | ------------------------------------------------------------ |
| I/O系统基本概念 | [输入/输出系统](http://zengbaocheng-996.github.io/files/oaa/7-1-1.pdf)<br />[I/O控制方式](http://zengbaocheng-996.github.io/files/oaa/7-1-2.pdf)<br />[外部设备](http://zengbaocheng-996.github.io/files/oaa/7-1-3.pdf) |
| I/O接口         | [I/O接口的功能](http://zengbaocheng-996.github.io/files/oaa/7-2-1.pdf)<br />[I/O接口的基本结构](http://zengbaocheng-996.github.io/files/oaa/7-2-2.pdf)<br />[I/O接口的类型](http://zengbaocheng-996.github.io/files/oaa/7-2-3.pdf)<br />[I/O端口及其编址](http://zengbaocheng-996.github.io/files/oaa/7-2-4.pdf) |
| I/O方式         | [程序查询方式](http://zengbaocheng-996.github.io/files/oaa/7-3-1.pdf)<br />[程序中断方式](http://zengbaocheng-996.github.io/files/oaa/7-3-2.pdf)<br />[DMA方式](http://zengbaocheng-996.github.io/files/oaa/7-3-3.pdf) |

