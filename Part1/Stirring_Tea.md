# 搅拌加热
###### STIRRING TEA
### Q．有次我在漫不经心地搅拌一杯热茶时突然想到：“咦，我不是在往这杯茶里输入动能嘛。”我知道搅拌能够加速茶的冷却，但如果我搅拌得快一些呢？我能不能通过搅拌的方式把一杯茶烧开呢？
<p align="right">——威尔·埃文斯</p>

***
### A．不能。
不过你说的基本原理是有道理的。温度其实就是（分子）动能的体现。当你搅拌茶的时候，你就在增加它的动能。这些动能总得有个去处，既然这杯茶没有从桌子上升起来也没有发光，那么这些动能最后肯定变成热了。

![1](./imgs/ST-1.png)   
`一定是我泡茶的方式不对！`

至于你为什么没有觉察到这些热量，是因为这些热量并不多。加热水需要大量热量，按体积来说，水的比热容比其他任何一种常见物质都要大。[^1]

如果你想要在2分钟内把水从室温加热到接近沸点，你需要有很大的功率：[^2]

![2](./imgs/ST-2.png) 

上面的公式告诉我们如果你想在2分钟内变出一杯热茶，那么你需要有一个700瓦的热源。微波炉一般来说有700～1100瓦，用它的确只需2分钟就可以做出一杯热茶。理论和现实一致的感觉真好！[^3]

将一杯水以700瓦的功率加热2分钟会使水吸收非常多的能量。当水从尼亚加拉瀑布顶端落下时会获得动能，到了瀑布底部这些动能变成了热能。但即使是下落了如此长的距离，水的温度也只是上升了0.12℃。[^4]要把一杯水烧开，你需要让它从大气层顶部以上的高度落下来。

![2](./imgs/ST-2.png)   
`英国版的菲利克斯·鲍姆加特纳`

那么搅拌和微波炉加热比起来有什么区别呢？

从工业混合机工程手册上的数字来看，我估计剧烈搅拌一杯茶增加热能的速率约为十万分之一瓦。这完全可以忽略不计。

而搅拌所产生的物理效果则要复杂一些。[^5]茶杯里绝大多数的热量都被茶杯上方对流的空气带走了，也就是说空气使得茶从上至下冷却。搅拌使得茶杯底部的热水被带到表层，因而加快了散热的速度。但同时还发生了其他事情——搅拌也扰乱了空气流动，使得茶杯壁温度升高，但没有数据，这种讨论没有太大意义。

但别忘了我们有互联网！StackExchange用户drhodes恰好测量了搅拌、不搅拌、不停把勺子浸入和拿出对茶冷却速率的影响。而且drhodes不仅上传了高分辨率的图像，还上传了原始数据，这可比许多论文提供的信息有用多了。

结论：不管你是不停搅拌，拿勺子放进去或者干脆啥事都不做，茶冷却的速度都差不多。（虽然拿勺子不停放进放出能让茶冷却得略微快一些。）

于是我们又回到了最初的那个问题：我们能够靠拼命搅拌把茶烧开吗？

不能。

首先是因为功率。700瓦差不多是1马力，所以要是你想在2分钟内把茶烧开，那么你至少需要一匹马帮你来拼命搅拌。

![3](./imgs/ST-3.png) 

当然了你可以通过延长做功时间来降低对功率的要求。只是如果时间太长的话，茶冷却的速度就要和你加热的速度一样快了。

即使你能以极高的速度搅拌——比如每秒成千上万转——流体力学会让你失望的。在这种高转速下，茶会发生空化；蒸汽泡会沿着勺子的路径生成，此时搅拌的效率会大大下降。[^6]

而如果你真的拼命搅拌到茶发生了空化，那么它的表面温度会急速增加，然后它会在几秒钟内冷却到室温：

不管你搅拌得多么拼命，茶都不会变暖。

![4](./imgs/ST-4.png) 

[^1]:按质量来算氢气和氦气有更大的比热容，但是它们是扩散性气体。剩下唯一一种按质量算有更大比热容的常见物质是氨。但如果按体积算的话，这三者都比不过水。
[^2]:注意：把即将沸腾的水加热到煮沸状态比把水从室温加热到接近煮沸的状态需要更多的能量——这些能量叫作蒸发能。
[^3]:如果水不够热，我们就会归咎于“效率太低”或者“涡流影响”。
[^4]:尼亚加拉瀑布的高度×重力加速度/水的比热容＝0.12℃
[^5]:在某些情况下混合液体能保持温暖。热水会上升，如果水体足够大并且足够静止（比如大海），表面就会形成一个热层。热层比冷层散热的速度更快，所以如果你用加水的方式扰乱这个热层，那么整体散热的速度就会下降。这也是为什么飓风停止前进力量就会大大减弱——停滞的大风会将海洋深层的冷水带上表面，切断飓风与表面热层之间的联系，而大洋表面的热层正是飓风的动力来源。
[^6]:有一些内置腔体的搅拌机确实就是这么加热内容物的，但问题是谁会这么无聊用搅拌机来沏茶？