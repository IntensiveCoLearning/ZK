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

{Rayer}
自我介绍: 区块链从业者
你认为你会完成本次残酷学习吗？ 会的
目前阶段对于 ZK 的了解？ 只有概念性的了解，没有数学和算法层面的了解
Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：介绍zk
- 学习内容小结
**零知识证明的基本概念**
  完整性：如果声明是真实的，诚实的证明者可以说服验证者。

  可靠性：如果声明是假的，没有办法伪造证明以说服诚实的验证者。

  零知识：除了声明的真实性之外，验证者不会获得任何额外的信息。

  Blum、Feldman和Micali在1988年提出了非交互式零知识证明（NIZK），这种证明系统不需要证明者和验证者之间的多轮交互。这一发展使得零知识证明在实际应用中更为实用。零知识简洁非交互知识论证（zk-SNARKs）。zk-SNARKs显著地减少了零知识证明的计算复杂性和证明大小，使其更适合在区块链和加密货币中应用。   


### 2024.07.30
- 学习主题：
（一）初识「零知识」与「证明」
（二）理解「模拟」
- 学习内容小结:
  对模拟有了初步认知，应该说，如果任何一个没有知识的人都能通过一个方法来伪造、模拟自己有这个知识，那么想要获取这个知识的人的利益就会受害。下一章节说是再讲如何保护求知者的利益。
### 2024.07.31
- 学习主题：
（三）寻找「知识」
- 学习内容小结:

Schnorr 协议，这是一个简洁而强大的零知识证明协议。Alice（证明者）通过一系列数学运算，向 Bob（验证者）证明她拥有某个秘密（私钥），同时保证 Bob 无法获取这个秘密。

协议步骤：

Alice 生成一个随机数 r，并计算出 rG。

Bob 提供一个挑战数 c。

Alice 计算 z = r + ac，并将 z 发送给 Bob。Bob 通过 zG 是否等于 rG + c(aG) 来验证。

可靠性证明：

通过引入“抽取器”（Extractor），展示了如何在理想世界中通过时间倒流等超能力，证明 Alice 具有知识，从而保证了协议的可靠性。
ECDSA 签名攻击：

解释了 ECDSA 签名方案中的一个安全隐患，即如果在两次签名中使用相同的随机数，签名者的私钥将会暴露。通过对比，指出这个问题与 Schnorr 协议中的可靠性证明过程类似。

### 2024.08.01
请假一天    
<!-- Content_END -->
