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

<!-- Content_END -->
