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

1.自我介绍 BUPT大四学生，ZK小白。
2.你认为你会完成本次残酷学习吗？ 会
3.目前阶段对于 ZK 的了解？ 还没入门，期望可以取得进步。

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：了解zk的历史、定义、特点。
- 学习内容小结：零知识证明是一种密码学方法，使得证明者能够向验证者证明某一声明的真实性，而无需透露任何关于声明的其他信息。具有完备性、可靠性、零知识的特点。
完备性（Completeness）：如果声明为真，诚实的证明者可以成功说服诚实的验证者。
可靠性（Soundness）：如果声明为假，欺诈性的证明者无法成功说服诚实的验证者，除了极小的概率。
零知识（Zero-Knowledge）：验证者不会获得除声明真实性之外的任何额外信息。

### 2024.07.30

- 学习主题：了解模拟器，理想世界，显示世界的概念。
- 学习内容小结：模拟器是一个算法，用来在理想世界中模拟与验证者的对话，而不使用实际的秘密信息。通过构造模拟器，可以证明在现实世界中，验证者无法从交互中获得除陈述真实性以外的其他信息。

### 2024.07.31

- 学习主题：学习"知识"的概念。
- 学习内容小结：零知识证明具有完备性、可靠性、零知识的特点。而只有「知识」在存在的前提下，保证「零知识」才有意义。

### 2024.08.01

- 学习主题：学习“挑战”
- 学习内容小结：非交互式零知识证明（NIZK）中模拟器无法使用“时间倒流”的超能力来模拟理想世界，从而理论上会导致系统不可靠。可以通过引入随机预言机来弥补挑战的缺失。随机预言机是一个假设存在的虚拟机制，可以通过哈希函数来模拟。

### 2024.08.02

- 学习主题：隐藏“秘密”
- 学习内容小结：隐藏的秘密通常指的是某些隐藏在公共参考字符串（CRS）中的信息，用来让模拟器（Simulators）具备某种特殊的能力，从而在非交互式零知识证明（NIZK）中达到与交互式零知识证明相同的效果。

### 2024.08.03

- 学习主题：回顾
- 学习内容小结：回顾了一下前几章的知识，着重关注了一下Zlice如何欺骗Bob。在SHVZK中，Zlice需要具有读取Bob预选随机数的“超能力”，将Bob最后验证所需的随机数改为R'=z*G-c*PK.
而在NIZK中，则是通过绑架负责预言的“精灵”，将c 与 (m, R')写入表格，R'=z*G-c*PK.

### 2024.08.05

- 学习主题：进入zk-SNARK的学习
- 学习内容小结：通过视频了解zk-SNARK。

- ### 2024.08.06

- 学习主题：学习Polynomial Interaction and Proof
- 学习内容小结：问题：prover 想要证明他知道一些多项式p(x)，verifier进行验证
  协议一：
  verifier构造t(x),t(x)的根是p(x)的根;并计算t(s)，并将s发送给prover
  prover 用h(x)=p(x)/t(x)计算出h(s)和p(s)发送给verifier进行验证
  verifier 验证 h(s)*t(s)?=p(s)
  存在的问题：协议对多项式阶数并没有明确的要求， prover 完全可以拿一个满足因式校验的超级高阶数的多项式来欺骗 verifier
  改进：采用同态和模运算。
  同态加密的核心：允许在加密状态下进行加法和乘法操作

<!-- Content_END -->
