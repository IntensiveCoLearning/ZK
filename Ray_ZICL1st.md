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

### 2024.08.07
- 学习主题：ZK 是什么
- 学习内容小结：模拟世界刚好证明了现实世界零知识的可靠性，因为模拟世界可以靠作弊骗过 Bob，但是实际上 Zlice 没有任何知识，那么在现实世界的 Alice 是一定有知识的，这样才能完全答对 Bob 的问题
    - 模拟世界中，通过时间倒流的超能力，可以把 Alice 的知识完整地抽取出来，这就保证了一个没有知识的 Alice 是无法让抽取器达成目标，从而证明了可靠性，这个抽取的能力被称之为抽取器
    - 区块链中随处可见的 ECDSA 就是一个简单的零知识证明系统
    - ECDSA 有一个安全隐患，如果在两次签名中使用了同一个随机数，那么签名者的私钥就会暴露出来，其实上面的 Schnorr 协议也有同样的问题，上面的抽取器就是基于这样的原理来推导出私钥
    - 从模拟世界引发的思考-我们这个世界是模拟的吗？
    - 通过随机数挑战是交互式证明零知识证明的信任根基，但是交互式的证明有很多的限制，非交互零知识证明（Non-Interactive Zero Knowledge）就很有必要性了
        - 交互式证明只能取信一个证明者并在那个时刻有效，而 NIZK 可以取信多个证明者或者所有人，而 NIZK 将始终有效
        - NIZK 的核心点是引入第三方，这里的第三方就是 Hash 函数，通过 Hash 函数将一个交互式证明变成非交互式证明的方法被称之为 Fiat-Shamir 变换

### 2024.08.08
- 学习主题：ZK 是什么
- 学习内容小结：非交互式 ZK 的关键是随机预言机
    - Hash 函数有一点小缺陷：
        - 对于 ZK 来说，需要的是一个具有一致性分布的真随机数，而 Hash 函数并不是一个真正有一致性分布的随机数
        - 但是也只能使用 Hash 函数，因为现实世界中，真正的随机预言机不存在
        - 这里有一个安全假设，那就是这个 Hash 函数是密码学安全的
            - 不使用这个假设的安全模型叫*标准模型*
            - 使用这个安全假设的安全模型叫*随机预言模型*
        - Public coin 协议：允许多方共同计算一个函数，而不泄露他们的私人输入
        - 对于任意的 Public coin 协议，都可以使用 Fiat-Shamir 变换来把整个协议压缩成一步交互
        - Fiat-Shamir 其实存在一些安全隐患需要注意：要注意应该传入的参数，如果参数不对，那么整个安全假设就会失效，就留下了一个严重的安全漏洞


### 2024.08.09
- 学习主题：ZK 是什么
- 学习内容小结：简单的一次交互只能证明简单的问题，但这远远不够
    - 对于零知识证明来说，有两个必要因素：
        - 交互：验证者通过多次反复挑战，把证明者作弊概率降低到一个极小的值
        - 隐藏随机性：验证者产生让证明者无法预测的随机数进行挑战
    - CSR（Common Reference String）：通过一段共享的字符串去除交互和隐藏随机性，这个字符串必须要事先由第三方来随机产生


### 2024.08.10
- 学习主题：ZK 是什么
- 学习内容小结：
    - NP 问题是不确定性图灵机多项式时间可以求解的问题类。所谓的不确定性图灵机，就是它每次往前走一步是不确定的，有很多个选择，只要任何一个执行路径能到达终止状态，就表示它解决了该问题 x
    - 它的执行路径是一棵树，如果我们把不确定图灵机每一步的路径选择记录下来，那么把(x, witness)交给一个确定性图灵机，那么它也能在多项式时间内解决掉 x 问题，这个执行路径的记录就叫 witness，也就是我们一直在说的知识
    - CRS 在一个证明之前就已经公开了，并且在证明者和验证者之间共享。
    - 在哈密顿环的证明过程，还不能完全算 NIZK 系统，因为这个共享字符串还不能对 Bob 公开，否则 Bob 就能计算出这个环路 c
    - 为了解决这个问题，就需要用到 Hidden bits

### 2024.08.11
- 学习主题：ZK 是什么
- 学习内容小结：
    - 在实际使用的过程中，需要将 Hidden bits 中的隐藏比特串去掉，变成一个 CRS，密码学中的陷门置换可以达到这个目的
    - 当前 Hidden bits 是目前实现 NIZK 唯一的办法
        - 基于「一致性分布」的共享 CRS
        - 实现任意 NP 语言的 NIZK Proofs
    - 通过上面的方式生成的 NIZK Proofs，它的长度要比知识长，知识就是 NP 问题中的 wintess，只要 Bob 算力够强，他就可以把证明解密
    - 那么可不可以构造证明尺寸小于 wintess 的 NIZK 呢？是可以的，这类的 NIZK 系统被称之为 NIZK Arguments
    - NIZK Atguments 系统的安全性：Computational Soundness，在这种情况下， Alice 如果算力超强，是有可能作弊的，在现实生活中，可以加大安全参数来降低作弊的可能性，但是能实现非常几只的零知识特性，而且即使 Bob 的算力很强，也很难暴力破解知识
    - P != NP


### 2024.08.12
- 学习主题：zk-SNARK 学习
- 学习内容小结：
    - 核心：
        - 加密函数：E(v)=g^v (mod  p)
        - 在同态加密中：
            - 模数 p 是双方都知道的，它通常写在加密代码中
            - 生成元 g 是一个证书，作为一个基用来生成一系列的数字（密钥，用来对数据进行加密）
            - v 就是我们要加密的值
    - 多项式是 zk-SNARK 的核心部分，用来作为证明媒介
    - 多项式的一个重要特性：不可能找到共享连续段的两条不相等曲线，也就是任何多项式在人一点的计算结果都可以看作是其唯一身份表示
    - 多项式的知识就是多项式的系数，所谓知道多项式就是指知道多项式的系数
    - 一个多项式只要有解，就可以分解成线性多项式，比如 x^3−3x^2+2x=(x−0)(x−1)(x−2)，它的解就是 0，1，2
    - 如果 prover 想要在不揭示多项式的前提下证明他的多项式确实有这两个根，那么他就需要去证明他的多项式 p(x) 是 t(x)=(x−1)(x−2) 和一些任意多项式 h(x) （例子中 x−0 ）的乘积

### 2024.08.13
- 学习主题：zk-SNARK 学习
- 学习内容小结：
    - 多项式可以被因式分解成它的根的因式的乘积，所以如果一个多项式有某些解，那么它被因式分解之后的式子中一定包含这些解的因式 -> 利用这个性质去构造证明
    - 证明过程：
        - Bob 挑选一个随机值 r，计算 t = t(r)，然后就 r 发送给 Alice
        - Alice 计算 h(x) = p(x)/t(x)，并对 p(r) 和 h(r) 进行休止，将计算结果 p, h 提供给 Bob
        - Bob 验证 p = t*h，如果多项式相等，就意味着 t(x) 是 p(x) 的因式
    - 这种校验方式要求多项式系数也是整数，对协议产生了很大的限制（这里比较难理解，需要消化一下）

### 2024.08.14
- 学习主题：zk-SNARK 学习
- 学习内容小结：
    - 如果 Alice 不知道真正的 p(x)，那么就可以会使用一个假的 p(x)，其中并不包括必须的因式，所以就会产生一个余数，导致最后算出的结果不是整数，那么 Bob 就会发现 Alice 并不真正知道这个结果，然后就会拒绝这个证明，但是这样同样也要求多项式的系数必须是证书，这样就对协议产生了很大的限制，需要让这个余数不被整除（即使这个原始值可以被整除）
    - 利用因式构造证明协议的缺陷：
        - 一旦 Alice 知道了 t(r)，就可以反过来构造一个可以整除 t(r) 的 p(r)
        - Alice 知道了点(r, t(r)*h(r))，就可以构造经过这一点的任意（高次）多项式来满足校验条件
        - 协议并没有对 prover 的多项式阶数进行约束
    - 所以关键是 r 这个值能不能隐藏起来不可见，这里可以通过模运算来解决这个问题

### 2024.08.17
- 学习主题：zk-SNARK 学习
- 学习内容小结：
    - 通过模运算形成的集合被称为有限域
    - 通过计算指数再进行模运算行为的集合构成循环群
    - 常见的同态加密方式除了整数幂取模之外，还有椭圆曲线上的倍乘
    - 然后配合这些工具，就可以对多项式进行加密处理，并且 Alice 和 Bob 后续会基于这个同态加密函数来计算
    - 但是这样构造出来的协议还是有一些问题，Bob 无法证明 Alice 使用了自己提供的加密值进行运算
    - 在 ZK 协议中，Prover 和 Verifier 之间的工作，如果 Prover 多做了一些，那么 Verifier 就可以少做一些，Verifier 多做一些，Prover 就可以少做一些


<!-- Content_END -->
