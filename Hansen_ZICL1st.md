---
timezone: Asia/Shanghai
---


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

# Hansen
1. 自我介绍
   
   学的东西比较杂，以 后端为主，对Web3有一定理解，看好web3。
2. 你认为你会完成本次残酷学习吗？
   
   精力不是很多，但应该会，
3. 目前阶段对于 ZK 的了解？

   了解一些基本的概念

## Notes

<!-- Content_START -->

### 2024.08.02

- 学习主题：寻找「知识」

### 2024.08.01

- 学习主题：随机「挑战」
- 学习内容小结：
	- 有点难 ，看的似懂非懂
 	- 随机预言机： Random Oracle ，像一个黑箱，对任何输入都返回一个真正均匀随机的输出，相同的输入返回相同的输出， 有点像 Hash 函数。 

### 2024.07.30

- 学习主题：理解「模拟」
- 学习内容小结：
	- 任何一个零知识的协议，都可以通过构造一个「理想世界」来理解
	- 「模拟器」这时候登场了，它能模拟出一个和现实世界外表一模一样的「理想世界」，然后「模拟器」在这个世界中可以轻松地骗过任何一个对手，让对方无法分辨自己是在现实世界中，还是理想世界中。因为「模拟器」手里没有那个秘密 w，「理想世界」是零知识的。又因为两个世界的不可区分性，所以我们可以得出结论：Alice 的交互协议是「零知识」的。

	- 我的理解：我们要做个模拟器，来模拟 这个世界，从而证明我对这个世界的理解， 但关键是这个模拟的世界，不是真正的世界，  真正的世界才是那个 知识 W

	- 椭圆曲线： y2 =x3+ ax +b  ，  应该叫奶头曲线  哈 ，关于x轴对称的

### 2024.07.29

- 学习主题：初识「零知识」与「证明」
- 学习内容小结：
	- 零知识证明：Zero-Knowledge Proof 
		- 不泄露重要信息，而证明结果 
	- 对证明的理解： 「编写程序」和「编写证明」实际在概念上是完全统一的，
		- 循环对应于归纳 
		- 码农实际不是在写代码， 是在做数学证明。 
		
	- 零知识证明的用处： 解决数据、计算的信任问题。
		- 零知识证明技术可以「模拟」出一个第三方，来保证某一个论断是可信的
		1. 数据的隐私保护
		2. 计算压缩与区块链扩容
		3. 端到端的通讯加密
		4. 身份认证
		5. 去中心化存储
		6. 公平的数字化商品交易
		7. 信用记录
		
	- 信息与知识
		- 「知识」是与「计算难度」相关，而「信息」则不是
		- 「知识」是与公共所知的东西有关，而「信息」主要与部分公开的东西有关
		
	- 我们平时跑的（没有死循环）代码，都可以用算术电路来表示。
		

### 2024.07.30

<!-- Content_END -->
