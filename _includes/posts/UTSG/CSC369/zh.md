## 课程介绍
CSC369是CS Specialist中最后两节必修课中的coding课。CSC369主要介绍了程序员三大浪漫中的Operating System(操作系统)。 这节课围绕着操作系统
的三个主题进行展开。这三个主题分别是persistence(持续性), concurrency(并发性), virtualization(虚拟化)。

persistence的意义是能够确保数据可以持久的储存在主机上即使发生意外也可以尽可能地保证数据少的丢失，在OS中file system(文件系统)是一套十分巨大用来
管理磁盘上的文件的软件，CSC369会介绍许多历史中存在过的文件系统例如fat, ext2等等，CSC369的第一个大作业也是设计并实现一个file system。 

concurrency是现代开发的一个主要问题,现代开发并不是一次只有一个程序在运行，而是会有许多的程序同时在运行，concurrency的目的是确保多个程序同时运行
且不会触发任何问题。这其中最常见的一种问题就是如何处理多个程序同时请求对一个资源的access。为了确保资源能被正确的access, CSC369会介绍不同的办法
例如semaphore, lock, conditional variable, 这里也会介绍到一个著名的并发问题叫做dining philosopher。
而CSC369第二个作业则是围绕着multi-threading的程序确保资源可以被正确access以及不会触发dead lock

virtualization的核心是给予物理地址一层虚拟化产生出virtual address(虚拟地址)同时分配给每一个程序一个virtual address space(虚拟地址空间)
使得每一个程序以为自己有一整个内存的假象，当程序需要access内存数据时，OS要负责将virtual address翻译到真正的物理地址,而这里就涉及到不同的翻译机制以及page。
CSC369第三个作业就是负责实现内存翻译以及各种page切换的算法

## 大体课设
- Assignment
    + File System
      
    + Multi-Threading
      
    + Virtual Memory
- Term Test
  
- Final

## 常驻教授
Karen Reid: Karen可以说是常驻在369的一位了，很多人在209就已经见过她了，Karen是个人很不错的教授，讲课也算清晰，你有问题她也会很愿意帮助你, 考试的内容也不会特别难为人，总体来说还是很不错的一位教授了

## 课程难度
CSC369这节课可以说是CS Specialist中的一节拦路虎。Workload可以说是CS前三年中相对比较大(甚至可以说是最大的一节)。这节课需要有很solid的C编程能力和
大量的时间来debug,这节课绝对不是可以你due前开始写还能写完拿高分的课。这节课的作业推荐大家一定要start early以及在上这节课的学期做好planning
确保自己不要有太大的workload。以及**强烈不建议**这件课和CSC373放在同一个学期上，很有可能就不用睡觉了(学霸例外)。

- 内容难度: 3.5 / 5

- 作业难度: 4 / 5

- Workload: 4.0 / 5

- Overall难度: 4.0 / 5