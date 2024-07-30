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

# Derick
1. 自我介绍
2. 你认为你会完成本次残酷学习吗？
3. 目前阶段对于 ZK 的了解？

## Notes

<!-- Content_START -->

### 2024.07.29
学习第一节课视频
计算机科学家Amit Sahai解释零知识证明(Zero-Knowledge Proofs)这一概念。视频分为5个不同难度级别的解释,从儿童到专家,Amit Sahai逐步深入地讲解了这一复杂概念。:
1. 零知识证明的基本概念
零知识证明是一种方法,允许证明者(prover)向验证者(verifier)证明某个陈述是真实的,而无需透露除了该陈述真实性之外的任何额外信息。

2. 对儿童的解释
Amit使用了一个藏在企鹅群中的海雀图片来解释这个概念。他通过在一块板子上开一个小孔,让孩子看到海雀而不知道它在图片中的具体位置,从而证明他知道海雀的位置,但不透露具体信息。

3. 对青少年的解释
Amit使用了一个带密码锁的盒子来演示。他能打开盒子并读出里面的内容,证明他知道密码,但并未透露密码是什么。

4. 对大学生的解释
Amit介绍了NP完全问题和地图三着色问题。他使用封闭的信封来表示地图上的颜色,通过多次随机验证来证明他有正确的着色方案,而不需要显示整个地图的着色。

5. 对研究生的解释
讨论了零知识证明在区块链和多方计算中的应用。强调了零知识证明不仅是为了提高效率,更是为了实现以前无法实现的功能,如在不透露个人投票信息的情况下证明选举的正确性。

6. 与专家的讨论
深入探讨了零知识证明的数学基础、随机性的作用、以及与量子计算的关系。讨论了未来研究方向,包括寻找量子抗性的困难问题,以及如何利用零知识证明来解决社会信任问题。

### 2024.07.30
- 学习第一篇 [零知识与证明](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
- 零知识证明的定义
- 零知识证明是一种密码学技术，允许一方（证明者）向另一方（验证者）证明某个陈述是真实的，而无需透露除了该陈述真实性之外的任何额外信息。
- 零知识证明的三个特性
- 完备性：如果陈述为真，诚实的证明者可以说服诚实的验证者。
- 可靠性：如果陈述为假，任何不诚实的证明者都无法说服诚实的验证者。
- 零知识性：如果陈述为真，验证者除了知道该陈述为真之外，不会获得任何额外信息。

<!-- Content_END -->
