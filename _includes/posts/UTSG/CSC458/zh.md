## 课程介绍
互联网的出现改变了人们的生活方式, 但是对计算机开发而言，Network(网络)可能是历史上最大同时最复杂的软件之一了。 CSC458这节课的主要内容就是介绍网络。
CSC458会简单概括网络架构的7层layer，这其中着重介绍其中的link layer, network layer, transport layer和每层layer中的protocol。

Link Layer的作用是使在一个局部范围内的网络群体可以互相传送数据也就是常说的局域网, 而ethernet(以太网)就是有线局域网中最常用的通信协议, CSC458会着重介绍使用ethernet进行通信的原理包括ethernet frame format, arp protocol

Network Layer是建立在Link Layer上使得原本只能在局部范围内通信的主机可以跨局域沟通，而IP protocol就是在Network Layer上实现的，跨局域通信的一个核心问题就是从起点到终点会跨域多个区域如何确保从起点到终点中的路径这个问题也就是所谓的routing(路由)。
CSC458会讲解IP的原理，IP地址，CIDR以及routing algorithm

Transport Layer是Network Layer的一个延伸也是现代互联网传输中最为核心的一层。Network Layer保证了两台主机可以跨区域沟通，而在主机上会有不同的程序，transport layer的作用就是可以让主机之间的程序互相沟通。
在Transport Layer里实现的protocol中最著名的一个就是TCP。CSC458会讲述TCP的工作原理和机制以及TCP的各种延伸

除了网络架构以外，CSC458还会穿插讲解网络学中的别的内容例如Middlebox, Security, Software-defined network

## 大体课设
- Two Major Assignments

- Term Test

- Final

## 常驻教授
Peter Josef Marbach: Peter是一个十分和蔼的教授，讲课质量是很不错的。他个人专攻与网络学里理论的部分，出卷的倾向会偏重于理论多一点。

Yashar Ganjali: Yashar也是十分和蔼的教授，也是最开始开设CSC458这节课的人，讲课质量也是很过硬的, CSC458用的slide基本都是他编写的。他偏向于实践部分，所以出卷的倾向会偏重于实践多

## 课程难度
CSC458是一节内容相对便实践的课，网络架构对于一个好的开发人员来说是必不可少的知识储备，如果之后想在开发这条路上走的远的朋友，你肯定会用上CSC458的内容的

- 内容难度: 3.5 / 5

- 作业难度: 3.5 / 5

- Workload: 4.0 / 5

- Overall难度: 4.0 / 5