---
timezone: Pacific/Auckland
---

> 请在上边的 timezone 添加你的当地时区，这会有助于你的打卡状态的自动化更新，如果没有添加，默认为北京时间 UTC+8 时区
> 时区请参考以下列表，请移除 # 以后的内容

timezone: Pacific/Honolulu # 夏威夷-阿留申标准时间 (UTC-10)

timezone: America/Anchorage # 阿拉斯加标准时间 (UTC-9)

timezone: America/Los_Angeles # 太平洋标准时间 (UTC-8)

timezone: America/Denver # 山地标准时间 (UTC-7)

timezone: America/Chicago # 中部标准时间 (UTC-6)

timezone: America/New_York # 东部标准时间 (UTC-5)

timezone: America/Halifax # 大西洋标准时间 (UTC-4)

timezone: America/St_Johns # 纽芬兰标准时间 (UTC-3:30)

timezone: America/Sao_Paulo # 巴西利亚时间 (UTC-3)

timezone: Atlantic/Azores # 亚速尔群岛时间 (UTC-1)

timezone: Europe/London # 格林威治标准时间 (UTC+0)

timezone: Europe/Berlin # 中欧标准时间 (UTC+1)

timezone: Europe/Helsinki # 东欧标准时间 (UTC+2)

timezone: Europe/Moscow # 莫斯科标准时间 (UTC+3)

timezone: Asia/Dubai # 海湾标准时间 (UTC+4)

timezone: Asia/Kolkata # 印度标准时间 (UTC+5:30)

timezone: Asia/Dhaka # 孟加拉国标准时间 (UTC+6)

timezone: Asia/Bangkok # 中南半岛时间 (UTC+7)

timezone: Asia/Shanghai # 中国标准时间 (UTC+8)

timezone: Asia/Tokyo # 日本标准时间 (UTC+9)

timezone: Australia/Sydney # 澳大利亚东部标准时间 (UTC+10)

timezone: Pacific/Auckland # 新西兰标准时间 (UTC+12)

# ZK 残酷共学第 1 期残酷指引

> ⚠️ 正式开始前请确保你在身体上和精神上都处于合适的状态，请刻意练习，残酷面对 🆒。为方便检索 The First ZK Intensive CoLearning 简写为 ZICL1st，第 2 期即为ZICL2nd，第 3 期即为 ZICL3rd，以此类推。

> ⚠️ 报名需要按要求认真填写下面 [ XXX ] 部分，方可通过报名审核，通过审核即可开始自主学习。

## 共学内容

第一期的重点是向大家介绍什么是 ZK、 ZKP 的基础知识，以及 Circom 代码入门，有一定难度，共学资料如下：

- 第一周：7 月 29 日 - 8 月 4 日：Introduction and History of ZKP
    - 20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
    - 70min 的播客：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
    - [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
    - [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
    - [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
    - 100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 第二周：8 月 5 日 - 8 月 11 日：Overview of Modern SNARK Constructions
    - 80min的视频： [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
    - [1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)
    - [2-Non-interactivity&Distributed-Setup](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html)
    - [3-General-Purpose-Computation](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html)
    - [4-Construction-Properties.md](https://learn.z2o-k7e.world/zk-snarks/4-Construction-Properties.html)
    - [5-Pinocchio-Protocol](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html)
- 第三周：8 月 12 日 - 8 月 18 日：Write some Circom
    - 基础电路：
        - [ZK Shanghai 基础电路教学](https://www.youtube.com/watch?v=CTJ1JkYLiyw&ab_channel=SutuLabs)
        - 编辑器：[zkREPL](https://zkrepl.dev/)
        - [基础电路练习](https://github.com/wenjin1997/zkshanghai-workshop/blob/main/lecture2-homework.md) 这部分材料结合了Circom源码，可以多花时间来研究
    - 实用电路：
        - [ZK Shanghai 实用电路教学](https://www.youtube.com/watch?v=smJz5RdY0Nc)
        - 课程资源：[snarkjs resources (zkiap.com)](https://zkiap.com/snarkjs)、[What Is Semaphore? | Semaphore](https://docs.semaphore.pse.dev/)

本次共学资料前两周的 lecture 来自 [zk-learning](https://zk-learning.org/)，博客来自 [《探索零知识证明系列》](https://learn.z2o-k7e.world/zkp-intro/toc.html)和[《从零开始学习 zk-SNARK》](https://learn.z2o-k7e.world/zk-snarks/toc.html)，第三周的 Circom 部分来自 [0xparc](https://zkiap.com/)，视频讲解为 [ZK Shanghai](https://zkshanghai.xyz/) 的中文版本。郭宇老师还推荐了这篇文章[《Survey-SNARKs》](https://www.di.ens.fr/~nitulesc/files/Survey-SNARKs.pdf)，学有余力者可以依此找到更多的扩展内容。

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# {Punkcan}
1. 自我介绍
	1. 现在是个普通上班族，编程，数据库，服务器，杂七杂八的都会一点点。
2. 你认为你会完成本次残酷学习吗？
	1. 这个较难，我降低一下预期55.335%
3. 目前阶段对于 ZK 的了解？
	1. 还在理解公式中

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：ZK入门影片
- 学习内容小结：
	- 说法一：对一个陈述的证明，但是你不用阐述原因或是陈述的内容
		- 不展示陈述，但可以展示陈述的一部分所转换出来的证据
		- 直到对方被说服
		- 从这个角度来看，验证者如何承认自己被说服，而且这个承认的风险要极低等于零，便可以完成ZKP
	- 说法二：例如有一个保险箱，我知道密码，但我不能跟你讲密码，于是我取出一个保险箱里面存在的东西，这样就可以证明我知道密码
	- 说法三：例如我知道地图原本的颜色，而且他们之间相邻不会有相同颜色
		- 你随机抽取两个相邻地图，打开确认不是一样颜色
		- 然后我把所有颜色替换了，例如黄色改蓝色，蓝色改绿色，绿色改红色，红色改黄色
		- 你再挑选两张，发现还是不同颜色
		- 当我们重复1000次之后，你就可以确定，我真的知道地图原本的颜色了
	- 说法四：我正在浏览网站，浏览器不需要知道谁浏览什么网站，但却可以知道该网站被浏览的频率
		- 其中提到一点，随机性是不可预测，但这种不可预测正好可以用来掩盖真实的信息
		- ZK有个特性，就是种类非常的多
	- 为什么用数学表达？因为用数学表达反而是简化了ZK的概念，让ZK更容易被应用
	- 但ZK有点像是一直持续探索的领域，因为现在要不是披露都信息太多，就是要验证的次数太多，因此披露信息跟验证次数的平衡度也是一个抉择点
	- 在编程的领域算是ZKP发展的一个转捩点，过去ZKP大多在数学领域发展

	

### 2024.07.30

- 学习主题：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
- 学习内容小结：
	- 技术的创新并不一定能落实在特定产品上，但随着时间，因为特定例如算力或是区块链等突破，就会出现转机
	- 所以ZK是需要高算力？
	- 前两个课程大多是在讲历史跟概念
	- 区块链上几个主要的ZK设计（AI回答的，努力理解中）
		- ### SNARKs
			- **比喻**：想象你有一个非常复杂的迷宫，你知道怎么走出去。你想告诉你的朋友你确实知道路径，但不想让他们知道具体的每一步。SNARKs 就像是你给朋友一个非常简短的说明，让他们确信你知道出口，而不需要他们自己走迷宫。

			- **原理**：SNARKs 通过生成一个简短的证明（就像迷宫的说明），让验证者可以快速验证你确实知道路径（解决方案），而不用自己走完整个迷宫。

		- ### STARKs

			- **比喻**：现在假设你有一个巨大的拼图，并且你已经拼好了。你想让朋友知道你确实完成了拼图，但不想展示整个拼图。STARKs 就像是你给朋友一张透明的纸，上面有拼图的边缘轮廓和几个关键点，让他们知道你确实完成了拼图，而不需要看到每一块拼图。
			
			- **原理**：STARKs 生成一个证明，这个证明不需要任何秘密参数，且可以处理非常大的数据量，同时还能对抗未来的量子计算机攻击。
		
		- ### Bulletproofs
		
			- **比喻**：假设你有一本秘密的日记，你想证明给朋友看你确实写了某件事，但不想让他们看整本日记。Bulletproofs 就像是你给朋友看日记中一小段被验证过的文字，证明你确实写了那件事，但他们看不到其他内容。
		
			- **原理**：Bulletproofs 生成一个短小的证明，验证者可以用这个证明验证特定的内容，而不需要看到所有的内容。它不需要秘密设置，适用于隐私保护。
		
		- ### ZK-Rollups
		
			- **比喻**：假设你有很多张卡片，每张卡片上都写了一个秘密，你想让朋友相信你知道所有这些秘密。ZK-Rollups 就像是你把所有卡片装进一个信封，然后给朋友看信封外面的一张标签，标签上写着一个简短的证明，证明你确实知道信封里的所有秘密。
			
			- **原理**：ZK-Rollups 把大量交易打包成一个批次，然后生成一个简短的证明，把这个证明放在区块链上，这样区块链只需要处理这个简短的证明，而不是每一笔交易。
		
		- ### Plonk
		
			- **比喻**：假设你有一个非常复杂的谜题，你想证明你知道答案，但不想展示整个解答过程。Plonk 就像是你给朋友一个简短的解答步骤，让他们确信你确实解开了谜题，而不需要看到整个解答过程。
			
			- **原理**：Plonk 是一种更通用的零知识证明，它生成一个简短的证明，让验证者可以验证你确实知道答案，而不需要看到所有的解答步骤。
	- **SNARKs**：简短证明，快速验证，适合复杂问题。
	- **STARKs**：高效处理大数据，无需秘密设置，对抗量子计算。
	- **Bulletproofs**：短小证明，隐私保护，无需秘密设置。
	- **ZK-Rollups**：批量处理交易，提高区块链扩展性。
	- **Plonk**：通用零知识证明，简短解答步骤。
- 问题：
	- 到底是如何证明的，我一个都看不懂，范围懂，概念懂，但是到底如何证明？例如ZK-Rollups，信封外面的一张标签是如何产生的，这个标签的证明又是什么？又如何验证证明是正确的？
### 2024.07.31

- 学习主题：深入了解一下 SNARKs
- 学习内容小结：
	- SNARKs 的解释中，这个「你给朋友一个非常简短的说明」会是什么样的说明？如何产生？为什么朋友能够相信这个说明？
		- 假设你有一个非常复杂的迷宫，你知道怎么走到出口。你想让你的朋友相信你确实知道怎么走出去，但不想让他们知道具体的每一步。
		- 迷宫的每个分岔路口和每条通道都可以转换成一个数学方程。
		- - 你需要证明你从入口走到了出口。你把所有的步骤（每个方程）进行计算，得到最终的解决方案。这个过程使用了一种叫做「多项式承诺」的数学工具，确保你的步骤是正确的。
		- 然后，你通过一个叫做「电路」的工具，把所有这些方程连接起来。这就像把迷宫的每条路都串起来，形成一个完整的路径。
		- 于是只要这个些方程是对的，就代表你是可以走出去的
		- 但是你又不能让人看到这些方程
		- 所以这个方程的结果会加密过，同时产生密文跟钥匙
		- 所以验证的人拿着钥匙，可以检查密文是不是真的，如果是真的，就可以认定你是能够通过迷宫的
		- 多项式承诺（Polynomial Commitment）用于证明一个多项式在给定点上的值和多项式的属性，而不需要显式地公开多项式的所有系数。
		- 提交者（Prover）能够生成一个承诺，该承诺表示某个多项式，但不公开多项式的具体形式，也不可变
		-  假设你有一个秘密的数学公式（多项式），比如  $$ P(x)=3x2+2x+1 $$
		- 你把这个公式“锁”起来，生成一个承诺 CCC。这个承诺就像是你把公式放进了一个加密保险箱中，并把保险箱的锁给别人看。
		- - 有人问你这个公式在某个特定数字 x0x_0x0​ 下的值是多少。比如，问你当 x=2x = 2x=2 时，公式的值是多少。
		- 你计算出这个值 $$ P(2) = 3 \times 2^2 + 2 \times 2 + 1 = 17 $$
		- 然后，你生成一个证明 π，证明你计算的这个值是正确的。
		- 问题来了，这个证明是如何产生？而且我产生的证明，为什么别人要相信？
		- 首先，验证的人必须要确定你的多项式不会变更
		- 你计算$$ π= \frac{P(x) - P(x_0)}{x - x_0} $$，这表示多项式 $$ P(x)$$ 去掉点 $$x0$$​ 后的商。
		- 证明 π\ 实际上是一个新的多项式。
		- 但这个验证流程是公开的
		- 验证者只要证明以下是正确的 $$ e(π,gx−x0​)=e(C,g)/e(gP(x0​),g) $$
		- 就能确定你的证明是真的
		- 这个证明的概念就是，当匹配的次数很多，但答案一致时，就可以认为你是对的
		- e(...,...)是一种双线性配对
		- g是公共生成元，你可以视为类似公钥的一种公开固定值
		- 算了，我们跳过公式，总之这个验证方式是公开的，几遍验证的人不知道你是不是对的
		- 但验证者知道，如果你的多项式是正确的，你的证明就会符合预期（另一个算式会是一致的）
		- 所以他只要用另一个算式来验证你的证明，只要一次就可以完成验证


### 2024.08.01

- 学习主题：模拟器.....
- 学习内容小结：
	- 为什么实体世界的Alice跟理想世界中的Zlice能够交互过程，让人无法区别？
		- 不是完全无法区别，是几乎无法区别
		- 这个Zlice模拟类似一种数学公式，就是能得到同样地答案或是判断，但是公式内容跟Alice却完全不一样，这样验证者就可以确定证明在Zlice得到的回应等于跟Alice交互得到的回应
		- 例如
			- #### 现实世界

				1. **初始承诺**：Alice发送一个数字y = x^2作为初始承诺。
				2. **随机挑战**：验证者发送一个随机数c。
				3. **生成响应**：Alice计算r = x + c，并发送给验证者。
				4. **验证**：验证者检查r^2是否等于y + 2xc + c^2。

			- #### 理想世界

				1. **初始承诺**：Zlice发送一个随机数字z作为初始承诺。
				2. **随机挑战**：验证者发送一个随机数c。
				3. **生成响应**：Zlice使用数学算法生成一个伪随机响应s。
				4. **验证**：验证者检查s是否满足与真实交互相同的验证条件。
		- 但这一切需要形成NP证明，也就是产出证明可能很麻烦，但是验证却很简单
			- 例如数独谜题。解开数独可能需要很长时间，但一旦你完成了，你的朋友可以在短时间内检查你的解答是否正确
			- 例如你要从城市里找到多点的路径是不是最短路径很麻烦，但是验证起来却很简单
			- **NP 问题**：解答可以在多项式时间内验证，但不一定能在多项式时间内找到。
			- **NP 证明**：用于验证 NP 问题解答的正确性，验证过程在多项式时间内完成。


### 2024.08.02

- 学习主题：发现自己欠缺很多基本知识，重新巩固基本知识
- 学习内容小结：
	- 先了解ZK所需要具备的基础知识有哪些，盘点自己对这些基础的认知程度
		- **离散数学**：逻辑，集合论，图论
		- 代数和数论：模运算，群（有限域上的运算，生成元与离散对数）、环和域，欧拉函数
		- 了解 P 和 NP 问题
		- 离散对数、因子分解
		- 理解概率论和统计学
	- GPT说其中最基础是模运算
		- 也就是很多范例常常讲的时钟概念
		- $$ a \equiv b \pmod{n} $$
		- 这意思就是当n去除以a或b时，得到的余数是一样
		- 例如你有五个朋友，当你有7颗苹果或是12颗苹果分给这五个朋友时，都会剩下两个
		- $$  12 \equiv 7 \pmod{5} $$
		- **在表达式中**：
		  - $$ n \mid (a-b) $$ 
		  - 这个部分表示 n 可以整除 a - b 。
		  -  a - b  是 n 的倍数，说明 a 和 b 的余数相同。
	- 例如凯撒密码就能用模运算来计算
	- 模运算适合用在有循环特质的分母中，例如星期，时钟，字母等等
	- 更深入的应用是RSA 加密算法，Diffie-Hellman 密钥交换，椭圆曲线密码学（ECC）
	- 上面讲的是模运算的基础公式，但其中a跟b跟n本身又可以是一个公式或是某数的多次方
	- 例如

		- **加密和解密**：
		  - **加密**：给定明文  m ，密文  c  是：
    $$
    c \equiv m^e \pmod{n}
    $$
		  - **解密**：给定密文  c ，明文  m  是：
    $$
    m \equiv c^d \pmod{n}
    $$
- 疑问：
	- 学ZK难道就得要先学会一堆数学吗？
		- 看起来是的....不会数学，很快就什么都看不懂了
	- 第二基础是群论，明天搞懂

### 2024.08.03

- 学习主题：初入群论
- 学习内容小结：
  - 群是什么？
    - **想象一个玩具箱**
    - **玩具箱（群）**：想象有一个玩具箱，里面装着不同的玩具，这些玩具就是群中的“元素”。
    - **玩法（运算）**：每次从箱子里拿出两个玩具，按照一定的规则来玩这个玩具，比如说把两个玩具组合在一起。
  - 也就是群运算是对群里元素的操作规则
  - 群有四个基本规则
    - **闭合性**：
      - 不管你怎么玩玩具，结果还是在这个玩具箱里。
      - **例子**：两个乐高积木拼在一起，还是乐高积木，依然在你的玩具箱里。
      - **定义**：对于群中的任何两个元素 a 和 b，运算 (a + b) 的结果仍然在群内。
      - **算式例子**：在整数集合 Z 中，a = 3 和 b = 5，那么  a + b = 8  也在 Z 中。
      - 3 + 5 = 8
	
    - **结合律**：
      - 你可以先把前两个玩具拼好，再和第三个玩具拼在一起，或者先拼后两个玩具，结果是一样的。
      - **例子**：你可以先拼一个房子，再加上一个车库，或者先拼车库，再拼房子，最后都是一个大建筑。
      - **定义**：运算的顺序对结果没有影响，(a + b) + c = a + (b + c)。
      - **算式例子**：对于 a = 2、b = 3、c = 4，不管你先加哪个结果都一样。
      - (2 + 3) + 4 = 9 和 2 + (3 + 4) = 9

    - **单位元**：
      - 玩具箱里有一个特别的玩具，任何玩具跟它一起玩都不改变其他玩具的样子。
      - **例子**：一个透明的底板，任何乐高积木放在上面都不会改变积木本身。
      - **定义**：存在一个单位元 e，使得 a + e = a 对任何 a 成立。
      - **算式例子**：在整数加法中，单位元是 0，因为对于任何整数 a，都有：
      - a + 0 = a，比如，5 + 0 = 5。
    - **逆元**：
      - 每个玩具都有一个“相反”的玩具，它们可以一起变回玩具箱的原样。
      - **例子**：一个火车和它的拆解工具，你可以把火车拆掉，重新变成零件。
      - **定义**：对于每个元素 a，存在一个逆元 -a，使得 a + (-a) = 0。
      - **算式例子**：对于整数 a = 7，它的逆元是 -7，因为：
      - 7 + (-7) = 0
  - **时钟**：时钟上的时间就是一个群。比如说，晚上 10 点再加 5 小时就是凌晨 3 点。无论你怎么加时间，结果总是回到时钟上的某个时间点。
  - **扑克牌游戏**：玩纸牌游戏的时候，不管你怎么洗牌、发牌，牌的总数还是不变的。


### 2024.08.04

- 学习主题：理解群论跟模运算的关联跟差异
- 学习内容小结：
  - 模运算属于群论的一部分
  - 离散对数问题也是基础数学知识
  - **基本概念**：

  - **乘法和对数**：在正常的算术中，如果你知道两个数相乘得到的结果，例如2的三次方等于8，那么找到 2 需要多少次乘以自己得到 8 是很容易的，这个数就是 3 。

  - **离散对数**：在一个有限的数学系统中，比如模运算系统，计算乘法的结果很简单，但反过来找出“指数”却很难。例如
  - $$ 3^x \equiv 2 \pmod{7} $$
  - 求x是困难的。这里x是离散对数。
  - 这就符合我们前面说道，制造验证很麻烦，但有了答案之后，验证却很简单的规则了
  - 群论如果要简单来理解，就是当公式，和几何，或是数的集合，形成群时，来进行这些数理的计算
  - 他的来源源自数学中许多不同领域，例如几何，代数等等，直到后面才开始逐渐汇整，形成群论


### 2024.08.05

- 学习主题：努力理解 [ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo) 的内容
- 学习内容小结：
	- 什么是交互证明？
	- 传统的证明方式可能会一次性提供证明工具，但是ZK的交互证明是透过多次的交互来完成验证
	- 过程中透过随机性来确保证明者不会预先准备答案
	- 并透过重复的过程来确保答案（这个在前面已经看过很多次）
	- 这需要反复看....我先把视频翻译给贴出来
大家好，我将为您讲授零知识证明课程的第一节课，我的讲座将是零知识交互证明的介绍。我很高兴能与Dan Bonet、Don Song、Justin Thaler和Yupeng Zeng一起授课。

我们谈论的是证明，让我们从经典证明开始。当我们想到经典证明时，会想到这些非常有声望的证明者，如高斯、欧几里得、A. MacArthur、艾伦·图灵以及我们自己的Steve Cook。我们会想到定理，比如你在几何课上可能学到的那种定理，有一堆公理，有一个你试图证明的声明或定理。你从公理中进行一系列推导，最终宣布定理被证明。它可以是素数定理、勾股定理等等。

但今天，我们将把证明视为一个交互过程，其中有一个证明者。但对我们的研究来说，更重要的是有一个验证者。所以这里明确提到的是正在阅读证明并验证其正确性的人。

我们这样思考：有一个声明，它是证明者和验证者的输入。证明者和验证者实际上都是算法。证明者发送一个字符串，我们在这张幻灯片中称之为证明。验证者阅读它。如果你想像几何证明一样，验证者就是阅读你证明的老师，并在最后接受其正确性或拒绝。接受声明被证明或没有。

事实上，在计算机科学中，我们经常谈论高效可验证的证明或NP证明。这些证明中，证明者发送给验证者的字符串是简短的。此外，验证者没有足够的时间来阅读它。他只有多项式时间。

现在，更明确地说，什么是简短？我们所说的多项式是什么意思？我们指的是，证明者发送给验证者的字符串大小是声明长度的多项式。所以我们将声明视为字符串X，二进制字符串。消息在这里是二进制字符串W。W的长度是X长度的多项式。因此，如果描述声明需要100位，W的长度应该是100的多项式。

验证者的时间也是多项式的。它可以是线性的，只是X的长度，二次的X平方的长度，甚至是X的长度到100，只要它是多项式函数。

再次，验证者是一个算法。它以X（声明）和W（证明字符串）为输入进行处理，并最终决定接受或拒绝。我们经常说接受或1。而当我们说拒绝时，它要么是0，要么是拒绝。我会交替使用这些术语。

有哪些例子？这些将是今天课程的重要例子。一个例子可能是NP证明和声明，证明者试图说服验证者某个特定的数N是两个大素数的乘积。这是一个有趣的声明，因为在验证多项式时间内，我们不知道有一个程序能够自行验证N是两个大素数的乘积。所以我们需要证明者的帮助，也许是一个全能的证明者，至少比多项式时间更强大。

在本课程的这个部分，我不会关注证明者花了多长时间来提出证明。所有的注意力将集中在一旦证明被发送，验证需要多少时间。稍后，我们将关注于可以由多项式时间证明者证明的声明，它可能知道一些额外的信息，使其能够说服验证者声明的正确性。

所以现在，让我们回到N是两个大素数的乘积。什么是证明？因为证明者的时间可能很长，我们并不关心这个。我们只关注验证需要多长时间。证明者只需将N因数分解。假设两个素数因子是P和Q，将其发送给验证者。验证者需要做什么？他需要计算P乘以Q，看是否得到N。乘法是一个简单的操作，多项式时间。并且他需要检查P和Q都是素数，这也是我们知道如何在多项式时间内完成的简单操作。如果是这样，他接受。否则，他拒绝。

所以在这次互动之后，验证者真正知道什么？他知道声明是真的。N是两个大素数的乘积。他知道一些额外的信息。他知道素数本身。这实际上比验证N是两个大素数的乘积所必需的要多。或者是吗？有没有其他方法来做到这一点？我们将在几张幻灯片中看到这一点。但让我们再看几个例子。

第二个例子。现在证明者试图说服验证者某个数Y是我们称之为模数N的二次剩余的数。因此，输入给这两个证明者和验证者的是一对Y和N。声明是Y是模数N的二次剩余。成为二次剩余是什么意思？这意味着，如果你看方程Y等于X平方mod N，它是可解的。即，存在一个X。这个X基本上介于一和N之间。此外，它与N互质。因此，N和X之间没有公共因子。这是这个方程的解。因此，存在一个X，使得Y等于X平方mod N。那什么是证明呢？

嗯，也许验证者可以自己完成。事实证明，这个问题非常困难。因此，寻找Y的模N平方根是困难的。如果这在多项式时间内很容易，验证者就不需要证明者了。它有多难？它和因数分解N一样难，这是经典计算机难题。证明者，就像我们说的，他是全能的。在这种情况下，她找到了一个X。将其发送给验证者。验证者将其平方mod N。比较以查看它是否等于Y。如果是这样，他接受。否则拒绝。

再一次，这是一个NP证明。存在一个短字符串X，当声明正确时，它将说服验证者接受。在这次互动之后，验证者相信，确实存在一个X使得Y等于X平方mod N。但他也知道X。他知道Y的平方根。

最后一个例子，然后我们开始更一般地定义这一点。这里，声明不是谈论数字，而是谈论图。实际上，如果你更仔细地观察这两个图，它们实际上是同构的。用简单的语言说，这意味着它们是相同的图，但画得稍微不同。形式上，这意味着从左侧图的顶点到右侧图的顶点有一个映射。所以如果你取这个映射，我们称之为同构，从左侧的数字1到10，到右侧的数字1到10，或者从左到右的顶点，它将是这样的，基本上，如果你用同构将左侧的一个映射到右侧的一个顶点，我们将其视为1。类似地，将左侧的2映射到右侧的2，如果左侧的1和2之间有一条边，那么在它们被映射到右侧的顶点之间也会有一条边。对于每对顶点都是如此。这意味着这两个图是同构的，并且π是一个同构。那么，描述π有多难？它在图的大小上是多项式大小吗？是的。基本上，它为每个顶点在另一个图上赋予一个名称。如果有n个顶点，它的长度就是n。验证者需要多少时间来检查它？他需要遍历左侧的每对顶点，检查它们之间是否有边，在它们被映射到右侧的地方也有边。如果它们在左侧之间没有边，在右侧之间也不应有边。

在这次互动之后，验证者将相信这两个图是同构的，如果你有一个好的同构，但他也知道一个同构。所以，所有这些例子都是NP证明的例子。当然，我们并不对某个特定的数n，或某个特定的数y，或特定的图对感兴趣。我们更普遍地对问题感兴趣，我们称之为语言。也就是说，所有的n都是两个素数的乘积。这是合数的语言。或者所有y和n对，使得y是模n的二次剩余。换句话说，我们对语言感兴趣。形式上，语言只是满足某些性质的二进制字符串x的集合。NP语言被定义为，这可以追溯到Koch和NP完全性，被定义为那些字符串集合，L，是一个NP语言。如果存在某个验证者v，其运行时间为x的长度的多项式时间，使得两个条件都成立，即完备性和可靠性。完备性成立意味着当x在语言中时，如果你谈论的是声明，或者在合数的例子中，当语言是两个素数的乘积的合数的语言，并且给出了这样一个n，那么必须有一个多项式证明或见证w，证明者可以发送给验证者，使得验证者检查x和w将接受。因此，完备性还不够。我们还需要可靠性，这就是为了确保当x不在语言中时，对于这个例子，n不是两个素数的乘积，那么不存在任何见证可以说服验证者接受。换句话说，对于证明者可能发送给验证者的所有字符串w，验证者将拒绝。

所以我们通常会谈论，完备性允许诚实的证明者说服验证者。可靠性确保无论欺骗性证明者试图做什么，他都无法说服你接受不正确的声明。但我们在本课程中要问的问题不是关于NP或NP完全性，而是我们要问的，是有没有其他方法来证明这些类型的定理？例如，证明者能否在不发送平方根的情况下，说服验证者y是模n的二次剩余？

这是在80年代初期激励Silvio Micali、Charlie Rakoff和我自己研究零知识证明的问题。这是一个大约三年的过程。答案是肯定的。即使不进入数学领域，主要思想是，证明者将说服验证者声明是真的，而不提供NP证明，在平方根的例子中，y是模n的二次剩余，而不提供平方根，而是证明，我可以证明它如果我愿意的话。所以我不会向你证明它，但我会证明我可以证明它。

以某种方式，能够证明我可以证明它将意味着在结束时，验证者将被说服，但他将不知道平方根，他将不知道n的因子，他将不知道同构。实际上，他将得到零知识证明。他将获得零知识除了声明是真的这一事实之外。当然，我们需要精确定义什么是零知识。

在我们定义之前，我想给你一个关于如何证明某事是平方根的想法，或者两个图是同构的等等，而不实际给出同构或平方根。我将从让你知道这不再是证明者发送一个字符串w给验证者开始。我们需要改变证明模型。我们需要两个新成分。一个将是互动。验证者不再只是被动地阅读证明，他将必须参与一个非平凡的互动与证明者。就像你在这张图中看到的那样，会有消息来回传递，证明者向验证者发送消息，验证者回答，来回，来回。可能是三步，可能是两步，可能是x长度的步骤，但它将是多项式数量的步骤。它将超过从证明者到验证者的单个消息。

稍后在本课程中，我们将看到有一种方法可以去除许多这种互动。仍然会在某种意义上至少有一个从证明者到验证者的消息和一些预备阶段。但现在我们有互动。互动还不够。我们还有随机性。我们指的是什么？我们指的是验证者不再只是一个评估他从证明者那里收到的东西的确定性算法。他实际上将被允许将投硬币作为一个基本操作。他对证明者的问题将取决于投掷这些硬币的结果。换句话说，他的问题有些不可预测。因为如果它们都是可预测的，证明者可以预见到并提前给他发送一个字符串w。但由于它们不可预测，证明者在发送消息后，验证者可能会根据他的投币结果提出许多不同的选择。而证明者应该能够回应所有这些选择。

验证者投掷随机性的事实是，我们也将愿意接受一个小的错误概率。这意味着什么？我们将在几分钟后详细定义这一点。非正式地，这意味着，与几何课不同，当你给老师一个证明，他们检查它，应该是100%正确的。我们将作为模型的一个正式部分，允许一个小的错误概率。但它将被量化，你将不得不能够表明你的错误小于1/，我不知道，阿伏伽德罗常数，或一个可忽略的错误。我们稍后会讨论。

目前，证明模型正在改变。它是互动的。它是概率性的，这意味着验证者可以投掷硬币。这意味着在证明者和验证者之间会出现很多可能的互动。这是可能的互动的历史。仍然是这样的。它们都得到输入，即声明。在这个问答期的结束时，验证者将接受他所做的互动历史，投掷硬币所做的互动历史，运行一个算法，决定是否接受或拒绝。

让我们看看第一个例子。第一个例子甚至不会是数学的。但它将是某种物理世界的东西。这里的声明是，这个特定的页面在我们面前有两种颜色，而不是单色。我要你记住的场景是，假设证明者可以分辨颜色，但验证者是色盲的。证明者试图说服验证者，这个特定的页面有两种颜色。他不会让他在未来看到颜色。所以在某种意义上，他所能说服他的只是这个页面有两种颜色而已。在这个意义上，它不会向他传递任何超出声明的东西。如何做到？

这是第一步。第一步是验证者使用他的硬币，掷硬币，提出以下想法。如果硬币落在正面，他就把页面翻过来。如果它落在反面，他就不改变页面。假设他掷了硬币，确实是正面，所以他翻转了页面，这样以前在顶部的紫色现在就在底部。现在他在自己家里这样做，没有向证明者展示他的硬币结果。但他所做的是将页面发送给证明者。证明者现在看着这个页面。他知道页面之前是什么样子，他现在看到页面是什么样子。因为证明者可以区分颜色，他可以判断硬币是落在正面还是反面，对吗？

这正是他所说的。他走出来，检查页面是否被翻转，然后写下新的硬币，硬币的值为正面，如果它被翻转，否则为反面，然后发送回硬币。他说，听着，我认为你投了硬币。验证者，现在的规则是，验证者，如果确实他掷的硬币等于证明者认为他掷的硬币，他说，好吧，看起来证明者可以判断页面是否被翻转。但他不能判断它是否只是单色的，所以页面上必须有两种颜色。我接受声明是真的。当然，如果发送过来的硬币与他掷的不同，他说，好吧，他甚至不能判断它是否翻转。那就肯定不是有两种颜色。我拒绝。

让我们尝试分析这一点。显然，如果有两种颜色并且证明者遵循此过程，那么验证者将始终接受，因为硬币始终等于硬币。如果只有一种颜色，证明者无法判断是否翻转。他仍然可以尝试猜测，他是一个欺骗的证明者，硬币是落在正面还是反面。他有50%的机会猜对。因此，概率是50-50。证明者发送正确硬币的概率最多是二分之一。如果验证者在这种情况下接受，则验证者错误地接受的概率，因为证明者很幸运，但页面上只有一种颜色，是二分之一。因此，如果有两种颜色，他将始终接受。如果有一种颜色，验证者接受的概率小于二分之一。这两者之间有一个差距，但你可能不喜欢这种几率。说什么？我将以一半的概率接受不正确的声明？别担心。你可以一次又一次地重复这个过程，每次验证者掷一个新硬币，决定是否翻转或不翻转，发送结果，等等。

现在，如果只有一种颜色，那么声明是不正确的，证明者能够每次向验证者提供正确硬币的概率是多少？第一次是一半。两次连续成功的概率是四分之一。三次连续成功的概率是八分之一。如果你重复k次，则是1/2的k次幂。因此，经过k次迭代后，验证者接受的概率非常非常小。

那么这里发生了什么？我能够说服一个色盲的验证者页面是否有两种颜色，以便在有两种颜色时他总是接受，而在页面上只有一种颜色时，他会以极小的概率接受这是不正确的。

让我们再看一遍这个想法，这次使用交互和随机性来在不传递显而易见的NP证明的情况下说服某人，这次是一个数学声明。因此，下一个例子是我们开始的例子，也就是输入给证明者和验证者的是一对N和Y，存在一个X使得Y等于X平方mod N。或者不是？证明者试图说服验证者，确实这对NY是这个语言的成员，QR语言，二次剩余语言。那些Y使得Y等于某个X的平方模N。你将如何在不提供平方根的情况下说服验证者这种情况？

就这样。证明者，作为第一步，选择一个介于1和N之间的随机值R。事实上，为了绝对正确，这个R应该介于R和N之间，并且与N的最大公约数为1，意味着R和N之间没有公共因子。对于那些不想深入研究的人，让我们简单地将其视为介于1和N之间的随机数。然后，他发送给验证者的是R平方。他不发送R，他发送R平方，我们称之为S，发送S。然后他对他说，听着，如果我给你S的平方根和S乘以Y的平方根，其中Y是输入。那么你会相信声明是真的，因为如果S有平方根，S乘以Y有平方根，那么Y本身也有平方根，模N。但是如果我那样做，那就像给你一个平方根的S是R，一个S乘以Y的平方根是R乘以X，那么你就知道Y的平方根了，对吗？你知道X，只需取R乘以X除以R。而这里的关键是我不想给你两个。因此我要做的是我只会给你S的平方根或S乘以Y的平方根之一。但我要说服你我可以给你两个平方根。

说服你的方法是，我告诉你，你可以选择。你可以选择得到S的平方根或S乘以Y的平方根，你的选择。我将能够回答任何一个问题，但我只回答一个。如果验证者聪明，选择要询问哪个问题的方式将是投硬币，而不是确定性地决定。因此，如果证明者在作弊，他将以50%的概率选择证明者无法解决的等式。为什么？因为如果证明者在作弊，他无法同时求解S的平方根和S乘以Y的平方根。因为在那种情况下，他没有作弊。因为他可以同时做到，意味着他没有作弊。

我将作为验证者投掷硬币选择挑战。嘿，给我S的平方根，或者嘿，给我S乘以Y的平方根。他应该这样做。因此，如果我的硬币结果是正面，即1，证明者应该返回S的平方根，即R。如果硬币是反面，他应该返回S乘以Y的平方根，即R乘以Y的平方根或R乘以X。那是Y的平方根。验证者检查他是否得到了正确的答案，所以他只在他得到的平方后，他会接受他所要求的，看看他得到了正确的答案。让我们分析这一点。再次，如果声明是正确的并且证明者按照协议行事，验证者将始终接受，因为证明者总是可以提供S的平方根和S乘以Y的平方根。再次，证明者是全能的。他知道Y的平方根。他可以，因为他是全能的。事实上，那是他唯一需要知道的。但是当声明是错误的时会发生什么？

可靠性总是较难显示的东西。如果声明是错误的，那么无论证明者做什么，他都无法求解两个等式之一。因此，我询问他解决他知道如何解决的等式的概率是多少？最多是一半。再次，也许一半对你来说不够。重复这一百次。在声明为假的情况下，验证者能够一百次如此不幸地选择证明者可以解决的等式而不是他无法解决的等式的概率将会在若干次试验中消失。尝试一次是一半，尝试两次是四分之一，尝试三次是八分之一，如果你尝试一百次，是二分之一的幂。如果你想进行k次，是二分之一的k次幂。

那么，这里发生了什么？我可以说服验证者接受声明是真的。当声明为假时，我很少有可能说服验证者接受。当你思考一下时，我从未实际传递X的平方根。因为每次我只是给他一个随机的R，它是S的平方根，或者一个随机的R乘以原始的X，或Y的平方根。随机乘以Y的平方根是随机的。当你对N进行模运算时。因此，它给出的基本上是我发送给他的随机数，即使我重复一百次，它们也是独立的。因为每次我都从验证者那里重新开始，证明者选择一个新的R。

是什么让这一点成为可能？这里有一个直觉。有很多可能的执行。因此，有很多可能的互动或证明。证明者基本上在第一步中随机选择了这些许多可能性之一。当他发送R平方时，他是在随机选择这些许多可能性之一。这些许多随机证明中的每一个都由两个部分组成。当我要求看到S的平方根时是一个部分，当我要求看到S乘以Y的平方根时是另一个部分。看到S的平方根或S乘以Y的平方根没有意义。如果验证者能同时看到这两个，那么就意味着百分之百的正确性。验证者随机选择这两个部分中的哪个是半C，哪个是C，S的平方根或S乘以Y的平方根。原则上证明者提供任何部分的能力使验证者相信证明者能够回答两者，因此正确声明是正确的。我们可以精确地定义这一点。

好的。我们有P和V，他们是某种语言或声明集的交互证明。如果验证者是多项式时间，但这次是概率多项式时间，并且存在完备性和可靠性。如果声明为真或X是语言的成员，验证者将始终接受。现在，可靠性已经被修改。如果X不是真的，声明是不正确的，或者X不是语言的成员，那么对于所有欺骗的证明者策略，无论他们多么努力，验证者都不会接受，除非是微不足道的概率，比如1/2的100次幂或1/2的k次幂，1/2的X的长度。

让我们引入一些符号。以下是一个作弊证明者。每个作弊证明者策略只会帮助证明者以微不足道的概率说服验证者。因此，一些符号。我们使用以下符号。我们谈论的是PV的概率，所以打开括号PV，关闭括号在X上接受在X等于L的情况下。完备性是概率1。在可靠性情况下，我们说对于所有作弊证明者P star，P star与V交互在输入X上的概率，它接受的概率是微不足道的。

什么是X长度的微不足道函数？这是一种增长比任何多项式慢的函数。因此，这是一个指数小的函数。因此，对于任何多项式来说，它小于1/多项式。有趣的是，如果你退后一步，想想自己，这是合理的称之为交互证明吗？我声称这最终是一个证明应该是什么。它应该说服验证者正确的定理，而不是说服他错误的定理。如果你只是在一生中成功地说服他某个错误的定理，概率如此之小，以至于在宇宙的生命中，不可能发生。这对我来说足够了。这就是证明应该是什么。它应该说服你正确的定理，而不是说服你错误的定理。在一个将花费时间在上帝的数字上的事件，一个宇宙的生命中的错误定理，基本上永远不会发生。

好的。顺便说一句，有趣的是，当你有一个练习，一个作业，并且你正在提出一个交互证明时，有时要让你拥有验证，始终接受正确的定理而不接受正确的定理几乎没有错误。你不必那么努力。你只需要证明完备性以概率C成立，而可靠性以概率S至多成立。对于C和S，它们是一个多项式分开。这将等效于实现C的概率为1，而S的概率为微不足道。这可以通过使用重复的一些标准技术来证明。因此，我们定义了什么是语言的交互证明，我们也可以谈论所有语言的类，它们都有交互证明。就像我们谈论NP是所有有NP证明的语言一样，我们将谈论IP是所有有交互证明的语言。同样，证明运行时间可能非常慢，但验证者必须是多项式时间，概率多项式时间。

好的。我们已经定义了什么是交互证明。但零知识呢？我们如何定义零知识？甚至对零知识的直觉是什么？这里是直觉。我想要一个零知识交互证明成为这样的证明，只有当声明为真时，你知道，验证者通过一个证明，交互证明通过证明者。最后，他以高概率相信声明是真的。但是除了这一点，他有一个互动历史。他有他投掷的硬币。也许在这个交互证明中你给了他很多东西，以至于现在他可以计算比以前更多的东西。例如，N，证明N是两个素数的乘积，或许在交互证明后，他可以因式分解一个数或计算一个平方根或找到一个同构。

我们将说互动是零知识的。如果验证者在互动后可以计算的东西本质上与他之前可以计算的东西相同。换句话说，互动没有增加计算能力或允许验证者计算比他以前可以计算的更多。此外，我们希望这不仅对遵循协议的诚实验证者成立，还对任何验证者，甚至是恶意的对手验证者都成立。这是一个直觉幻灯片。我们如何数学地捕捉这一点？让我们尝试。我们将慢慢来。

首先，我想说这个验证者有某种视图。我想，你知道，所以他在互动后了解到定理以高概率为真，但他也获得了一个视图。那就是成绩单，你知道，答案和问题加上他投掷的硬币。我们将定义这个正式变量。这是视图子V的PV在X上的视图。那是一个随机变量。我指的是有很多可能的值这个变量可以获得。这是一个关于V和P都投掷的硬币的概率分布。记住，让我们说在展示Y是一个二次剩余的例子中，证明者投掷硬币选择R。验证者投掷硬币选择他是否想看到R平方的平方根，或者R平方乘以Y的平方根。因此，这些都是可能的执行。这些都是这个变量可以获得的可能分配。好的，所以这是验证者的视图。

我会说如果验证者可以自己模拟这个视图，而不与证明者交互，这个视图就不会给验证者任何新东西。所以这就是模拟范式。这个模拟范式开始于零知识的概念。它在今天的加密学中被广泛使用。模拟范式的想法是什么？我们说真实视图，所以如果我们看这个大块，这个伟大的大块，我称之为真实视图，这基本上是一个概率分布。这个空间中的点是证明者和验证者之间所有可能的交互历史加上验证者的硬币。我说如果验证者能在家里自己模拟这个视图，那么这个视图就没有给他带来任何新东西。他可以基本上自己采样模拟视图。而模拟视图与真实视图的关系必须是，如果有其他人，比如我们称之为多项式时间的区分者，他正在按按钮。按下按钮表示，给我一个你有的分布中的样本。我试图确定我是在与真实视图交互，还是在与模拟视图交互。我只是不断按按钮，得到视图。在最后，我应该告诉我得到的所有视图是来自真实视图还是来自模拟视图。如果一个区分者不能分辨这一点，不能比50-50更好地分辨这一点，我说这两个视图是计算上的。他们是计算上无法区分的。他只是，一个多项式时间区分者无法分辨他们。

让我们进一步深入研究这一点。两种分布，两种概率分布在计算上无法区分意味着什么？在我们的情况下，这两种分布是真实视图和模拟视图。但这不一定适用于这个特定的设置。我们可以更广泛地谈论计算上无法区分的概念，在哪里，再次，有两个分布。在我们的情况下，有视图，但可以只是两个K位字符串。游戏是，如果墙的另一边有一个区分者，他可以按下按钮并得到样本，始终来自分布D1的所有样本，或来自分布D2的所有样本，他的愿望是区分哪个是情况。我们说这两个分布，在多项式时间内是无法区分的，如果对于任何策略这个多项式时间区分者采用的所有区分者算法。即使在接收到来自分布D的多项式数量的样本后，分布1或2，他可以猜测这是否是分布1或分布2的概率小于1/2减去微不足道的概率。

关于什么？这里我称为K的某种安全参数，它可能是样本字符串的大小，样本字符串的大小。因此，回到零知识，以下是定义。一个交互协议P和V是语言L的零知识，如果存在一个模拟器，一个算法，SIM，使得对于L中的每个X，我只在定理正确时才要求它，只在X在L中时才要求它。为什么？因为你确实得到了一些东西，你得到的是X在L中，但这是一个细节。我要求这两个概率分布在多项式时间内是无法区分的。第一个是验证者在交互中获得的真实视图。第二个是模拟器的输出。模拟器在这里以X为输入，只有X。他没有Y的平方根或任何秘密，只有输入，即P和V都看到的输入。你会注意到这里有另一个输入给模拟器，这是这个1的幂次方。这基本上是一个技术性问题，因为我们希望确保我们允许模拟器运行足够长的时间，通常当X非常小时，这并不能给他足够的时间。但实际上，对于所有实际目的，如果我们考虑大X，忘记这个1。因此，它们都是多项式时间运行的。要成为零知识意味着这两个分布在计算上是无法区分的，这将使协议PV成为一个零知识交互证明，如果它是完整的。如果不是，它是一个零知识交互证明。声音满足完备性和可靠性，并根据这个定义是零知识。

几乎。两个注意事项。我们将让这个模拟器，这个概率多项式时间，在预期多项式时间内运行。那意味着什么？我们在这里所说的预期多项式时间本质上意味着，如果你取模拟器在所有可能的模拟器随机性上的期望，它将是一个多项式时间。一个注意事项。实际上这意味着可能会有一些非常不幸的硬币给模拟器，这将使他花费很长时间来运行。但通常情况下，他将在多项式时间内运行。这是你们应该知道的。那是预期多项式时间的定义。还有一个注意事项，在这个定义中，我从未提到验证者。我只是说一个特定的P和V对是零知识，如果可以确定以下条件成立。这实际上是情况。

条件成立。但我们希望这对每个验证者都成立，即使是一个撒谎的验证者。因此最终定义必须考虑验证者可能是一个骗子并试图获得他不应该的知识，所以他不诚实。

所以我们最终得到一个协议是语言L的零知识的定义，如果对于每一个V星，和P一起工作，存在一个多项式时间模拟器，使得视图和模拟是计算上无法区分的。我用这个波浪线等于表示计算上无法区分的。因此，这些可能是不同的概率分布，但区分者不能分辨它们。

好了，让我们休息一下。所以P，V是零知识，如果对于每个V星，无论V星做什么，我们实际上可以在我们自己中模拟这个。这捕捉到了验证者在交互中可以学习到的直觉，并没有增加任何计算能力。记住我们最初的直觉是你在交互前后可以计算的东西是一样的。原因是因为我们说以下，也许有一个V星，一个真正狡猾的，可以从证明者那里得到一些东西。零知识说没有。如果这样的V星存在，那么我们可以在之前计算，因为一个模拟器可以使用那个V星来产生一个模拟分布，它比视图更多。但零知识要求说那是不可能的。对于每个V星，将会有一个模拟器，可以实现与现实视图基本上等价的分布。因此，现实视图没有增加任何计算能力。

好的。顺便说一下，这就是所谓的计算无法区分的零知识。有时人们使用符号C，ZK，C表示计算。但还有其他类型的零知识。您还可以要求完美零知识定义。当真实分布和模拟分布是相同的或可能是统计接近的。所以完美零知识是一个特殊情况，当你看到验证者的视图时，我们实际上可以完美地模拟它。所以模拟视图和真实视图是相同的，这意味着它们对于任何算法都是无法区分的。因此，这意味着当您可以证明完美零知识时，它是一个无条件的结果。因为通常当我们只证明计算上零知识时，我们做出了一些假设，即有些计算是困难的。而在完美的情况下，它只是完美的零知识。在现实交互中可以学习到的东西和我们可以从模拟中学到的东西之间没有区别。

让我们通过一个模拟，现在我们有一个定义。回忆二次剩余的协议。因此证明者发送R平方，他要求要么看到R，要么看到R乘以Y的平方根，他得到了答案。他检查它。因此这里的视图是什么？视图是S，这是第一个消息，B，第二个消息和Z，第三个消息。这些硬币投掷是B，所以它无论如何都包括在内。是S，B，Z。我们如何模拟呢？好吧，我们将在不同的顺序中模拟这一点。毕竟，模拟器不能只是选择一个R并自己发送一个消息。我是说，他可以，但如果你投掷硬币，你只知道如何返回R。您不知道如何返回R乘以Y的平方根。

那么我们将如何获得一个模拟呢？这个想法是这样的。我们将只为一个诚实的验证者展示一个模拟。事实上，模拟将是一个完美的零知识模拟。模拟器要做的是，不是真正按照真实交互的顺序，而是他首先选择验证者的问题。他将这样做，就像一个诚实的验证者那样，选择一个随机位B。然后他将实际上选择第三个答案，即他将选择一个随机的Z。注意Z实际上只是一个随机数，除了在这种情况下是R，在这种情况下是R乘以X。因此剩下的唯一事情是确保我可以计算出哪个S将是正确答案。

注意这个方程S等于Z平方除以Y的B次幂模N，正好满足S应该是什么。为什么？让我们看看这个。让我们代入B等于零，在这种情况下，S等于Z平方。这正是它应该的情况。在B等于零的情况下，Z是S的平方根。在B等于一的情况下，我让S等于Z平方除以Y。那是正确的吗？让我们想想这个。如果B等于一，Z是Z乘以X。所以我将得到X平方，这将是Y。我将得到Z平方除以Y，YZ是S。

好的。注意到现在，由于他是一个模拟器，所有三个值都是由模拟器选择的。S，B，Z。所以这完全在他身上。并且注意到这就是模拟和真实执行的区别。首先，问题是由真实交互中V的投币来决定的。在这里，由模拟器自己来选择。第二，Z是由在真实交互中正确响应来决定的。在这里，它是由模拟器自己选择的。因此这是对诚实验证者的完美模拟。

所以我给你们留个问题。将模拟器与诚实验证者一起工作修改为适用于任何V星。考虑一个V星可能在他提问之前并非诚实的情况。什么是现实世界中的零知识证明协议？现在，为什么我们对这个东西感兴趣呢？你知道，如果你回到1980年代，当我们做这些研究时，问题是，好的，许多理论学者对此感到兴奋，但这将如何影响现实世界呢？那么问题是它们实际上对现实世界有用吗？

答案是，这实际上非常有用。它们在许多实际系统中都有应用，特别是在身份验证方案中。因为许多协议的核心是相同的。Alice想说服Bob，她知道某件事。或者她拥有某件事，但她不想给他任何关于它的线索。例如，她想说服Bob，她知道一个密码，但不想给他它的线索。她知道她的私钥。Bob知道她的公钥。她不想给Bob关于她的私钥的线索。她知道一个证明，或任何关于她的身份的内容。基本上，任何关于她想要得到的她的身份的东西，应该保持私密。

因此，这里有两个例子，但有许多例子。Alice可以证明她知道一个二次剩余的平方根，证明她知道一个大数的因子。如果这是多方协议中的签名协议，Alice和Bob必须验证，任何人都可以验证。Alice在签署协议时想要保持自己的信息私人，并且有很多这样的例子。她想证明她知道一个秘密，但不想让Bob知道她知道的更多。

第二个例子是证明协议的正确性。这是我们与随机证明交互证明等证明协议一起得到的，这些协议在这里并没有真正涵盖太多。但它们在我们谈论的ZKSNARK和ZKSTARK以及接下来的几节课中更为相关。在许多协议中，有许多地方你只想证明某件事是正确的，而不泄露任何关于它的内容。你只想说服他们，它发生了，而不泄露有关它的内容。

所以这种情况下是什么？例如，你对云中的数据进行了加密。你想证明你的加密和解密是正确的，但你不想告诉人们你的加密是什么，你的解密是什么。因此，数据加密在云中。你想证明数据确实被加密，但你不想告诉他们你的数据是什么。你不想告诉他们你的加密密钥是什么。这实际上是零知识证明的两个例子。这两个例子也是许多其他例子的代表。

我们最后看看一些应用程序。零知识证明非常有用。这里有一些例子。你可以在核裁军中使用它们，证明一个核弹头已经被核拆除，而不泄露有关弹头的秘密。你可以用它们来检查一个程序是否正确，而不泄露任何关于程序的内容。这在许多法律协议中也很有用。在许多法律协议中，你想证明协议符合某种法律法规，而不泄露协议的具体细节。你可以用它们来进行隐私和身份验证。

这是它们的几个例子。所以在今天的课程中，我们定义了什么是交互证明，我们谈到了交互和随机性，我们定义了零知识。我们讨论了为什么它们在现实世界中有用，并展示了一些例子。

我们没有证明的是，所有NP语言都有零知识证明。这将是课程的最后一个讲座，也是最困难的一个。

### 2024.08.06

- 学习主题：
- 学习内容小结：

### 2024.08.07

- 学习主题：
- 学习内容小结：

### 2024.08.08

- 学习主题：
- 学习内容小结：

### 2024.08.09

- 学习主题：
- 学习内容小结：

### 2024.08.10

- 学习主题：
- 学习内容小结：

### 2024.08.11

- 学习主题：
- 学习内容小结：

### 2024.08.12

- 学习主题：
- 学习内容小结：

<!-- Content_END -->

