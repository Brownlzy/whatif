# 最长的落日
###### THE LONGEST SUNSET
### Q．假设你遵守交通法规不超速驾驶，并且在铺有路面的道路上行驶，那么你能观赏到的最长日落会持续多久？
<p align="right">——迈克尔·伯格</p>

***
### A．要回答这个问题，首先我们要确定什么叫“日落”。
这算是一个日落：

![1](./imgs/LS-1.png)

![2](./imgs/LS-2.png)

日落在太阳开始没入地平线的那一瞬间就算开始了，当太阳完全没入地平线以下之后日落也就结束了。如果太阳碰了一下地平线又重新升了起来，那这就不能称为日落。

要算得上日落，太阳必须没入理想地平线之下，而非只是躲在附近一座小山后面。以下这种情况虽然看起来像日落，但其实不是：

![3](./imgs/LS-3.png)

至于原因很简单：你不能随便躲在某个看不见太阳的障碍物后面就说太阳落下去了，否则你只要藏在石头背后就随时能够制造出一场日落。

注意我们要考虑折射情况。地球的大气层会使光线弯折，因而当太阳实际碰到地平线的时候，你会发现太阳实际比地平线高出一个身位。在所有常规的计算中这种情况的平均效应都已经被考虑在内，我这里也是。

如果你身处赤道，那么3月和9月的日落略微比2分钟多一点。在像伦敦这样靠近极点的地方，日落可能长达200～300秒。日落的持续时间在春季和夏季最短（在这些时候太阳直射点在赤道上方），在至日和春分（秋分）的时候最长。

如果你在早春3月在南极站定，太阳整天都高高挂在天上，在地平线上方绕一整个圈子。有时在3月21日前后太阳会落到地平线之下，这也是一年中唯一一次。这样的日落会长达38～40小时，这也意味着在日落的过程中太阳转了一整圈还不止。

但是迈克尔的问题问得很好。他问的是你在铺有路面的道路上能看到的最长的日落有多久。有一条路通向南极的科研站，但它没有铺路面——它是由雪堆出来的。两极附近都没有任何一条铺有路面的道路。

能够符合上述标准的离极点最近的道路估计是挪威斯瓦尔巴特群岛上朗伊尔城的主干道。（如果你能开到朗伊尔城中的机场跑道末端，你可以离极点更近一点，不过这么做你可能会惹上大麻烦。）

朗伊尔城离北极的距离比南极洲的麦克莫多站离南极的距离还近。还有一大把军事基地、研究站和钓鱼站离北极更近，不过它们都没有铺有路面的道路，有的只是用碎石或雪铺成的飞机跑道。

如果你在朗伊尔城中心城区[^1]闲逛，你能看到的最长的日落差几分钟满一小时。至于你有没有开车基本不会有什么影响，因为这个城市实在是太小了。

但如果你回到大陆上，那儿的道路更长，你会看到更长的日落。

如果你从热带地区开始驾车，一直在铺有路面的道路上行驶，那么能跑到的最北的地方是挪威的欧洲69号公路末端。斯堪的纳维亚北边有许多互相交叉的道路，因而那里是启程的好地方。但我们该选择哪条路呢？

从直觉上来看，我们要尽可能地往北跑。我们离极点越近，就越容易追上太阳。

但事实上试图追上太阳不是一个好的策略。即使你在像挪威这样的高纬度地区，太阳移动的速度还是太快了。在欧洲69号公路的尖端——从赤道开始通过铺有路面的道路你能达到的最北边的地方——你仍然需要以约音速的一半的速度才能赶上太阳。（而且欧洲69号公路是南北向，而不是东西向，所以一直开下去就会跌入巴伦支海。）

幸运的是，我们还有更好的办法。

当太阳在挪威北部靠近地平线时，晨昏线（terminator）以如下方式滑过大陆：

![4](./imgs/LS-4.png)

不要跟《终结者》系列中的终结者搞混了，它是这么移动的：

![5](./imgs/LS-5.png)
`我都不知道逃离哪一个要更容易。`[^2]

要想看到更长的日落，你的策略很简单：静静等待晨昏线正要达到你所在的位置。在晨昏线抵达你所在的位置之前乖乖地待在车里，晨昏线抵达之后你就往北开，尽可能长时间保持你在晨昏线前面一点点（取决于当地的道路布局），在撑不下去之后掉头往南开，速度越快越好，直到你进入黑暗处的庇护。[^3]

令人惊喜的是，这一招在北极圈内的任何地方都有差不多好的效果，因而你能在芬兰和挪威的许多道路上看到这么长的日落。我用PyEphem[^4]和挪威高速GPS记录搜索了一下能看到最久日落的驾驶路线，我发现在不同的路径和时速条件下，最长的日落差不多都是95分钟左右——比使用一动不动待在斯瓦尔巴特群岛这种策略提升了近40分钟的时间。

不过如果你被困在斯瓦尔巴特群岛而又想看到更长一点的日落——和日出——的话，你可以试试逆时针转动身体。[^5]是的，你可以多看到几分之一纳秒的风景，但如果考虑一下你是和谁在一起……

![6](./imgs/LS-6.png)

……这么做有可能是值得的。

[^1]:和“北极熊过马路”的标志拍张照。
[^2]:译注：terminator既可指晨昏线，又可指终结者。
[^3]:这招也适用于你遇上终结者的时候。
[^4]:译注：星历表计算软件。
[^5]:参考xkcd网站上“角动量”一章，[http://xkcd.com/162/](./imgs/angular_momentum.jpg)