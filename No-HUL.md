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

# {超自然}
1. 自我介绍
* 本科在读，对ZK有兴趣
2. 你认为你会完成本次残酷学习吗？
* 会
3. 目前阶段对于 ZK 的了解？
* 看了WTF-zk的前几章，但没有坚持下去，还看了几篇科普软文..

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：初识「零知识」与「证明」
  
- 学习内容小结：
  * 二十世纪初人们着手探索将“证明”的过程拆解为形式化的符号推理，试图将任何假设的“证明过程”抽象成有限个公理和有限个运算法则的演算。
  * 1960s，科学家发现「编写程序」和「编写证明」实际在概念上是完全统一的，不久后出现了用程序来辅助证明的案例。
    
      > 「寻找证明」仍然是最有挑战性的工作。「验证证明」，则必须是一个简单、机械、并且有限的工作。这是种天然的「不对称性」。
  
  * 『交互式证明系统中的知识复杂性』这篇论文中，提出了交互式证明系统的概念：通过构造两个图灵机进行「交互」而不是「推理」，来证明一个命题在概率上是否成立。
  * 信息≠知识，零知识证明不是零信息证明
    * 如果 Bob 在交互过程中获得的「信息」，可以帮助提升 Bob 直接破解 Alice 秘密的能力，那么我们说 Bob 「获得了知识」。
    * 「知识」是与「计算难度」相关，而「信息」则不是
    * 「知识」是与公共所知的东西有关，而「信息」主要与部分公开的东西有关
   
  > NP-Complete 是一类问题，他的求解过程是多项式时间内难以完成的，即「求解困难」，但是验证解的过程是多项式时间可以完成的，即「验证简单」。
  
  * 最新的零知识证明技术，有的技术可以让 Bob 高速验证证明（在移动设备上几毫秒验证完成）；有的技术可以让所有吃瓜群众帮忙验证（非交互式零知识证明）；有的技术支持非常小的证明大小（小到几十个字节）。

### 2024.07.30

* 学习主题：安全 & 模拟

* 学习内容小结：
  * 一切安全都有前提的。只有经过数学证明之后，大家才能够确信这个 算法/方案 的安全性基于一些非常明确的「安全假设」。

 > 完美安全：假设你是一个攻击者，你通过密文获取不到任何有价值的信息，破解的唯一手段就是靠瞎蒙。
 > 语义安全：假设你是一个攻击者，你通过密文在多项式时间内计算不出来任何有价值的信息。

1. 证明的零知识过程，等价于构造（寻找）一个「模拟」算法，这个算法能够让模拟器来模拟出一个「没有知识」的理想世界。如果这个算法存在，而且两个世界不可区分，那么就证明完毕。
2. 证明零知识的过程，就是要寻找一个算法，或者更通俗点说，写出一段代码，它运行在外部计算机系统中，但是实现了虚拟机的功能。而且在虚拟机中，需要有一个不带有「知识」作为输入的 Zlice，可以骗过放入虚拟机运行的 Bob。
 
<!-- Content_END -->