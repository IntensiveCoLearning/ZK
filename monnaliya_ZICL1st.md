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

# {你的名字}
1. 自我介绍 I'm a frontend developer, I want learn web3 technology
2. 你认为你会完成本次残酷学习吗？yes, I will
3. 目前阶段对于 ZK 的了解？not know too much

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：零知识证明
- 学习内容小结：密码学的一种方法，即不泄露所拥有的信息，又能向其他人证明确实拥有这个信息。有三个特征：
  - 完整性：如果声明是真的，那么诚实的证明者可以说服验证的人
  - 可靠性：如果声明是假的，那么欺骗性的证明者没有办法说服验证的人
  - 零知识性：验证的人在验证的过程中，不会获得除声明的这个事实以外的其他信息。


### 2024.07.30

- 学习主题： [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
- 学习总结：学习了零知识证明的概念（一方面另一方证明某个声明是真的，又不泄露除声明真实性之外的其他信息），关键属性：完备性，可靠性，零知识。它的应用：隐私保护交易，身份验证，安全投票系统。两种类型：交互式零知识证明，非交互式零知识证明。所用到的密码学原语：承诺方案，同态加密，默克尔树。它在金融，身份验证和安全通信等各领域中很有应用价值。

### 2024.07.31
- 学习主题： [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
- 学习总结：
  - 介绍了零知识证明中的“模拟”概念。模拟是理解零知识的关键，通过构建“理想世界”和“现实世界”来展示如何验证一个系统的零知识特性。零知识证明是一种方法，可以让你在不泄露任何秘密的情况下，证明你知道一个秘密。举个例子，假设你有一个神奇的洞穴，有两个入口，只有你知道如何穿过洞穴。你可以通过让别人站在洞穴外看你从一个入口进去，然后从另一个入口出来，来证明你知道这个秘密路线，而不需要告诉他们具体的路线。用洞穴的故事说明了模拟器的作用，模拟器就像是有“时间倒流”能力的人，能让你相信他知道一个秘密而不需要告诉你具体是什么。这就是零知识证明的基本原理。这样的方法在保护隐私和安全方面有很多应用，比如密码和身份验证。

### 2024.08.01
- 学习主题：[（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
- 学习总结：
  - 介绍了零知识证明，在在不泄露秘密的情况下，证明某人知道某个秘密。它使用了Schnorr协议的例子来解释这一点。首先，零知识证明的基本思想是让一个人（叫做证明者）向另一个人（叫做验证者）证明他们知道某个信息，但不透露具体信息。它是通过数学方法实现的。
  - 介绍了Schnorr协议的工作原理。通过下面这些步骤，验证者可以确认证明者知道秘密信息，但不会知道具体的秘密是什么。进一步解释了零知识证明的可靠性和安全性，以及这些方法在实际应用中的重要性。
    1.	生成随机数：证明者选择一个随机数，并根据这个随机数生成一个临时的计算结果。
    2.	提交计算结果：证明者将这个计算结果提交给验证者。
    3.	验证者发出挑战：验证者随机选择一个挑战数，并把这个挑战数发给证明者。
    4.	证明者回应挑战：证明者根据挑战数和之前选择的随机数，计算出一个新的结果，并把这个结果发送给验证者。
    5.	验证结果：验证者根据证明者的回应，检查计算结果是否正确，以验证证明者确实知道秘密信息。
  - 讨论了模拟器的角色。模拟器是一个假想的工具，用来证明在零知识证明中，验证者无法区分真实的证明过程和模拟的过程。换句话说，验证者无法通过观察证明过程来获取任何额外的信息。
  - 引用了一些著名的零知识证明应用场景，如密码学中的身份验证、隐私保护的数字货币交易等。这些应用展示了零知识证明在现代信息安全中的重要作用。


### 2024.08.02
- 学习主题：100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 学习总结：视频中的计算机科学家Amit Sahai解释了“零知识证明”这一概念，从简单到复杂分为五个难度级别。视频通过不同难度层次的解释，从基础到深入地理解零知识证明的概念。
  1. 初学者级别：零知识证明是一种在不透露任何额外信息的情况下，证明某个陈述是真实的方法。这个概念类似于在不透露具体位置的情况下证明一张照片中的隐形小精灵的存在。
  2. 中级：零知识证明用于在不透露秘密信息的情况下，证明某事是真实的。它可以用来在没有透露任何信息的情况下，建立双方之间的信任。这个方法在计算机技术和面对面的互动中都有应用。
  3. 高级：零知识证明是一种互动，通过这种互动，两个人中的一人可以在不透露原因的情况下，证明某个陈述是真实的。尽管这些证明可能看起来令人费解，但它们可以用来证明各种陈述的真实性。例如，图三着色问题是使用零知识证明解决的一个NP完全问题的例子。
  4. 专家级：这一部分使用颜色和信封解释了零知识证明的概念。通过使用颜色组合来证明某事，而不透露颜色的原始组合。这种证明是基于概率的零知识证明，类似于加密技术。
  5. 大师级：零知识证明使用随机性来在不透露秘密的情况下证明诚实。这种方法广泛用于多方计算中，以完成复杂的任务。随机性在经典证明中可能看起来不直观，但在零知识证明中非常有用。

<!-- Content_END -->
