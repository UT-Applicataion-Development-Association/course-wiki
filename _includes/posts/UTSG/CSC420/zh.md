## 课程介绍
图像识别可以说是现在AI十分流行以及前沿的一个领域, 人眼是十分高精度可以识别出许多的东西, 但是对于计算机而言一张照片的本质其实就是一个2d的array,每一位代表一个pixel, 
从计算机的角度来看, 一张照片就是一堆的数字，它没有办法直接作出任何的决定。 而CSC420主要介绍的就是通过不同的算法来对这些pixel进行筛选和分析其中包括Edge Detection, Corner Detection, SIFT, Camera Model。

Edge Detection: Edge Detection可以说是Image Understanding里的敲门砖, CSC420介绍了两种detect edge的办法分别是Canny Edge Detector和Laplacian of Gaussian。这两种都是通过对照片使用不同的filter之后对照片内的pixel进行筛选从而得出结果

Corner Detection: Corner是在Image中常见的一种feature,corner可以被拿来做image matching, 一种常用的在Image中找寻Corner的办法就是Harris Corner Detection, 它的原理是根据Image gradient和Weighted Matrix对照片内的pixel进行过滤得出照片的corner

SIFT: SIFT的全程是Scale-invariant feature transform, SIFT的意义是在于即使在照片进行尺寸变化和旋转后SIFT依旧可以检察出照片中的特征。SIFT通过Difference of Gaussian组建了一组Image Pyramid从而使得SIFT可以对尺寸发生变化后的照片进行检测同时计算keypoint neighbour的gradient magnitude和orientation用来做旋转检测。

Hologram: Hologram的核心是将视角从2d切换到3d它的重点是通过camera mode来将2d坐标转换为3d坐标 从而实现3d视角

## 大体课设
- 4 Programming Assignments

- Team Project

## 常驻教授
Morteza Rezanejad: Morteza是新加入UofT的一位教授,他个人不太喜欢重复回答一些问题, 他一般对这些问题他会说他在哪里有回答过让你去refer。但除此之外 大多数问题他是愿意给你解答的而且也会给一定的hint 总体还是可以的一位教授

## 课程难度
CSC420是相对便实际运用的一节课,它会讲解image understanding中的算法和原理(但不会特别深入讲解原理)。Assignment会有written和programming两个part分别是对应简答和algorithm实现。而最后的project则是从给定的topic中选择一个做实现而Project通常会需要涉及到machine learning的知识。总体来说是一节便向入门CV的课

- 内容难度: 3.5 / 5

- 作业难度: 3.5 / 5

- Workload: 3.5 / 5

- Overall难度: 3.5 / 5
