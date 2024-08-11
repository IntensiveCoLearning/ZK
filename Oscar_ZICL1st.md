---
timezone: Asia/Shanghai
---

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

---

# Oscar
1. A eco-lifelong learner.

   For the dream of  2 million😄. To surf🏄‍♀️ better in the Web3 world. Enjoy this challenging vibe and become cooler 🆒. 
2. 你认为你会完成本次残酷学习吗？Yes

3. 目前阶段对于 ZK 的了解？Have a little knowledge. 

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：Introduction and History of ZKP
- 学习内容小结：

  - 看[视频](https://mp.weixin.qq.com/s/ZIXOxidlYZExzDZuEdg8Yg)：计算机科学家 Amit Sahai 分别向五类不同水平的人群（儿童、青少年、大学生、研究生和专家）讲解零知识证明。有趣的思考：**为什么叫零知识而不是零信息、零数据** ? 🤔

  - 查看[Wiki](https://zh.wikipedia.org/wiki/%E9%9B%B6%E7%9F%A5%E8%AF%86%E8%AF%81%E6%98%8E)：[密码学](https://zh.wikipedia.org/wiki/密码学)中，**零知识证明**（英语：zero-knowledge proof）或**零知识协议**（zero-knowledge protocol）是一方（证明者）向另一方（检验者）证明某命题的方法，特点是过程中除“该命题为真”之事外，不泄露任何信息。因此，可理解成“零泄密证明”。
    - 例如：欲向人证明自己拥有某情报，则直接公开该情报即可，但如此则会将该细节亦一并泄露；零知识证明的精粹在于，如何证明自己拥有该情报而不必透露情报内容。这也是零知识证明的难点。

    - **零知识证明要具备下列三种性质：**
      - **完备**（complete） 若所要证之事为真，则诚实（意即依协议行事）的证明者能说服诚实验证者。
      - **健全**（sound） 若命题为假，则作弊证明者仅得极小机会能说服诚实验证者该事为真。
      - **零知识（zero-knowledge）** 若命题为真，则验证者除此之外，过程中没有得悉任何其他信息。换言之，仅知命题为真（而不知秘密本身）已足以“想像”出一个交互的情境，其中证明者的确知道该秘密。此性质能严格定义为：每个验证者皆有相应的模拟器，输入欲证事实时，无需求助于证明者，已可输出一套通信誊本，看似诚实验证者与证明者的通信记录。

      小结：前两种性质，更广义的[**交互式证明系统**](https://zh.wikipedia.org/wiki/交互式证明系统)亦应具备。第三种性质使该交互证明称为零知识。 零知识证明不算[**数学证明**](https://zh.wikipedia.org/wiki/數學證明)，因为尚允许有很少（但非零）概率，令作弊证明者能向验证者“证明”假命题。该概率称为可靠度误差（soundness error）。换言之，**零知识证明是概率“证明”**🤔，而非决定性。不过，也有技巧将可靠度误差压到忽略不计。

### 2024.07.30

- 学习主题：Introduction and History of ZKP
- 学习内容小结：
  - 密码学中的零知识首次出现在 1985 年的论文《互动证明系统的知识复杂性》（[GMR85]）中，由先驱者 Shafi Goldwasser、Silvio Micali 和 Charles Rackoff 提出。
  - 什么是知识？Goldwasser 等人在 1985 年 zk 的开创性论文「The knowledge complexity of interactive proof-systems」中对「知识」的定义是「the output of an unfeasible computation」，从中可以提取到两个关键词「output」和「unfeasible computation」。
    - 首先，「知识」必须是一个「输出」，不能将我们藏在心里的「信息」称作「知识」；
    - 其次，「知识」必须是关于「unfeasible computation」的，否则验证者（Verifier）根本不需要阅读证明者（Prover）的「输出」，如「1+1=2」这种常识，不能说验证者看到证明者输出「1+1=2」，验证者就获得了「知识」，因为即使验证者不看到输出，也能够自行算出「1+1=2」。
    - 什么问题算是「unfeasible」呢？在zk中，一般说NP问题是「unfeasible」。
  - 如何证明我今天学习了 ZKP 但又不需要提交 push ？ 🤔

### 2024.07.31

- 学习主题：Introduction and History of ZKP

- 学习内容小结：

  - 资料学习：[ZKPs in Web 3: Now and the Future](https://medium.com/alliancedao/zkps-in-web-3-now-and-the-future-21b459348f29)
  - 应用方向了解：
    - 数据的隐私保护：在一个数据表格中，多多少少都有一些信息不想被暴露，比如当年我的成绩单，我只想向人证明，我的成绩及格了，但是我不想让别人知道我到底考了61分还是62分，这会很尴尬。我没有心脏病，但是保险公司需要了解这一点，但是我不想让保险公司知道我的隐私信息。那我可以证明给保险公司看，我没有心脏病，但是病历的全部并不需要暴露。我是一家企业，我想向银行贷款，我只想向银行证明我具备健康的业务与还款能力，但是我不想让银行知道我们的一些商业秘密。
    - 计算压缩与区块链扩容：在众多的区块链扩容技术中，Vitalik 采用 zkSNARK 技术能够给现有的以太坊框架带来几十倍的性能提升。因为有了计算的证明，同样一个计算就没必要重复多次了，在传统的区块链架构中，同样的计算被重复多次，比如签名的校验，交易合法性校验，智能合约的执行等等。这些计算过程都可以被零知识证明技术进行压缩。
    - 端到端的通讯加密：用户之间可以互相发消息，但是不用担心服务器拿到所有的消息记录，同时消息也可以按照服务器的要求，出示相应的零知识证明，比如消息的来源、与发送的目的地。
    - 身份认证：用户可以向网站证明，他拥有私钥，或者知道某个只要用户自己才知道的秘密答案，而网站并不需要知道，但是网站可以通过验证这个零知识证明， 从而确认用户的身份。
    - 去中心化存储：服务器可以向用户证明他们的数据被妥善保存，并且不泄露数据的任何内容。
    - 信用记录：信用记录是另一个可以充分发挥零知识证明优势的领域，用户可以有选择性的向另一方出示自己的信用记录，一方面可以有选择的出示满足对方要求的记录分数，同时证明信用记录的真实性。
    - 构造完全公平的线上数字化商品的交易协议。
    - 更多的例子，可以是任何形式的数据共享，数据处理与数据传输。



### 2024.08.01

- 学习主题：Introduction and History of ZKP

- 学习内容小结：
  - ZKPs 最早的用例：Zcash 创始团队创建了 ZKP 变体 zk-SNARK（简洁非交互式零知识论证），以支持 Zcash 网络中的隐私/私人交易时。
    - PLONK：是一种高效的零知识证明协议，特别适用于构建可扩展的和高效的零知识证明系统。PLONK的全称是“Permutation Argument for Linearized Polynomial Commitments”，是对之前的zk-SNARKs（简洁非交互式零知识论证）的一种改进。
    - Circom：是一个用于构建和编译零知识证明电路（比如PLONK电路）的框架。它允许开发者使用一种简化的结构化语言来定义电路，然后将这些电路转换为零知识证明所需的逻辑形式。
  - 🤔 无论是精妙的数论定理，地图三染色问题，还是电路可满足性问题。证明存在的意义是什么？
    - 所有的证明都体现了「证明」与「验证」的「不对称性」。证明可能是一个非常耗费算力，或者脑力的活动，无论是耗时几百年的「费马大定理」，还是比特币中的 POW 证明，这些证明都凝结了在寻找证明过程中所消耗的能量，证明过程可能是超乎寻常的复杂，偶尔需要天才横空出世。而验证过程一定（或者应该）是一个非常简单的，机械的，在（多项式）有效时间内且能终止的活动。
    - 某种意义上，这个**不对称性**真正体现了证明的意义，展示了零知识证明的价值。粗略看，「证明」是「逻辑」的产物，但「逻辑」与「计算」却又有着密不可分的联系，大家可能模模糊糊感觉到一些关于「证明」与「计算」之间的关联，它们贯穿始终：如机械推理、证明表达、交互计算 。这是一个有趣但更宏大的哲学问题。

### 2024.08.02

- 学习主题：Introduction and History of ZKP

- 学习内容小结：

  - **PLONK**：是一种高效的零知识证明协议，特别适用于构建可扩展的和高效的零知识证明系统。PLONK的全称是“Permutation Argument for Linearized Polynomial Commitments”，是对之前的zk-SNARKs（简洁非交互式零知识论证）的一种改进。**PLONK支持通用电路，这意味着它可以用于多种类型的计算任务，而不仅限于特定的应用。**

  - **Circom**：是一个用于构建和编译零知识证明电路（比如PLONK电路）的框架。它允许开发者使用一种简化的结构化语言来定义电路，然后将这些电路转换为零知识证明所需的逻辑形式。Circom 通常与 PLONK协议结合使用，以生成所需的证明和验证机制。PLONK 协议是实现 ZKP 的一种具体协议，而 Circom 是开发和构建与 PLONK 兼容的电路的工具。在零知识证明的生态系统中，它们各自发挥着重要的作用。

### 2024.08.05

- 学习主题：Overview of Modern SNARK Constructions
- 学习内容小结：
  - ZKP、SNARK 和 STARK 等这些密码学概念随着最近区块链的兴起变得热⻔起来。但是，它们经常会被误解和混用。其实，所有这些概念都属于一个更广义的范畴，叫做证明系统 (Proof System)，或者叫做密码学证明（Cryptographic Proof）。零知识证明和 SNARK、STARK 之间都有交叉的部分，但并不相互包含。它们之间的关系可以用一张图来表示。
  - 简洁性的证明系统必然是论证系统。结合非交互性，就有了简洁非交互式论证 (Succinct Non-interactive ARGument, SNARG)。如果一个 SNARG 同时是一个知识论证，它就被称为简洁非交互式知识性论证 (Succinct Non-interactive ARgument of Knowledge, SNARK)。SNARK 只具有简洁性和非交互性，并不一定具有零知识性。如果有零知识性，应该叫 zkSNARK。🤔

    ![Image](https://mmbiz.qpic.cn/mmbiz_png/SibzTfiakrIr2c4IOPvSlsRjDfmORJV7NyOqIBlterqNib6R3N2nkVhsAybDzBbTnyp6g87BVOdDEialrvdiagOFxjQ/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2024.08.06

- 学习主题：Overview of Modern SNARK Constructions
- 学习内容小结：
  - 构造通用、简洁、非交互、公开可验证的零知识证明，简称 zkSNARK。如何构造？🤔
    - 首先讨论了 NP 的刻画方式，包括图灵机、电路以及 R1CS 等数学问题。
      - 有点吃力，如何把枯燥的数学变的有趣呀😯

    - 然后讨论了实现简洁性的必要方式：要么假设计算是均匀的，要么使用预处理。
    - 最后，理想模型中构造零知识证明比直接在非交互场景中构造更加方便，怎样将理想模型中的零知识证明转化为 ZK-SNARK。


### 2024.08.07

- 学习主题：Overview of Modern SNARK Constructions
- 学习内容小结：
  - ZK-SNARK 项目中的代表是 Layer1 解决方案 mina protocol。它通过递归零知识证明方式，在保证区块链安全性的同时极大提升了公链可扩展性（TPS）。支持开发者基于递归零知识证明与智能合约开发ZKapp，可以用于：匿名投票系统、（买保险时）健康信息验证、（借贷时）信誉信息验证等。
  - 准备找相关 ZK 比较成熟的具体应用场景了解学习哈。
    - [zk-merkle-tree 库：使用 zkSNARK 在以太坊上进行匿名投票](https://foresightnews.pro/article/detail/47366) 
    - 区块链行业与 ZK 结合，如利用ZK Rollup（zkSync, StartkNet, Scroll等）生成有效性证明来证明状态变化的正确性。
    - ZK-Email 通过验证电子邮件的 DKIM 签名的 ZK 证明来验证电子邮件的真实性，进而用邮箱控制以太坊合约钱包。


### 2024.08.08

- 学习主题：Overview of Modern SNARK Constructions
- 学习内容小结：
  - **zkSNARK**，**z**ero-**k**nowledge **S**uccint **N**on-interactive **AR**guments of **K**nowledge：
    - **S**uccinct：证明的数据量比较小
    - **N**on-interactive：没有或者只有很少交互。
    - **AR**guments：验证者只对计算能力有限的证明者有效。拥有足够计算能力的证明者可以伪造证明。这也叫“计算可靠性"（相对的还有”完美可靠性"）。
    - of **K**nowledge：对于证明者来说在不知道证据（**Witness**，比如一个哈希函数的输入或者一个确定 Merkle-tree 节点的路径）的情况下，构造出一组参数和证明是不可能的。
  - 零知识证明大体由四部分组成：
    - **多项式问题的转化** - 需要证明的问题转化为多项式问题 t(x)h(x) = w(x)v(x)，证明者提交证明让验证者确认多项式成立。
    - **随机挑选验证** - 随机选择验证的数值 s，验证 t(s)h(s) = w(s)v(s)。相对于验证多项式相等 t(x)h(x) = w(x)v(x)，随机挑选验证，简单，验证数据少。随机挑选验证，安全性肯定不及多项式等式验证，但如果确实足够随机，安全性还是相当高的。
    - **同态隐藏** - 同态隐藏指的是函数的一种特性。输入的计算和输出的计算保持“同态”。以加法同态为例，满足如下的三个条件的函数 E(x)，称为加法同态：1. 给定 E(x)，很难推导出 x. 2. 不同的输入，对应不同输出 3. E(x+y) 可以由 E(x)，E(y)计算出来。乘法同态类似。
    - **零知识** - 证明者和验证者之间除了“问题证明与否”知识外，不知道其他任何知识（不知道随机挑选值，不知道挑选值的多项式计算结果等等）。

### 2024.08.09

- 学习主题：Overview of Modern SNARK Constructions

- 学习内容小结：

  - 了解，零知识证明四部分组成：多项式问题的转化，随机挑选验证，同态隐藏以及零知识

  - 需要零知识证明的问题先转化为特定的NP问题，挑选随机数，设置参数，公布 CRS。证明者，在求得证据的情况下，通过 CRS 计算出证据。验证者再无需其他知识的情况下可以进行验证。

  - 逻辑框架：🤔

    ![](https://img.learnblockchain.cn/2020/01/25/15799706341243.jpg!/scale/40)





### 2024.08.11

- 学习主题：ArkStream Capital：零知识证明行业研究
- 学习内容小结：
  - ZKP 区块链技术发展路径: 围绕扩容、隐私、 兼容性、加速和互通性。未来展望：ZK将成为加密网络的基础，所有基于互联网的应用和服务都将有 Crypto 版本，并使用ZK进行加速和扩容。
  - ZKP 区块链应用: ![](https://mmbiz.qpic.cn/mmbiz_jpg/9boz8OkE5jOrYkuhk3yaOwqx9rEic7uY2j1icADTdxaJFUqU1uyybSnc70edULZfsH5ibuz5FqI48kT8vkLTaxBmQ/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)
  - ZKP 非区块链应用：![](https://mmbiz.qpic.cn/mmbiz_jpg/9boz8OkE5jOrYkuhk3yaOwqx9rEic7uY26zadOZW9NWgOO0jIxpMykfsaiaWWZs1p5rWCW75TjPQlLV5DKWBibREA/640?wx_fmt=jpeg&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)

### 2024.08.12

- 学习主题：
- 学习内容小结：






<!-- Content_END -->
