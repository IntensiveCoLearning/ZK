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

# Alex
1. 自我介绍: 学生开发者，后端+合约
2. 你认为你会完成本次残酷学习吗？ 会
3. 目前阶段对于 ZK 的了解？ 零基础

## Notes

<!-- Content_START -->

### 2024.07.29
- 学习主题：20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
- 学习内容小结：
1. zkp定义：交互式系统，涉及证明者和验证者，证明者能够不暴露自身知识即可向验证者证明知识存在
2. zkp为什么有价值：人们本质上是不信任他人的，所以相比将秘密共享，zkp这种不暴露秘密即可达到证明某件事情成立的技术更令人激动 
3. np问题与zkp：np问题是在多项式时间内难以解决的一类问题，但若是解决了其中一个，即可解决所有；zkp可以利用np的这种特性，只要其可以解决a问题（与秘密无直接关系），那就一定能解决b问题（与秘密有直接关系） 
4. zkp应用场景：目前最广泛的使用场景是区块链 
5. 注意区分information和knowledge： 后者是需要保护的 
6. 视频对zkp未来预测：寻找harder problems

### 2024.07.30
- 学习主题： [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
- 学习总结：zkp需要通过模拟第三方来达到证明的目的；文章还讲了地图三染色这种交互式的zkp，并以此引出信息和知识的区别；此外就是电路可满足问题，同样也是np问题，将程序转换为算术电路去验证，而像zksnark这样的零知识电路可满足性协议，则可以不暴露细节即可证明电路运算通过。

### 2024.07.31
- 学习主题： [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
- 学习总结：
  对安全有了一个新认识：在多项式时间内无法求解；
  本文重点是介绍了模拟器的概念和作用；模拟器本质就是为了产生零知识过程，它可以通过一些root权限，比如“时光倒流”来达到效果；一个有知识的现实世界和一个模拟出来的没有知识的理想世界，以此达到零知识；
  后面的地图三染色和阿里巴巴都是应用了模拟器的例子；
  看完本文对于zkp有了更深的理解：zkp首先需要寻找一个算法去达成零知识的环境，随后若是验证全部能够通过，那么零知识证明成功，否则失败

### 2024.08.01
- 学习主题：  [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
- 学习总结:  开头讲解了一番可靠性的定义：用于保证若是验证通过则知识一定存在；介绍了schnorr这一零知识证明协议，利用了交互性+同态加密（有限域到循环群）+随机数；后面又简单介绍了ecdsa，其中强调了随机数必须随机，不然知识是可以被推出来的；关于最后的脑洞，我认为是的，所谓科学是一种更抽象的程序，所谓幻象往往就是bug

### 2024.08.02
- 学习主题：[1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)部分内容
- 学习总结：
1. 多项式是zksnark的核心，本质是因为当阶数较多时，多项式在任意点的计算结果一致的可能性几乎为0；
2. 多项式中的知识指的是item的系数
3. 基本的利用多项式的因式分解来构造的证明系统有一些问题，本质是因为暴露了原始值，所以可以用同态加密来解决，此处利用到了模运算

### 2024.08.03
- 学习主题：80min的视频： [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
- 学习总结：首先学习了snarks是什么：一种非交互式零知识证明系统，一般是将functional commitment scheme和interactive oracle proof结合；还讲了交互式语言IOP，以及多项式承诺和IOP相结合
<!-- Content_END -->
