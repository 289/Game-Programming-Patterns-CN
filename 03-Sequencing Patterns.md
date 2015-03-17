# 序列模式
============================

Videogames are exciting in large part because they take us somewhere else. For a few minutes (or, let’s be honest with ourselves, much longer), we become inhabitants of a virtual world. Creating these worlds is one of the supreme delights of being a game programmer.

视频游戏很大程度会让我们兴奋是因为它们把我们带到了其他地方。在几分钟（或者，坦率讲，时间更长）里，我们成为了虚拟世界的人。创建这些世界是作为游戏程序员的最高乐趣之一。

One aspect that most of these game worlds feature is time — the artificial world lives and breathes at its own cadence. As world builders, we must invent time and craft the gears that drive our game’s great clock

从一方面来讲，大多数游戏世界的特征便是时间————虚拟世界按照自己的节奏运行着。作为世界的建造者，我们必须创造时间和打磨用来驱动游戏巨大时钟的齿轮。（译者注：这里作者用了比喻来说明问题）

<!-- @Henry-T: 中文破折号是 ———— -->

<!-- @Henry-T: 作者并不强调invent和craft意义上的差别，可以统一译为“创造”。因此，句式可以简化成： -->
<!-- 作为世界的建造者，我们必须创造时间以及驱动游戏这个巨大时钟的齿轮。 -->

<!-- @Henry-T: 比喻很明显啦，“译者注”这里可以去掉 XD -->


The patterns in this section are tools for doing just that. A Game Loop is the central axle that the clock spins on. Objects hear its ticking through Update Methods. We can hide the computer’s sequential nature behind a facade of snapshots of moments in time using Double Buffering so that the world appears to update simultaneously.

在本节中的模式便是用来做那样工作的工具。[游戏循环](03.2-Game Loop.md)是时钟旋转的中心轴，对象通过[更新方法](03.3-Update Method.md)来聆听它的滴答声。我们可以通过[双缓冲](03.1-Double Buffer.md)来及时的将计算机的连续性隐藏在时刻快照之后，从而使得游戏世界能够同步更新。

<!-- @Henry-T: that直接翻译成那样，似乎没英文读着顺畅，是否可以补充上下文？ -->
<!-- 本节中的模式便是用来创造它们的工具。 -->

<!-- @Henry.T:  simultaneously 直接理解有点绕，可以把它展开了说。 -->
<!-- 我们可以通过[双缓冲]()把计算机顺序处理的本质隐藏在一个个时间片之后，使得游戏世界中的所有物体看起来是一起更新的。 -->


## 本章模式

-  [双缓冲](03.1-Double Buffer.md)
-  [游戏循环](03.2-Game Loop.md)
-  [更新方法](03.3-Update Method.md)
