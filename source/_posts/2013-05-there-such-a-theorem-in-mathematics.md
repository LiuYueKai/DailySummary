---
layout: post
title: 数学中竟然还有这样的定理！
date: 2013/05/11 11:24:00
categories: 
- 技术
tags: 
---

谁说数学是枯燥的？在数学里，有很多欢乐而又深刻的数学定理。这些充满生活气息的数学定理，不但深受数学家们的喜爱，在数学迷的圈子里也广为流传。

**喝醉的小鸟** 

![](https://ww4.sinaimg.cn/large/006tNc79gw1fahpm6lsz9j30dw08u3yr.jpg)

**定理：喝醉的酒鬼总能找到回家的路，喝醉的小鸟则可能永远也回不了家。** 

假设有一条水平直线，从某个位置出发，每次有 50% 的概率向左走1米，有50%的概率向右走1米。按照这种方式无限地随机游走下去，最终能回到出发点的概率是多少？答案是100% 。在一维随机游走过程中，只要时间足够长，我们最终总能回到出发点。 现在考虑一个喝醉的酒鬼，他在街道上随机游走。假设整个城市的街道呈网格状分布，酒鬼每走到一个十字路口，都会概率均等地选择一条路（包括自己来时的那条路）继续走下去。那么他最终能够回到出发点的概率是多少呢？答案也还是 100% 。刚开始，这个醉鬼可能会越走越远，但最后他总能找到回家路。 不过，醉酒的小鸟就没有这么幸运了。假如一只小鸟飞行时，每次都从上、下、左、右、前、后中概率均等地选择一个方向，那么它很有可能永远也回不到 出发点了。事实上，在三维网格中随机游走，最终能回到出发点的概率只有大约 34% 。 这个定理是著名数学家波利亚（George Pólya）在 1921 年证明的。随着维度的增加，回到出发点的概率将变得越来越低。在四维网格中随机游走，最终能回到出发点的概率是 19.3% ，而在八维空间中，这个概率只有 7.3% 。 

**“你在这里”** 

![](https://ww3.sinaimg.cn/large/006tNc79gw1fahpm95n7gj30dw0ajmyt.jpg)

**定理：把一张当地的地图平铺在地上，则总能在地图上找到一点，这个点下面的地上的点正好就是它在地图上所表示的位置。** 

也就是说，如果在商场的地板上画了一张整个商场的地图，那么你总能在地图上精确地作一个“你在这里”的标记。 1912 年，荷兰数学家布劳威尔（Luitzen Brouwer）证明了这么一个定理：假设 D 是某个圆盘中的点集，f 是一个从 D 到它自身的连续函数，则一定有一个点 x ，使得 f(x) = x 。换句话说，让一个圆盘里的所有点做连续的运动，则总有一个点可以正好回到运动之前的位置。这个定理叫做布劳威尔不动点定理（Brouwer fixed point theorem）。 除了上面的“地图定理”，布劳威尔不动点定理还有很多其他奇妙的推论。如果取两张大小相同的纸，把其中一张纸揉成一团之后放在另一张纸上，根据布劳威尔不动点定理，纸团上一定 存在一点，它正好位于下面那张纸的同一个点的正上方。 这个定理也可以扩展到三维空间中去：当你搅拌完咖啡后，一定能在咖啡中找到一个点，它在搅拌前后的位置相同（虽然这个点在搅拌过程中可 能到过别的地方）。 

**不能抚平的毛球** 

![](https://ww3.sinaimg.cn/large/006tNc79gw1f5127yhdj9j30dw0dwq48.jpg)

**定理：你永远不能理顺椰子上的毛。** 

想象一个表面长满毛的球体，你能把所有的毛全部梳平，不留下任何像鸡冠一样的一撮毛或者像头发一样的旋吗？拓扑学告诉你，这是办不到的。这叫做毛球定理（hairy ball theorem），它也是由布劳威尔首先证明的。用数学语言来说就是，在一个球体表面，不可能存在连续的单位向量场。这个定理可以推广到更高维的空间：对于任意一个偶数维的球面，连续的单位向量场都是不存在的。 毛球定理在气象学上有一个有趣的应用：由于地球表面的风速和风向都是连续的，因此由毛球定理，地球上总会有一个风速为 0 的地方，也就是说气旋和风眼是不可避免的。

**气候完全相同的另一端** 

![](https://ww1.sinaimg.cn/large/006tNc79gw1fahpmdilnnj30dw0dfq5i.jpg)

**定理：在任意时刻，地球上总存在对称的两点，他们的温度和大气压的值正好都相同。** 

波兰数学家乌拉姆（Stanisław Marcin Ulam）曾经猜想，任意给定一个从 n 维球面到 n 维空间的连续函数，总能在球面上找到两个与球心相对称的点，他们的函数值是相同的。1933 年，波兰数学家博苏克（Karol Borsuk）证明了这个猜想，这就是拓扑学中的博苏克-乌拉姆定理（Borsuk–Ulam theorem）。 博苏克-乌拉姆定理有很多推论，其中一个推论就是，在地球上总存在对称的两点，他们的温度和大气压的值正好都相同（假设地球表面各地的温度差异和大气压差异是连续变化的）。这是因为，我们可以把温度值和大气压值所有可能的组合看成平面直角坐标系上的点，于是地球表面各点的温度和大气压变化情况就可以看作是二维球面到二维平面的函数，由博苏克-乌拉姆定理便可推出，一定存在两个函数值相等的对称点。 当 n = 1 时，博苏克-乌拉姆定理则可以表述为，在任一时刻，地球的赤道上总存在温度相等的两个点。对于这个弱化版的推论，我们有一个非常直观的证明方法：假设赤道上有 A、B 两个人，他们站在关于球心对称的位置上。如果此时他们所在地方的温度相同，问题就已经解决了。下面我们只需要考虑他们所在地点的温度一高一低的情况。不妨假设，A 所在的地方是 10 度，B 所在的地方是 20 度吧。现在，让两人以相同的速度相同的方向沿着赤道旅行，保持两人始终在对称的位置上。假设在此过程中，各地的温度均不变。旅行过程中，两人不断报出自己 当地的温度。等到两人都环行赤道半周后，A 就到了原来 B 的位置，B 也到了 A 刚开始时的位置。在整个旅行过程中，A 所报的温度从 10 开始连续变化（有可能上下波动甚至超出 10 到 20 的范围），最终变成了 20；而 B 经历的温度则从 20 出发，最终连续变化到了 10。那么，他们所报的温度值在中间一定有“相交”的一刻，这样一来我们也就找到了赤道上两个温度相等的对称点。

**平分火腿三明治** 

![](https://ww4.sinaimg.cn/large/006tNc79gw1fahpmfghjwj30dw0933zk.jpg)

**定理：任意给定一个火腿三明治，总有一刀能把它切开，使得火腿、奶酪和面包片恰好都被分成两等份。** 

而且更有趣的是，这个定理的名字真的就叫做“火腿三明治定理”（ham sandwich theorem）。它是由数学家亚瑟•斯通（Arthur Stone）和约翰•图基（John Tukey）在 1942 年证明的，在测度论中有着非常重要的意义。 火腿三明治定理可以扩展到 n 维的情况：如果在 n 维空间中有 n 个物体，那么总存在一个 n - 1 维的超平面，它能把每个物体都分成“体积”相等的两份。这些物体可以是任何形状，还可以是不连通的（比如面包片），甚至可以是一些奇形怪状的点集，只要满足点集可测就行了。 

From:果壳网 