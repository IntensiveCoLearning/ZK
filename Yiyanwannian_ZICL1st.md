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

# {Punkcan}
1. 自我介绍
	1. web3 btc l2 developer。
2. 你认为你会完成本次残酷学习吗？
	1. 尝试尽力吧
3. 目前阶段对于 ZK 的了解？
	1. 还在理解公式中

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：
  - 观看youtube视频: [初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
- 学习内容小结：
  - 理解zk的本质是一个P = NP 的问题，zk是一个证明系统，可以证明一个事情是正确的，但是不会泄露任何信息。

### 2024.07.30

- 学习主题：
    - 听播客: [零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
- 学习内容小结：
    - 理解zk-SNARK 和 zk-STARK的不同
    - 理解rollup的原理, optimistic rollup 和 zk rollup的区别
    - 理解optimistic rollup的安全性问题，为什么要引入 federation, 多签和预签机制

### 2024.07.31

- 学习主题：
    - 看视频: [ZKP Lecture 1: Introduction and History of ZKP](`https://www.youtube.com/watch?v=uchjTIlPzFo`)
- 学习内容小结：
    - 以硬币和三色国土为例，理解零知识证明的概念
    - 讲解了零知识证明的历史，本人理解不是很深，还需后续学习

### 2024.08.01

- 学习主题：
    - 看文档: [探索零知识证明系列](https://learn.z2o-k7e.world/zkp-intro/toc.html)
- 学习内容小结：
  - 阅读： 探索零知识证明系列
  - 通过 地图三染色问题的零知识证明、阿里巴巴洞穴、模拟与图灵机、柏拉图的洞穴寓言 等例子介绍「模拟」


### 2024.08.02

- 学习主题：
  - 看文档: [寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E5%AF%BB%E6%89%BE%E7%9F%A5%E8%AF%86)
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
- 学习内容小结：
  - 零知识证明性质： Completeness（完备性）、Soundness（可靠性）、Zero-Knowledge（零知识）
  - Schnorr协议公式： z*G ?= R + c*PK = rG + c*(aG)

### 2024.08.03

- 学习主题：
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
  - 学习内容小结：
    - 通过弱版本的协议SHVZK证明Schnorr的安全性
    - 「抽取器」需要利用「时间倒流」的超能力才能计算出Schnorr的签名私钥
    
### 2024.08.04

- 学习主题：
  - 看文档: [证明零知识](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html#%E8%AF%81%E6%98%8E%E9%9B%B6%E7%9F%A5%E8%AF%86)
- 学习内容小结：
  - ecdsa和Schnorr算法类似
  - ecdsa和Schnorr算法都存在的缺点：两次签名中使用同一个随机数，那么签名者的私钥将会暴露出来，计算公式
      ```shell
      k = (c - c')/(s - s')
      a = (k * s - c)/e
      ```
  - 随机数必须是具有密码学安全强度的随机数，否则会导致私钥泄露
  - 作者脑洞我们生活是否在模拟世界中生存


### 2024.08.05

- 学习主题：
  - 看视频:  [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
- 学习内容小结：
  - 讲解zk-SNARK和Blockchain的结合方式：链下存储全量交易，链上验证少量交易
  - 用sony相机照片（C2PA）的例子举例说明zk-SNARK在非区块链行业的应用场景
  - 讲解NARK,zk-SNARK，（不是很懂）
  - 讲解Ploy-IOP、Multilinear-IOP、Vector-IOP, (不是很懂)

<!-- Content_END -->
