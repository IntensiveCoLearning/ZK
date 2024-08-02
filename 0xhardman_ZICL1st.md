---
timezone: Asia/Shanghai
---

 # 中国标准时间 (UTC+8)

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
最硬的男人
2. 你认为你会完成本次残酷学习吗？
必须能
3. 目前阶段对于 ZK 的了解？
懂一点点  

## Notes

<!-- Content_START -->

### 2024.07.29
#### 用 5 种难度解释一个概念

1. Child:
很喜欢这个例子：找一张海豹群照片里企鹅，我证明我找得到企鹅，但不透露企鹅的位置。
此时只需要用一块大板子挡住照片，但只漏出企鹅即可。

2. Teen:
一个带密码的秘密罐子，把秘密投进罐子里，此时除我以外没有人能知道秘密，除非有人知道密码。
那么如果一个人说出了我的秘密就说明他知道密码。 
关键是不能暴露秘密

3. College Student:
ZKP的核心是两个人的交互
进行ZKP前得明确证明什么
NP-Complete Problem: NP-complete problems are a class of computational problems where an efficient, algorithmic solution has yet to be found
NP-Complete-三色问题
ZKP不是第一步第二步第三步，而是在一定概率上可以证明某事
（比如三色问题，不断的随机挑两个颜色，如果很多很多次都是对的，那么就可以证明三色设置是对的）

4. Grad Student 
ZKP解决人的不信任问题
ZKP的瓶颈在验证者，但可以考分布式并行计算加快验证。

5. Expert
ZK!=ZK information
非交互性但可验证性
ZK的未来：
量子计算下怎么增加难度

### 2024.07.31
零知识证明是打通链上数据与链下计算的关键技术，也是实现链上数据隐私保护的重要途径

理解证明：洞见-符号推理-程序-交互

零知识证明：
1. 数据的隐私保护
2. 计算压缩与区块链扩容
3. 端到端的通讯加密
4. 身份认证
5. 去中心化存储
6. 信用记录

### 2024.08.01
#### 安全性与零知识证明总结

##### 1. 安全假设

在讨论任何系统的安全性之前，必须明确其安全假设。例如：
- 系统权限隔离假设管理员账号未被破解。
- 手机银行软件假设手机SIM卡未被克隆。

每个感觉安全的系统都基于大量安全假设，如比特币私钥的安全性依赖于助记词不被暴露、私钥保存加密算法足够强等。

##### 2. 安全定义

讨论安全性时需要明确其数学意义上的定义。香农从信息论角度给出了完美安全的定义：
- **完美安全**：攻击者通过密文获取不到任何有价值的信息，破解的唯一手段是瞎蒙。

但由于完美安全定义过于严格，实际应用中难以满足。Goldwasser 与 Micali 提出了**语义安全**的概念：
- **语义安全**：攻击者通过密文在多项式时间内计算不出任何有价值的信息。

##### 3. 信息不可区分性

为了更好地理解“计算不出来信息”这一概念，引入了**不可区分性**：
- 攻击者随机产生两段等长的明文并交给加密者。
- 加密者随机挑选一个明文进行加密，产生密文c。
- 攻击者在多项式时间内无法区分密文c的来源，则加密算法是语义安全的。

##### 4. 零知识证明

理解不可区分性后，回到零知识证明：
- 零知识证明是指一个交互式系统在不泄露任何额外信息的情况下，证明某个命题的真实性。

注：不可区分性在概率意义上可分为完全不可区分、统计不可区分和计算不可区分。在本文中，不需要深入理解这些概念的差别。

<!-- Content_END -->
