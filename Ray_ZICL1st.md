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

# Ray
1. 一个认为 ZK 很难但是还想学习的人
2. 你认为你会完成本次残酷学习吗？会的
3. 目前阶段对于 ZK 的了解？很浅

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：XXXX
- 学习内容小结：XXXX（鼓励用自己的语言描述学到的知识）

### 2024.07.30

### 2024.07.31

- 学习主题：ZK 是什么
- 学习内容小结：
    - ZK：向一个人证明一件事情是真的，但是不透露任何事实
    - ZK 中有两部分：
        - 证明者：向别人证明知道一个事实，但是不泄露事实本身
        - 验证者：证明验证者确实知道这个事实，这个过程其实是一个概率证明，可能会重复一千次
    - 为什么要研究 ZK？为了更安全，保护隐私
    - NP Complete Problems

### 2024.08.01

- 学习主题：ZK 是什么
- 学习内容小结：
    - ZK 证明的本质：利用随机性，来真正隐藏我们想要隐藏的信息。
    - ZK 需要构造数学问题，这些问题需要足够有难度，但是在量子计算面前，我们需要更难的问题，这样才能抗量子计算
    - 对于知识的具体定义需要明确，知识不等于信息，可以说是零知识证明，但是不能说是零信息证明，因为在整个证明的过程中一直都有信息的参与
    - ZK 证明的过程有两种：
        - 交互性证明
        - 非交互性证明

### 2024.08.02
- 学习主题： ZK 是什么
- 学习内容小结：
    - ZK Proof 可以解决数据的信任问题
    - 只要数据的判定是客观的，那么零知识证明就适用，零知识证明可以模拟出一个第三方，来保证某个论断是可信的
    - ZK 证明的一些用处：
        - 数据隐私保护
        - 计算压缩与区块链扩容
        - 端到端的通讯加密
        - 身份认证
        - 去中心化存储
        - 信用记录

### 2024.08.03
- 学习主题： ZK 是什么
- 学习内容小结：
    - NP Complete Problems 的典型例子地图染色问题
        - 如果你想向别人证明你有办法用三种颜色来表示地图，但是你又不想向小明透露地图上具体的颜色分布证明的方式？
            - 1.你先把地图的颜色都打乱，然后由小明随机选择地图上的两个块，然后展示那两个块的颜色，这里重点是随机
            - 2.然后重复上面 1 的过程
            - 3.重复到足够多的次数之后，小明就可以判断我是真的有能力使用三种颜色来完成一个地图，而且，小明相信这一点之后，还不知道地图上的颜色是怎么构成的
            - 上面其实就是一次零知识证明的过程
        - 在上面地图证明的例子中：
            - 每一次小明都会获取到一次信息，但并没有获取到完整的地图颜色分布，也就是没有获取到知识
            - 每一次的地图上随机揭露的两个块都是信息
            - 完整的地图上的颜色分布是知识
            - 知识是与计算难度相关，而信息不是
            - 知识是与公共所知的东西有关，而信息主要与部分公开的东西有关

### 2024.08.04
- 学习主题：ZK 是什么
- 学习内容小结：以下各种问题的中的 P 是指 polynominal 多项式，https://yzhang-gh.github.io/notes/others/p-np.html
    - 时间复杂度：
        - 多项式级复杂度：常见的算法的复杂度 O(1), O(nlogn)
        - 非多项式级复杂度：O(c^n), O(n!)
    - P 问题：通常表示那类可以有效地解决的可计算型问题，数据结构与算法课程中的问题基本都是 P 问题，时间复杂度为多项式级复杂度，也就是说可以在多项式时间内被解决
    - NP 问题：可以由非确定型图灵机 (Nondeterministic Turing machine) 在多项式时间解决的问题，简单来说，*NP 问题的求解比较困难，但是很容易验证*，P 问题是 NP 问题的子集
        - 哈密顿环问题
    - NP Complete 问题：
        - 归约：从问题 A 转化为另一个问题 B，可以用 问题 B 的解法来解决问题 A
        - 满足两个条件
            - 是 NP 问题
            - 所有的的 NP 问题都能在多项式时间内归约为它
        - 图着色问题
    - NP Hard 问题：至少是和 NP Complete 一样难的问题
        - 条件：
            - *不要求是 NP 问题*
            - 所有的 NP 问题都能（在多项式时间内）归约为它
        - 旅行商问题
        - 停机问题：这个问题已经被证明是不可能的，以太坊中的 gas 就是用来解决停机问题的

### 2024.08.05
- 学习主题：ZK 是什么
- 学习内容小结：NP Complete 问题其实就说明了零知识证明的特点：证明的过程可能非常费力，但是验证过程一定是非常简单的，可以在多项式时间内能完成的过程。而零知识证明的关键是安全，我们需要确保在证明的过程中没有出现不必要信息的泄露。怎么保证安全就很关键了。
    - 安全假设：在各个各样的系统中，安全假设很重要，需要很明确，比如一个系统的权限设计的很好，安全假设是管理员账号没有被破解。手机银行转账通过短信验证码确认，安全假设是 SIM 没有被克隆。比特币账户的安全假设是你的助记词不会被泄露，安全的前提是需要满足安全假设。
    - 安全的定义：安全需要一个数学意义上的严格定义
        - 香农的完美安全定义：假如你是一个攻击者，你通过密文获取不到任何有价值的薪酬，破解的唯一手段就是靠瞎蒙
        - 概率加密论文中的寓意安全：假如你是一个攻击者，你通过密文在多项式时间内计算不出来任何有价值的信息
        - 不可区分性：如果在两段明文中随机挑选一个在加密后无法在多项式时间内破解出来，那么我们就认为这个信息有不可区分性，是语义安全的
        - 模拟是零知识证明过程中的很重要的一点，换句话说，证明零知识的过程，就是要寻找一个算法，或者更通俗点说，写出一段代码，他运行在外部计算机系统中，但是实现了虚拟机的功能。而且在虚拟机中，需要有一个没有知识作为输入的 Zlice，可以骗过放入虚拟机运行的 Bob
            - 这里的虚拟机可以理解为一个拥有时间倒退功能的人，可以知道 Bob 预先的输入，然后造一个假的输出来骗过 Bob，Bob 并不知道世界倒退了，也不知道自己的输入被人知道了，所以在 Bob 的视角，Zlice 是那个知道答案的人


### 2024.08.06
- 学习主题：ZK 是什么
- 学习内容小结：通过模拟产生的理想世界与现实世界不可区分，由于理想世界中不存在知识，都是通过时间机器给出正确答案，所以推导出现实世界满足零知识。
    - 零知识系统的三个性质：
        - 可靠性（Soundness）：Alice 在没有知识的情况下不能通过 Bob 的验证
        - 完备性（Completeness）：Alice 在有知识的情况下可以通过 Bob 的验证
        - 零知识（Zero-knowledge）：Alice 在交互的过程中不会泄露关于知识的任何信息，这样保证了验证者 Bob 没有计算能力把和知识相关的信息抽取出来
    - 简洁的 Schnorr 协议
        - sk = a
        - pk = aG
        - 同态：椭圆曲线群有限域之间存在着一种同态映射关系
            - 有限域，我们用 Zq这个符号表示，其中素数 q是指有限域的大小，它是指从 0, 1, 2, …, q-1 这样一个整数集合
            - 在一条椭圆曲线上，我们通过一个基点，G，可以产生一个「循环群」，标记为 0G, G, 2G, …, (q-1)G，正好是数量为 q个 曲线点的集合。任意两个曲线点正好可以进行一种「特殊的二元运算」，G + G = 2G，2G + 3G = 5G，看起来这个二元运算好像和「加法」类似，满足交换律和结合律。于是我们就用 + 这个符号来表示。之所以把这个群称为循环群，因为把群的最后一个元素 (q-1)G，再加上一个 G就回卷到群的第一个元素 0G
            - 给定一个有限域上的整数 r，我们就可以在循环群中找到一个对应的点 rG，或者使用标量乘法来标识 r\*G，但是这个关系的反向计算很困难
        - Schnorr 协议利用有限域和循环群之间的单向映射，实现了最简单的零知识证明协议



<!-- Content_END -->
