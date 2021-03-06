## 课程介绍
CSC384是AI的introduction，但这个AI可能和很多人预期里的AI相差有点大，现在来讲AI代表的都是十分酷炫的产品，例如自动翻译，语音识别等等。但这些是随着现在的发展AI所扩展出的领域，
最初的AI的设计其实只是一个能有着很大算力来穷尽问题从而找到问题最好的解的这样一个软件，而这也是CSC384要介绍的AI。AI的本质其实就是通过做Searching来找到最优解,但随着问题的复杂AI所需要进行的search以及AI的策略也会变得不同。
CSC384会着重介绍4种和AI searching有关的策略分别是basic search, multi-agent search, constraint satisfaction和probabilistic reasoning。 最后CSC384会讲解knowledge representation即如何将人类可以理解的知识转化为计算机可以理解的形式。

Basic Search是相对基本的内容它建立在单agent无constraint的前提下进行其中包含了BFS, DFS, Heuristic Search和A* Search, 以及这些algorithm的变形例如path checking, cycle checking等等

Multi-agent是当多于一个agent进行zero-sum game时要进行的策略，而最常用的一个algorithm便是minimax algorithm, minimax的一个弊端是它会对所有可能进行search但其中很多可能是不会在游戏中出现的, 
为了减少搜素量,一个必要的技巧就是pruning(剪枝),一个在minimax的基础上添加了pruning的经典算法就是alpha-beta pruning

Constraint Satisfaction则是当agent需要在有constraint的背景下进行searching(例如数独中不允许任何的重复), CSP的重点在于如何在有constraint的前提下进行选择以及进行当agent进入一个dead state的时候需要进行backtrack(回溯)

Probabilistic Reasoning则是让agent可以根据probabilistic model来进行选择, 而这里则会涉及到probability, bayes network和hidden markov chain对应的知识

## 大体课设
- 4 Programming Assignments

- Term Test

- Final

## 常驻教授
Fahiem Bacchus: Fahiem是一位知识渊博同时十分和蔼的老爷爷,他每件课用的slides页数特别多，但是内容都会放在slides上，基本上无论是考试复习还是写作业时都可以参考下slides, 作业和考试来讲相对都算fair 挺推荐的一位教授

## 课程难度
CSC384可能的确和很多人预期差了很多，但是它讲述的AI的技巧却都是现在依旧能用得到的，例如minimax, pruning, backtrack。内容相对不算抽象和复杂，好好听课基本上都没什么太大问题

- 内容难度: 3 / 5

- 作业难度: 3 / 5

- Workload: 3 / 5

- Overall难度: 3 / 5