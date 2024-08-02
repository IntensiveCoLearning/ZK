---
timezone: Asia/Shanghai
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

# {你的名字}
1. 自我介绍
2. 你认为你会完成本次残酷学习吗？
3. 目前阶段对于 ZK 的了解？

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：零知识证明
- 学习内容小结：零知识证明（ZK，Zero Knowledge）通俗的理解就是告诉你一个结果或者一个结论，但是并不会告诉你理由或者证明过程，即保证了在交易结果成立时保留了私密性。我学网安的，这个在密码学里面大概学过,还在听博客ing。（鼓励用自己的语言描述学到的知识）

### 2024.07.30

- 学习主题：zk的介绍与历史
- 学习内容小结：计算机科学中有两个方法论至关重要，第一个是「抽象」，第二个是「模拟」，而zk的实现就离不开模拟，任何一个零知识的协议，都可以通过构造一个「理想世界」来理解。
- 同时zk的博客也介绍了zk是什么以及如何实现的，并介绍了zk协议所包含的三个性质：完整性（A成立，B成立），可靠性（A不成立，B不成立），零知识性
- 然后介绍了零知识证明在区块链上的两种实现方式:zk-SNARKs和zk-STARKS，以及他们的区别和优缺点
- 介绍零知识证明的三种主要数据储存形式:Rollups、Validium和Volition
- 以及对两种方式的案例分析

### 2024.07.31

- 学习主题：zk-SNARK协议的实现
- 学习内容小结：1.第一节讲了如何构造和验证多项式以证明某个陈述的正确性，而不暴露具体的数据。构造过程中使用了同态加密和多项式承诺的技术，通过多项式的评估和验证来确保数据的完整性和隐私。证明者和验证者之间的交互通过随机选择的点来进行，从而在确保安全性的同时减少计算复杂度。

### 2024.08.01

- 学习主题：zk-SNARKs的非交互性和分布式设置
- 学习内容小结：2.第二节讲了zk-SNARKs的非交互性通过使用公共参考字符串（CRS）实现，这个字符串由一个可信的第三方生成并且在整个协议中保持不变。这样，证明者和验证者之间无需直接通信即可验证证明。分布式设置则通过多方计算（MPC）生成CRS，这种方法可以分散信任，不依赖于单一实体，从而增强安全性。这些机制确保了系统的安全性和隐私性，使得证明过程更加可靠和不可篡改。

### 2024.08.02

- 学习主题：zk-SNARKs的通用计算方法
- 学习内容小结：3.第三节讲了zk-SNARKs如何将通用计算转换为多项式形式，以验证计算的正确性。它介绍了如何用多项式表示简单程序、单个运算、多操作数多项式，以及如何通过证明这些多项式的正确性来验证计算的准确性。文章还探讨了确保变量在所有运算中只有一个取值的机制，并详细说明了多项式插值和验证方法。整个过程旨在确保在零知识证明中，计算过程和结果都是正确和可信的。
<!-- Content_END -->
