## 课程介绍
CSC373是CS Specialist中最后两节必修课中的theory课。CSC373承接了CSC263继续沿着CLRS往后讲。CSC373的着重点是各种算法的讲解和证明包括Divide and Conquer, Greedy Algorithm, 
Dynamic Programming, Network Flow, Linear Programming在讲完这些算法后会涉及到CS中一个最著名的topic即PNP问题，在PNP的最后会介绍approximation algorithm作为这节课的结尾

Divide and Conquer是解决问题中一种常见的思路即将问题分解成许多个小问题通过对每个小问题进行求解从而将解合并成为原问题的解。

Greedy Algorithm通常是为了解决最大化/最小化objective的问题而使用的，通过每次greedily选择intermediate objective从而获得最后的解。 但是Greedy并不能保证得出来的解永远是optimal的所以有了Dynamic Programming。

Dynamic Programming本质上和Divide and Conquer很像但Divide and Conquer有一个问题是对于重复出现的问题它会重复进行运算，
而Dynamic Programming则会使用称之为memorization的技巧来记住重复出现的问题的解从而不会重复进行运算，但如何设计DP算法和使用data structure来进行memorization则是DP的一个难点

Network Flow是一种图论问题,每个edge储存着一个点到另一点的可流量，Network Flow研究的问题即是一个图中从源点到终点最多可以输送多少流量。为此介绍了各种算法和max-flow min-cut定理

Linear Programming是一类优化问题，给予一个线性函数和对应的constraint，试图得出能最大化/最小化函数的解。这其中会涉及到duality的性质以及使用simplex来求解linear 
programming

PNP是CS理论上最著名的问题之一它也是千禧年7个问题中的一个(即人类史上最难挣的100万), PNP的主要方向是在complexity上，很多问题问题我们是可以在polynomial时间能解决出来的这类问题被称为P类问题，
但是同时有很多问题我们并**不知道**它们是否能在Polynomial内解决也就是所谓的NP类问题, 而这其中包括了NP, NP hard, NP complete, PNP问题的核心即P和NP是否相等(这个问题现在还并没有被解出来)。
题外话, 提出PNP这个问题的Stephen Cook也是UofT的教授不过已经退休了

Approximation是对于一些NP类问题通过一些算法从而使它们能在polynomial的时间内得到一个近似解(但并不是准确解)作为参考

## 大体课设
- 3 - 4 Written Homework

- Term Tests

- Final

## 常驻教授
Francois Pitt: Francois是目前为数不多完成了大一到大三所有theory课都执教过的人, 他上课的feedback都还不错讲课也很清晰，但考试和作业会偏难

Nisarg Shah: Nisarg是373教授中最年轻的一位，以前他讲课时经常就会手舞足蹈起来，上课十分活跃。他个人十分愿意给学生提供帮助, 作业和考试的难度也相对适中,还是一位不错的教授

Allan Borodin: Allan是theory group中的元老，他是十分博学的一个人，但他不是一个好的教授，他会经常讲着讲着就开始讲很多超出范围的东西，
从而使大家完全不知道他在讲什么以及他对难度的掌控并没有很好的把握。很不推荐上Allan的373

## 课程难度
CSC373作为CS Specialist最后一节theory必修课, 它的确可以说是一节天花板难度的课了。内容本身十分的抽象很需要花时间理解，同时作业和考试都很考察对知识的理解和运用，
以及需要一定的发散式思维。是一节需要花大量时间来学习的课。 强烈**不推荐**和CSC369在一个学期一起上
- 内容难度: 4.5 / 5

- 作业难度: 4 / 5

- Workload: 4.0 / 5

- Overall难度: 4.5 / 5
