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

# Dust
1. 自我介绍
爱好者
2. 你认为你会完成本次残酷学习吗？
会
3. 目前阶段对于 ZK 的了解？
了解一些

## Notes

<!-- Content_START -->

### 2024.07.29
本身有zk基础，所以跳过前面部分，改为其他zk相关自学内容
- 学习主题：BLS签名
- 学习内容：
1. BLS签名验证过程 即e(P, H(m)) = e(G, S)
2. BLS签名聚合，即S=S1+S2+...+S1000情况下，根据pairing的特性，依旧能满足验证
3. 密钥聚合和n-n多签，在对私钥S和公钥P进行聚合，聚合后同上原理进行验证
4. m-n多签，需要生成成员密钥（成员密钥中包含私钥及聚合公钥对参与序号进行签名），在此基础上结合同上原理进行验证

ref: https://learnblockchain.cn/article/1711

### 2024.07.30
- 学习主题：交互式GKR Sum-Check协议
- 学习内容
1. 交互式协议，需要进行多轮交互，每轮交互将推进一次证明，交互轮次等于多项式degree
2. 初始阶段prover需要产生声明，其后进入交互证明过程
3. 每一轮需要verifier生成挑战值，挑战值会被prover用来产生下一轮多项式
4. 最后一轮verifier产生挑战值后，从Oracle处获取多项式取值进行对比，对比通过则完成

https://learnblockchain.cn/article/6188

### 2024.07.31

- 学习主题：Shamir's Secret Sharing
- 学习内容:
1. SSS算法原始秘密只能通过使用最小数量的共享来重建，这允许不同的各方进行合作，而无需完全信任彼此，原始秘密只能通过使用最小数量的共享来重建，这允许不同的各方进行合作，而无需完全信任彼此
2. SSS算法基于多项式实现，秘密隐藏于多项式常数项中，在3-5的SSS方案中，会产生一个degree为2的多项式，每个人持有多项式上的一个点，因此任意三个人通过插值均可以还原出该多项式
3. 关键问题：秘密/多项式系数的产生和销毁，重建过程中每个人需要暴露自己的知识？

### 2024.08.01

- 学习主题: circom-mp-mpdz学习
- 学习内容:
1. example native-search中circom用于对于input1数组进行查找，查找目标为input2单个数字
2. example 流程中第一步使用circom-2-arithc进行circom到电路的转换，转换后生成4个目标文件 circuit.txt debug.json circuit_info.json report.json
3. 每次输入参数由example下py文件生成，output记录了正确匹配的次数
4. 函数的调用为直接通过命令行调用，因此不存在跨语言调用的问题

### 2024.08.02

- 学习主题: bristol format
- 学习内容：
1. 
### 2024.08.02

- 学习主题: bristol format
- 学习内容：
1. 
### 2024.08.02

- 学习主题: circuit debug 文件
- 学习内容：
1. 主要分成nodes、signals、gates三个结构
2. gates代表操作，比如Add，gate下id关联到nodes
3. node下signals id关联到signals下
4. signals下主要包含in、out等signal、常量以及中间变量以random命名


### 2024.08.03

- 学习主题: lattigo学习
- 学习内容：
1. lattigo为一个实现基于格的同态加密工具
2. lattigo支持BFV、CKKS、RLWE、BTP方案
3. 在上文MP-SPDZ的学习中可以看到，其接收MPC文件的电路格式以及PlayerData下的InputData，但是对于lattigo来说好像并不能很好支持对电路的理解，所以可能需要手动解析对于mpc文件的理解
4. 在mpc的计算过程中，仅需要进行计算，而不像zk一样要产生proof以及验证，即使同样是circom电路


### 2024.08.04

- 学习主题: circom学习
- 学习内容: 
1. circom证明电路常见设计方式，包括为0判断、选择等
2. circom 二进制约束代码


<!-- Content_END -->

