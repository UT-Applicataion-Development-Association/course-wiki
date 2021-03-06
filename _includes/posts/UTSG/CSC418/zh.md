## 课程介绍
CSC418是把程序员三大浪漫中Computer Graphics(图形学)推上舞台的课。Computer Graphics和
Computer Vision是有本质上的区别的, 简单来说Computer Vision是将一张照片作为输入, 通过各种算法分析出这张照片里各种信息。而Computer Graphics则是根据算法做出一张照片或者特效, 常说的
CG特效其实就是指graphics。CSC418是从入门开始讲解graphics主要内容包括raster image, ray casting, ray tracing, boundary volume hierarchy, mesh, shader pipeline, kinematics, mass-spring system。课程的最后会要大家根据课上学的内容自由发挥做一个project

Raster Image: Raster Image可以说是最常见存储图像的一种方式, 简单来说一个Raster Image就是一个二维的Array每一位储存着对应的pixel value也就是对应位置上的光强, 对一张raster image的操作本质就是对array进行操作

Ray Casting: Ray Casting是成像的第一步, Ray casting的主要职责是生成光源 发射光线 从而与物体相交

Ray Tracing: Ray Tracing是一套成像的框架, 简单来说Ray Tracing需要首先通过ray casting生成光源每次与物体相交时需要根据规则进行反射 折射还有吸收 直到光源消失 便有了成像

Boundary volume hierarchy: 图案渲染中一个核心的问题是计算射线与物体的交点位置, 但通常它需要庞大的计算量以及会遇到并不需要考量的物体, 所以为了提高效率便介绍了Boundary Volume Hierarchy。Boundary Volume Hierarchy的本质也是Data Structure将物体位置进行augmentation从而减小计算量

Mesh: 在Graphics中物体的一种主流表达方式是通过mesh(网格)。mesh是有两个大部分组成分别是位置信息和拓扑信息。位置信息储存一个网格顶点的位置,拓扑信息则是网格和网格之间如何连接在一起。从而通过这两部分可以构造出mesh用来还原一个3d物体

Shader Pipeline: Shader Pipeline主要讲述的是GPU从CPU接受信息到输出位置的一整流水线包括着色, 转化, 投影等等

Kinematics: Kinematics主要讲述的是如何通过不同的算法来模拟物体运动

Mass-Spring System: 模拟物理变形的一套常用方法就是Mass-Spring System(弹簧质点系统)。Mass Spring System由质点和弹簧构成, 每一个质点包含一系列多个弹簧连接的质点, 从而可以通过time integration来进行物理模拟

## 大体课设
- 8 Programming Assignments

- Term Test

- Project

- Final

## 常驻教授
Alec Jacobson: Alec可以说是改变了CSC418这节课的一个教授,CSC418里很多内容都是由他扩充进来的。Alec本身也是一个十分博学且讲课质量非常过硬的教授,他也十分欢迎给学生解答问题,是个非常棒的教授

David Levin: David是位很有幽默感的教授, 上课经常讲着就会穿插着各种金句出来, 总之上David的课是不会无聊的。和Alec一样David也是专业背景和讲课都很过硬同时也很亲民的教授

## 课程难度
CSC418是一节内容十分有趣但相对workload偏大的一节课。每周的programming assignment对应着课程每一周所讲述的知识是对上课内容一个很好的复习, 但每个作业会需要大量的时间在debug所以临due再开始写是会吃苦头的。同时这节课是一节对C++和Linear Algebra都有一定要求的课, 特别是课程后期想要能理解课上的内容需要有好的linear algebra的背景, 推荐在上CSC418之前复习一下Linear Algebra。但总体是一节很有意思的课

- 内容难度: 3.5 / 5

- 作业难度: 3.5 / 5

- Workload: 4 / 5

- Overall难度: 4 / 5
