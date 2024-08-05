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
infra engineer mainly on solana eco.
2. 你认为你会完成本次残酷学习吗？
sure!
3. 目前阶段对于 ZK 的了解？
I've done some projects about zk poker game, zklogin with groth16. Want to known more about zkp.

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：(二)理解模拟 （三）寻找知识
- 学习内容小结：
1. 所谓「模拟条件」是指，通过「模拟」方法来实现一个「理想世界」，使之与「现实世界」不可区分；而由于在理想世界中不存在知识，所以可以推导出结论：现实世界满足「零知识」。
2. 「零知识」保证了 验证者 Bob 没有（计算）能力来把和「知识」有关的信息「抽取」出来。不能抽取的「知识」不代表不存在。「可靠性」保证了知识的「存在性」。
3. Schnorr协议 verifier： z*G = (r+c*sk)*G = R + c*(sk*G)= R + c* PK， prover 用随机数 r 保护私钥sk，因为任何一个秘密当和一个符合「一致性分布」的随机数相加之后的和仍然符合「一致性分布」
4. Schwatz-Zippel 定理：如果 r + a*x = r' + a'*x 要成立，极大概率上 r=r'，a=a' 都成立。也就是说， Alice 在 c 未知的前提下，想找到另一对不同的 r',a' 来计算 z 骗过 Bob 是几乎不可能
5. 知识提取器：同一个随机数 r ，发送两个c, c'得到两个z, z' 能反推出私钥

### 2024.07.30
- 学习主题：(四）随机挑战
- 学习内容小结：
1. 交互式证明系统需要验证者 Bob 在交互中提供一个或若干个「随机数」来挑战。所谓的非交互可以看成是只有「一轮」的证明过程，即Alice 直接发一个证明给 Bob 进行验证。
2. 采用 Hash 函数的方法来把一个交互式的证明系统变成非交互式的方法被称为 Fiat-Shamir 变换
### 2024.07.31
- 学习主题：(五）埋藏「秘密」
- 学习内容小结：
1. witness 其实是知识，零知识证明系统正是为了保护 witness 不泄露的前提下，实现 NP 问题的验证
2. zk 几乎正交地提供了另外一种创造信任的方式，就是通过交互进行概率性证明，同时提供信任。正如 Vitalik 所说，他们是正交于共识协议的另外一种非常重要的区块链核心技术。
3. 密码学基础 https://zkiap.com/
4. 密码学基础 https://toc.cryptobook.us/
5. 计算理论 Computational Complexity: A Modern Approach》，另一本是《Computational Complexity: A Conceptual Perspective by Oded Goldreich》

### 2024.07.31
- 学习主题：ZKP Lecture 1: Introduction and History of ZKP
- 学习内容小结：以前第一次听是一句也听不懂，现在居然能听懂了

### 2024.08.03
- 学习主题：ZKP Lecture 1: Introduction and History of ZKP
- 学习内容小结：零知识二次剩余，Bob 能够验证 
 是二次剩余，但无法了解到 
 具体是多少。即使交互多次，由于每次 Alice 都会随机选择一个新的 ，Bob 无法构造出 ，得到的仅是一串随机数。
### 2024.08.04
- 学习主题：zkcompression
- 学习内容小结：
1. 核心思想：交易可以将帐户数据作为交易负载的一部分传递，而不是将所有帐户存储在磁盘上并在需要时读取它们。我们可以通过使用 Merkle 树来确保提交交易的用户提供正确的状态。 Merkle 证明是提交某些数据的一种方法。这样，可以根据承诺来验证证据，以验证已传入正确的状态并且用户对所提供的状态没有不诚实。
### 2024.08.05
- 学习主题：state compression
- 学习内容小结：
1. 先学习没有zk的情况，solana account state 存在validator的rocksdb中，是可信的，长期账本存储在归档节点中如Google Bigtable或者IPFS或者中心化存储，不可信需要验证，但是账本数据更便宜，所以将state数据存在账本中，计算Merkle root并存储在account state中做验证。
2. 压缩nft 存储metadata在ledger，没有token account, mint account。account state 由metaplex提供程序管理，除了concurrent merkle tree 账户还有一个账户存储必要的信息，我猜是和ledger信息有关，ts客户端根据这些信息可以找到nft的ledger。我们写ts就能创建压缩nft了。ledger 会被 rpc provider 转移到 archival node，但是对rpc请求是透明的
3. zk compress 非常类似了，压缩nft由于是新发行的，所以不需要基于历史account state变更。如果希望压缩一些已经存在的账户余额呢？首先就需要证明初始余额的正确性。merkle proof 随着叶子结点增加而变大，zk compression 的证明大小是恒定的，zk可以证明您进行了一定的计算并得到了一定的结果。一旦有人得到结果和证明，他们就可以验证你是否正确地完成了计算，而无需实际运行计算。zk 可以做隐藏，另外zk即使不用来隐藏也是可以的，Because you’re turning a problem that requires running 1000 computation steps (or even a million) into a problem that requires just verifying one proof to know that the computation has been done correctly.
4. ZK Compression uses the same technology to run the actual Merkle tree membership logic. So, it has a circuit that can take the account data, a proof (128 bytes), and verify that the data is indeed part of the "commitment" on the chain. 虽然普通的 Merkle 证明是 Log 2 (N)，但 ZK 压缩始终是恒定的，因此您可以在一次承诺下拥有大量账户。生成此证明可以在链外完成，但验证此证明必须在链上完成，因为程序需要知道您为帐户提供了正确的数据，然后才能继续执行。


<!-- Content_END -->
