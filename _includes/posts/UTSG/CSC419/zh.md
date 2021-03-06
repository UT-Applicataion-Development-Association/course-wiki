## 课程介绍
Geometry Processing是现在相对比较新颖的一个领域, Geometry Processing的主要内容是对3d物体的分析和操作。CSC419的主要内容也是教授这些操作和对应的知识包括reconstruction, alignment, denoising, shape deformation, surface parameterization, curvature.

Reconstruction: Reconstruction的本质是将无数3d扫描后的sample points重新构造成为一个3d的物体, 其中一种常用的做法就是Poisson Reconstruction, 在3d point cloud和normal vector的基础上通过gradient得到近似从而进行重建

Alignment: Alignment的目的是将一个物体和同一物体在不同位置不同视角下的扫描进行匹配从而使它们尽可能的重合, 为此介绍了Iterative Closest Point(ICP)算法根据sample points和要objective function来得出最优的rotation matrix和从而minimize objective function直到算法converge即表面互相重合

Denoising: Denoising的意义是对物体表面上进行去噪包括纹理 形状等等 在此会cover到Geometry Processing中十分常用的Cotangent Laplacian和Massmatrix

Deformation: Deformation主要的研究是模拟物体变形例如对物体进行拉展 旋转等等这里会介绍两种deformation的做法分别是biharmonic和as-rigid-as-possible

Parameterization: Parametrization的本质其实就是将3d surface通过2d进行表达, 常见的texture mapping(给物体添加纹理)也是parameterization的运用

Curvature: Curvature代表了物体表面的曲率许多算法可以根据Curvature来决定boundary condition

## 大体课设
- 7 Programming Assignments

- Paper Implementation

## 常驻教授
Alec Jacobson: Alec可以说是现在Geometry Processing的领头人之一,他在Geometry Processing上有很大的建树同时他自身的教课质量也是相当过硬 上课讲解也非常的清晰 十分推荐的一位教授

## 课程难度
CSC419对数学特别是calculus和optimization有很高的要求, 这节课课上主要是以讲解每一部分的数学原理为主,课后作业会要求实现课上的内容。CSC419作业的workload相对并不大但是它需要对内容要非常好的理解不然甚至没有办法开始作业。而最后的project是需要从提供的paper选择一个进行implementation和做presentation。

- 内容难度: 4 / 5

- 作业难度: 3.5 / 5

- Workload: 3.5 / 5

- Overall难度: 4 / 5