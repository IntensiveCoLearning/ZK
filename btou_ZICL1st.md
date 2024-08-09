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
1. 自我介绍
btou
2. 你认为你会完成本次残酷学习吗？
For sure.
3. 目前阶段对于 ZK 的了解？
zero.

## Notes

<!-- Content_START -->

### 2024.07.29
零知识证明的5个级别
level 1 child
零知识证明就是告诉你某件事是真的，但是不告诉你任何原因
eg.企鹅与海雀
为什么使用零知识证明？
在更大程度的保护个人隐私的情况下来证明“我是我”这个问题

level 2 teen
eg. 密码箱

解决什么问题？
隐私和信任的问题
为什么使用零知识证明？
证明有一个秘密，但是不去告诉这个秘密的具体信息

level 3 college student
在区块链领域，零知识证明只是一个开始
eg. NP completed problems

不是为了提效，是为了解决之前无法解决的问题

具体应用：零知识证明下的选举

level 4 grad student
实际应用中，弄清楚哪里能用零知识是很困难的
利用随机性来掩藏我们想要隐藏的信息

level 5 expert

知识和数据和信息
知识作为哲学也解释不清的一个问题，怎样能够和数学&计算机联系起来

从医药的领域来说，可以不揭示这个药的化合物，就能证明这个药有效

非交互性和可验证性

怎样将零知识证明来证明更复杂环境的更多问题
- 学习内容小结：
初步从5个阶段由浅入深认识了零知识证明，某一些概念对于我来说还是有难度的，希望自己能坚持学习。

### 2024.07.30

zk proof：一场无知游戏
昨日学习内容回顾：给五个从child到expert阶段的人解释什么是zk&案例

新内容：
区块链上的实际应用：
zk-SNARKs和zk-STARKs是什么和优缺
zk-SNARKs——高效，手续费低，相对的风险性高且不透明
eg.怎样证明作业是自己完成但是不展示如何完成
使用一种特殊方法将作业和一张纸条强关联，让老师看到纸条的时候相信作业完成
zk-STARKs-够透明，大家都可以验证，扩展性强，安全度更高但是应用率低，开发者生态与工具不够完善
eg.用哈希函数生成一个盒子，这个盒子在没完成作业的时候会自毁
生成盒子的过程很快（可扩展性）

Optimisitic Rollup和ZK rollup：
根本区别在于验证方式
OP：验证状态在处于被质疑的状态的时候才证明
zk：每一批交易上链时都会有证明，gas更高

### 2024.07.31
validiem
有效证明数据储存在链下，提高了吞吐量，降低gas成本
弊端：作恶成本低
探索零知识证明系列（一）

证明的发展与延伸：

希腊人发明公理与逻辑，用证明来说服彼此，这是一种去中心化的争辩。


符号系统的发明，使得推理证明系统化。

证明的代码化：码农码的不是代码，是数学证明

交互式证明和零知识证明

Alice和Bob的零知识对话

关于零知识证明的一个新的类比：零知识证明技术可以「模拟」出一个第三方，来保证某一个论断是可信的

知识与信息的区别：
「知识」是与「计算难度」相关，而「信息」则不是

「知识」是与公共所知的东西有关，而「信息」主要与部分公开的东西有关

### 2024.08.01
零知识与模拟

web2的证明是建立在安全假设有效的基础上的
eg.WEB3钱包安全的安全假设：首先你的助记词不能让别人知道，手机钱包里私钥保存加密算法足够强，密钥派生算法正规，你不能忘记助记词
以前的安全都是有前提的
安全的定义（层级由高到底）
完美安全的定义：假设你是一个攻击者，你通过密文获取不到任何有价值的信息，破解的唯一手段就是靠瞎蒙。
放松些要求，语义安全
语义安全的定义：假设你是一个攻击者，你通过密文在多项式时间内计算不出来任何有价值的信息。

理解不可区分性

证明的零知识过程，等价于构造（寻找）一个「模拟」算法，这个算法能够让模拟器来模拟出一个「没有知识」的理想世界。

模拟器其实只是一个图灵机。
### 2024.08.02
今日请假

### 2024.08.03
寻找知识

「零知识证明」并不是通过给出一个不允许发生的事件列表来定义，而是直接给出了一个最极致的「模拟条件」

Schnorr协议
椭圆曲线这一块学起来略费力，不太看得懂

### 2024.08.04
今日请假

### 2024.08.05
今日加班，本周请假第一次

### 2024.08.06
证明的媒介：
长度为10的位数组证明实验
多项式的举例看不太懂，但是在最后的验证逻辑那一块是可以看懂的，明白了多项式作为数学依据体现在zk-SNARK核心部分的可行性
到此为止证明方式的缺点：协议中并没有采取任何措施去保证参与方必须按照协议的规则生成证明，所以参考之前学习到的“安全假设”，目前的验证的可行性是在双方都按照协议这个假设来保证的
模糊计算：
rg：绳子绕圈模运算实例
模运算最重要的性质就是运算顺序无所谓。

### 2024.08.07
限制多项式：
如何确保verifier在提供证明时没有作恶，提供的证明是通过和prover一样的多项式得出的
KEA：Bob和Alice彼此都不知道要求的幂是什么，与此同时作为Verifier的Bob没有办法通过作恶来得到需要被验证的结果
有了 KEA，就可以约束prover只能通过用verifier提供的加密值去构造证明了
Pinocchio 协议？Groth16？
怎样进行证明的提效？
需要重复使用，公开，可信，又不会被滥用的秘密参数

### 2024.08.08
是否只要是能够用多项式表示的程序都可以做证明？
将要证明的程序转换为数学多项式表达的形式
算数电路是什么概念？

### 2024.08.09
今日请假，本周请假第二次
<!-- Content_END -->
