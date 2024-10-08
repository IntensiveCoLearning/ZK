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

# {ocean}
1. 自我介绍
blockChain 开发工程师
2. 你认为你会完成本次残酷学习吗？
sure!
3. 目前阶段对于 ZK 的了解？
做过一些基础的zk工作

## Notes

<!-- Content_START -->


Notes
### 2024.07.29
- 学习主题：初步理解zk 是什么
- 学习内容小结：
1. 证明者需要花费巨大的资源进行证明。可以通过分布式或者云进行并行化计算
2. 知识与数据不同
3. 零知识问题的核心是np 问题

### 2024.07.30

### 2024.07.31 
(1-Polynomial-Interaction-and-Proof)
多项式可以被因式分解成它的根的因式的乘积。这个性质就意味着，如果一个多项式有某些解，那么它被因式分解后的式子中一定包含这些解的因式。 有了这个性质，我们就可以愉快地去做一些证明啦。
Schwartz-Zippel定理是一个关于多项式和有限域的基本结果，它给出了非零多项式在有限域上的零点数量的一个上界。这个定理在计算机科学和密码学中有很多应用，如概率算法、多项式插值和零知识证明。

### 2024.08.01 
3-General-Purpose-Computation
总结一下本文证明协议的大致思路为：

将要证明的程序转换为数学语言表达的形式（即加减乘除的计算）
用多项式在某处的取值来进行计算以此表示数学计算，进而进行证明
用多项式在多处的取值来进行计算表示多个数学运算，进而加以证明
对证明的“程序”在不同计算中使用的相同的变量进行约束

### 2024.08.02 
2-Non-interactivity&Distributed-Setup

一般問題可分成兩類： P問題 和 NP問題 。P問題指的是在多項式時間內可解 的問題。 NP問題（Non-Deterministic Polynomial Problem，非確定性多項式問題），指不能在多項式內可解，但是可以在多項式時間內驗證 的問題。
●选择一个随机数 α
●计算 a′=aα(modn))
●提供一个元组 (a, a′) 给 Bob, 然后让他对这 2 个值执行任意的求幂运算，返回结果元组 (b,b′) ( The α-shift remains the same. i.e. b′=bα(modn) )
我们可以通过如上方法验证 prover 是否是真的使用了 verifier 提供的值 gs0,gs1,…,gsd 来构造证明的


### 2024.08.04 
2-Non-interactivity&Distributed-Setup
即使理论上多项式参数 ci  是一个很广的取值范围内的值，在实际中, 这个范围可能很有限（比如前例中的 6），这就意味着 verifier 可以在有限范围的系数组合中进行暴力破解，获取 P 的知识 , 最终计算出一个与 P 的答案相等的结果 :
比如 V 将每个系数的取值范围定为 100，多项式阶数为 2，那么大概只会有 100 万种不同的组合，可以认为 V 暴力破解 P 的密钥只需要少于 100 万次的迭代.更重要的是，对于一个安全的协议, 即使在只有 1 个系数，值为 1 的例子中，安全协议也必须能够保证其安全 !!!

我们可以使用随机值 δ (delta)来 “shift” 这些值, 如 (gp)δ现在，为了提取知识，就必须首先要知道一个不可知的值 δ。通过引入这个随机值的方式，我们将系数隐藏起来，实现零知识的功能。


<!-- Content_END -->
