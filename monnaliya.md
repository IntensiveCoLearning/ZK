---
timezone: Pacific/Auckland
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
1. 自我介绍 I'm a frontend developer, I want learn web3 technology
2. 你认为你会完成本次残酷学习吗？yes, I will
3. 目前阶段对于 ZK 的了解？not know too much

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：零知识证明
- 学习内容小结：密码学的一种方法，即不泄露所拥有的信息，又能向其他人证明确实拥有这个信息。有三个特征：
  - 完整性：如果声明是真的，那么诚实的证明者可以说服验证的人
  - 可靠性：如果声明是假的，那么欺骗性的证明者没有办法说服验证的人
  - 零知识性：验证的人在验证的过程中，不会获得除声明的这个事实以外的其他信息。


### 2024.07.30

- 学习主题： [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
- 学习总结：学习了零知识证明的概念（一方面另一方证明某个声明是真的，又不泄露除声明真实性之外的其他信息），关键属性：完备性，可靠性，零知识。它的应用：隐私保护交易，身份验证，安全投票系统。两种类型：交互式零知识证明，非交互式零知识证明。所用到的密码学原语：承诺方案，同态加密，默克尔树。它在金融，身份验证和安全通信等各领域中很有应用价值。

### 2024.07.31
- 学习主题： [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
- 学习总结：
  - 介绍了零知识证明中的“模拟”概念。模拟是理解零知识的关键，通过构建“理想世界”和“现实世界”来展示如何验证一个系统的零知识特性。零知识证明是一种方法，可以让你在不泄露任何秘密的情况下，证明你知道一个秘密。举个例子，假设你有一个神奇的洞穴，有两个入口，只有你知道如何穿过洞穴。你可以通过让别人站在洞穴外看你从一个入口进去，然后从另一个入口出来，来证明你知道这个秘密路线，而不需要告诉他们具体的路线。用洞穴的故事说明了模拟器的作用，模拟器就像是有“时间倒流”能力的人，能让你相信他知道一个秘密而不需要告诉你具体是什么。这就是零知识证明的基本原理。这样的方法在保护隐私和安全方面有很多应用，比如密码和身份验证。

### 2024.08.01
- 学习主题：[（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
- 学习总结：
  - 介绍了零知识证明，在在不泄露秘密的情况下，证明某人知道某个秘密。它使用了Schnorr协议的例子来解释这一点。首先，零知识证明的基本思想是让一个人（叫做证明者）向另一个人（叫做验证者）证明他们知道某个信息，但不透露具体信息。它是通过数学方法实现的。
  - 介绍了Schnorr协议的工作原理。通过下面这些步骤，验证者可以确认证明者知道秘密信息，但不会知道具体的秘密是什么。进一步解释了零知识证明的可靠性和安全性，以及这些方法在实际应用中的重要性。
    1.	生成随机数：证明者选择一个随机数，并根据这个随机数生成一个临时的计算结果。
    2.	提交计算结果：证明者将这个计算结果提交给验证者。
    3.	验证者发出挑战：验证者随机选择一个挑战数，并把这个挑战数发给证明者。
    4.	证明者回应挑战：证明者根据挑战数和之前选择的随机数，计算出一个新的结果，并把这个结果发送给验证者。
    5.	验证结果：验证者根据证明者的回应，检查计算结果是否正确，以验证证明者确实知道秘密信息。
  - 讨论了模拟器的角色。模拟器是一个假想的工具，用来证明在零知识证明中，验证者无法区分真实的证明过程和模拟的过程。换句话说，验证者无法通过观察证明过程来获取任何额外的信息。
  - 引用了一些著名的零知识证明应用场景，如密码学中的身份验证、隐私保护的数字货币交易等。这些应用展示了零知识证明在现代信息安全中的重要作用。


### 2024.08.02
- 学习主题：20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
- 学习总结：视频中的计算机科学家Amit Sahai解释了“零知识证明”这一概念，从简单到复杂分为五个难度级别。视频通过不同难度层次的解释，从基础到深入地理解零知识证明的概念。
  1. 初学者级别：零知识证明是一种在不透露任何额外信息的情况下，证明某个陈述是真实的方法。这个概念类似于在不透露具体位置的情况下证明一张照片中的隐形小精灵的存在。
  2. 中级：零知识证明用于在不透露秘密信息的情况下，证明某事是真实的。它可以用来在没有透露任何信息的情况下，建立双方之间的信任。这个方法在计算机技术和面对面的互动中都有应用。
  3. 高级：零知识证明是一种互动，通过这种互动，两个人中的一人可以在不透露原因的情况下，证明某个陈述是真实的。尽管这些证明可能看起来令人费解，但它们可以用来证明各种陈述的真实性。例如，图三着色问题是使用零知识证明解决的一个NP完全问题的例子。
  4. 专家级：这一部分使用颜色和信封解释了零知识证明的概念。通过使用颜色组合来证明某事，而不透露颜色的原始组合。这种证明是基于概率的零知识证明，类似于加密技术。
  5. 大师级：零知识证明使用随机性来在不透露秘密的情况下证明诚实。这种方法广泛用于多方计算中，以完成复杂的任务。随机性在经典证明中可能看起来不直观，但在零知识证明中非常有用。

### 2024.08.03
- 学习主题：100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 学习总结：视频是零知识证明的介绍和历史，以及交互的证明过程和随机性的作用。鉴于这个证明过程是交互的，需要通过来回的消息传递和随机的问题来进行验证，同时还介绍了可以使用重放技术来提取知识的概念，实现了零知识证明。一些具体的应用场景：协议设计和非 NP 问题的证明。
  1. 首先介绍了经典证明和交互式证明的概念。
    - 经典证明是一个从公理到定理的推导过程。
    - 交互式证明是一个包含证明者和验证者的过程。
    - 验证者读取证明并判断其正确性。
  2. 然后介绍了交互和随机性两个新的概念。
    - 证明者和验证者之间需要进行交互，而不仅仅是证明者发送一个字符串给验证者。
    - 验证者可以通过抛硬币来决定向证明者提问的方式。
    - 由于验证者的提问是不可预测的，证明者需要能够回答所有可能的问题。
    - 我们还愿意接受一定的错误概率。
  3. 然后讲解了零知识证明的工作原理和可能性。
    - 零知识证明可以让验证者相信声明是正确的，而且几乎不可能让验证者相信声明是错误的。
    - 零知识证明通过发送随机数来实现，这些随机数是彼此独立的。
    - 零知识证明的核心是选择一种可能性，并通过发送不同的部分来说服验证者。
    - 零知识证明的目标是让验证者相信声明的正确性。
  4. 为了使得协议PV成为零知识互动证明，模拟器和输出之间应该在计算上是无法区分的。
    - 模拟器接收输入x，并在多项式时间内运行。
    - 模拟器还接收另一个输入，用于确保允许模拟器运行足够的时间。
    - 模拟器的运行时间通常是多项式时间，但可能会因为不幸的随机数而变长。
    - 零知识互动证明的定义中并没有提到验证者的内容。
  5. 证明知识的零知识证明的定义是通过多次运行提取器来验证证明者的知识。
    - 如果提取器能够多次重放并从中提取信息，则证明者具有知识。
    - 零知识证明的精确定义涉及到概率和多项式时间。
    - 当概率大于α时，我们要求提取器是多项式的。
  6. 讲解了零知识证明和承诺方案的概念。
    - 零知识证明可以用于证明一个图的三色性。
    - 零知识证明也可以用于证明一个问题是否属于NP类。
    - 承诺方案是一个包含两个协议的方案，用于隐藏和绑定信息。
  7. 零知识证明可以用于强制执行密码协议中的行为，而不泄露任何知识或信息。
    - 零知识证明可以确保协议参与者遵守协议步骤。
    - 可以通过零知识证明验证参与者发送的消息是否符合协议规则。
    - 零知识证明需要在协议开始时对内部随机性和私有输入进行承诺。
  8. 最后讲述了一个关于证明者和验证者之间互动的例子，以及问题是关于互动证明是否比Arthur-Merlin更强大。
    - 证明者和验证者之间的互动类似于之前讲到的色盲的例子。
    - 问题是关于互动证明是否比Arthur-Merlin更强大。
    - 可以将任何互动证明转换为只有验证者抛硬币的系统。

### 2024.08.04
- 学习主题：100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
- 学习总结：
  1. **零知识定义**：
    - 零知识证明的核心思想是，证明者在不泄露额外信息的情况下，让验证者相信某个陈述是正确的。
    - 这通过一个特性来实现，即在互动结束后，验证者无法计算出互动前无法计算出的任何新信息。
  2. **模拟范式**：
    - 验证者在互动后的视图应该在计算上无法区分出是通过与证明者的真实互动获得的，还是验证者自己生成的。
    - 这通过存在一个模拟器来形式化，模拟器可以生成与真实互动无法区分的视图。
  3. **概率多项式时间**：
    - 验证者在验证过程中允许使用随机性。
    - 即使包含随机性，证明也必须是健全的（高概率地拒绝错误陈述）和完备的（高概率地接受正确陈述）。
  4. **交互式证明**：
    - 交互式证明不是由证明者向验证者发送单一消息，而是多次消息交换的互动。
    - 这种互动有助于确保验证者被说服而不学到任何新东西。
  5. **计算不可区分性**：
    - 验证者在互动中的真实视图和模拟视图（由模拟器生成）应在任何多项式时间算法下无法区分。
  6. **知识证明**：
    - 如果存在一个高效算法（提取器），可以在多次运行互动时从证明者那里提取出见证（秘密信息），那么一个证明系统就是一个知识证明。

### 2024.08.05
- 学习主题：80min的视频： [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
- 学习总结：
  1. **SNARK 概述**
    - SNARK 是简洁非交互式知识论证（Succinct Non-interactive Arguments of Knowledge），用于证明某个声明的真实性。
    - SNARK 的证明很短，验证速度非常快。
  2. **零知识属性**
    - SNARK 具备零知识属性，即证明不暴露关于被证明消息的任何额外信息。
    - 在处理私密交易时，确保交易数据对公众不可见。
  3. **商业应用**
    - SNARK 在业界有广泛应用，吸引了很多商业兴趣。
    - 应用领域包括区块链扩展、跨链资产转移、合规性验证等。
  4. **区块链应用**
    - **计算外包**：利用 SNARK 生成的短证明，区块链可以扩展处理速度，例如 ZK Roll-up 技术。
    - **跨链互操作性**：使用 SNARK 证明源链资产已锁定，从而在目标链上生成相应资产。
  5. **多种 SNARK 构造方法**
    - 介绍了不同的 SNARK 构造方法，包括代数技术和多项式承诺。
    - 详细解释了多项式承诺在 SNARK 中的核心作用。
  6. **函数承诺与交互式 Oracle 证明（IOP）**
    - 使用函数承诺和 IOP 来构建高效的 SNARK。
    - 这些技术能够提升 SNARK 的效率和适用性。
  7. **新一代 SNARK 系统**
    - 支持快速证明生成是新一代 SNARK 系统的关键特性。
    - 使得在合理时间内生成大规模声明的证明成为可能。
  8. **技术突破与应用**
    - 新技术使得 SNARK 在各种应用中变得更实用，尤其是在区块链领域。
    - SNARK 技术的进步推动了其在多个行业的广泛应用。

### 2024.08.06
- 学习主题：[1-Polynomial-Interaction-and-Proof](https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html)
- 学习总结：
  1.	多项式交互与证明简介：
    - 概述了多项式交互在零知识证明中的重要性。
    - 介绍了zk-SNARKs（零知识简洁非交互式知识论证）。
	2.	基本概念：
    - 解释了多项式及其在密码学协议中的作用。
    - 描述了多项式承诺在zk-SNARKs中的应用。
	3.	多项式承诺方案：
    - 详细描述了各种多项式承诺方案。
    - 这些方案如何帮助创建紧凑且可验证的证明。
	4.	交互证明与zk-SNARKs：
    - 讨论了从交互式证明到非交互式证明的演变。
    - zk-SNARKs如何实现非交互性和简洁性。
	5.	验证者和证明者的角色：
    - 详细说明了zk-SNARKs中验证者和证明者的角色。
    - 交互模型以及证明者如何在不泄露任何秘密的情况下说服验证者。
	6.	数学基础：
    - 介绍了支撑zk-SNARKs的数学概念。
    - 使用椭圆曲线和基于配对的密码学。
	7.	效率考虑：
    - zk-SNARKs如何在证明大小和验证时间上优化效率。
    - 实现这些优化的技术。
	8.	zk-SNARKs的应用：
    - zk-SNARKs在隐私保护协议中的实际应用。
    - 区块链技术中的例子，如以太坊。
	9.	挑战和未来方向：
    - 实施和采用zk-SNARKs的当前挑战。
    - 未来可能的进展和研究领域。

### 2024.08.07
- 学习主题：[2-Non-interactivity&Distributed-Setup](https://learn.z2o-k7e.world/zk-snarks/2-Non-interactivity&Distributed-Setup.html)
- 学习总结：
  1.	引言
    - 介绍了zk-SNARKs（零知识简洁非互动知识证明）的背景和基本概念。
	2.	设定
    - 详细说明了一个分布式设置系统中zk-SNARKs的使用。
    - 介绍了参与者和各自的角色，包括证明者、验证者和第三方。
	3.	非互动性
    - 讨论了zk-SNARKs如何实现非互动性，即证明者和验证者之间无需交互即可验证信息。
	4.	分布式设置
    - 说明了如何在分布式系统中进行zk-SNARKs的设置。
    - 讨论了多方计算（MPC）协议在分布式设置中的应用。
    - 介绍了可信设置和去中心化设置的概念。
	5.	安全性
    - 讨论了分布式设置中zk-SNARKs的安全性问题。
    - 介绍了不同的攻击模型和防御措施。
	6.	具体步骤
    - 分步详解了在分布式系统中实施zk-SNARKs的具体步骤和操作方法。
    - 包括初始化、证明生成、验证等过程。
	7.	应用场景
    - 提供了zk-SNARKs在不同实际应用场景中的案例分析和应用效果。
	8.	结论
    - 总结了zk-SNARKs在分布式设置中的优势和挑战。

### 2024.08.08
- 学习主题：[3-General-Purpose-Computation](https://learn.z2o-k7e.world/zk-snarks/3-General-Purpose-Computation.html)
- 学习总结：文章中最难理解的部分是证明阶段，特别是为变量分配值和构造整体多项式的过程。这一部分的复杂性在于需要在保持多项式方程完整性的同时，确保所有添加和移位的分配变量多项式形成一个连贯的结构。
  1. **L(x) 的介绍：**
     - \( L(x) \) 表示涉及操作数变量的复杂操作序列多项式，由 V 限制。
  2. **设置阶段：**
     - 通过考虑操作变量构造 \( L(x) \)。
     - 计算与操作数变量相关的各种多项式，分配系数。
     - 建立证明密钥和验证密钥。
  3. **证明阶段：**
     - 为变量分配值以形成不同的多项式结构。
     - 添加所有分配的多项式以构造整体多项式。
     - 生成多项式有效分配的证明。
  4. **验证阶段：**
     - 解析证明并验证评估。
     - 确保多项式方程成立，确认提供的值及其各自的评估。
  5. **后果和限制：**
     - 证明者不能随意修改提供的多项式值。
     - 证明者需要使用设置阶段提供的评估和系数。
     - 设置阶段的框架限制了添加新多项式或修改现有操作数多项式的能力。
  6. **总结和回顾：**
     - 突出了证明者面临的主要问题和限制。
     - 强调了遵守设置参数的重要性。
     - 讨论了 zk-SNARKs 在维护多项式完整性方面的安全性和有效性。

## 2024.08.09
- 学习主题：[4-Construction-Properties.md](https://learn.z2o-k7e.world/zk-snarks/4-Construction-Properties.html)
- 学习总结：最难理解的部分是关于如何构建多项式以及验证过程中的数学细节。
  1. **QAP（Quadratic Arithmetic Program）介绍**：
     - QAP 是 zk-SNARKs 中用于编码电路的数学结构。它的作用是将电路的计算表示为多项式形式，使验证者可以通过多项式验证电路的正确性。
     - QAP 的核心思想是将计算分为若干个多项式，并通过这些多项式来表示电路中的每一个约束。
  2. **多项式的构建**：
     - 文章详细解释了如何通过电路的输入和输出来构建相应的多项式。多项式的构建过程中需要确保它们满足特定的约束条件，这样才能正确地表示电路。
     - 为了验证证明者的计算是否正确，验证者会检查多项式是否满足这些约束条件。
  3. **验证过程**：
     - 验证者通过计算并检查证明者提供的多项式是否满足特定的条件，从而验证证明的正确性。
     - 验证过程是不依赖于电路具体输入的，这意味着证明者可以在不泄露输入信息的情况下进行验证。
  4. **多项式的零化性质**：
     - 多项式的零化性质在 zk-SNARKs 中起到了至关重要的作用。通过确保特定多项式的值为零，验证者可以确认计算结果的正确性，而不需要实际进行计算。
     - 文章解释了如何利用这一性质来简化验证过程。
  5. **优化与简化**：
     - 为了提高验证效率，文章还讨论了如何优化 QAP 的构建过程，以及如何减少计算复杂度，使得 zk-SNARKs 更加高效。

## 2024.08.10
- 学习主题：[5-Pinocchio-Protocol](https://learn.z2o-k7e.world/zk-snarks/5-Pinocchio-Protocol.html)
- 学习总结：文章中的R1CS（Rank 1 Constraint System）与QAP（Quadratic Arithmetic Program）的转换和表示过程涉及到大量复杂的数学推导和概念
  1. **Pinocchio协议背景**：
     - Pinocchio协议旨在提高零知识证明（zk-SNARKs）的效率和实用性，主要应用于隐私保护和区块链等领域。
  2. **Pinocchio协议的核心特点**：
     - 证明生成和验证的高效性：Pinocchio通过简化的证明生成和快速的验证来提高性能。
     - 通用性：适用于任意的计算任务，而不仅限于特定的应用场景。
  3. **协议的数学基础**：
     - 文章详细介绍了构建Pinocchio协议所需的数学工具，如椭圆曲线、同态加密和双线性对等技术。
  4. **协议的构建过程**：
     - 通过多项式的表示和生成过程，协议能够有效地将计算任务转换为一个特定的证明问题。
  5. **Pinocchio协议的具体实现步骤**：
     - 将计算任务表示为R1CS（Rank 1 Constraint System）。
     - 利用QAP（Quadratic Arithmetic Program）来实现零知识证明。
     - 通过k-query来完成证明生成和验证。
  6. **协议的优化策略**：
     - 针对实际应用中可能出现的性能问题，文章提出了多种优化策略，如批量验证和减少查询次数等。
  7. **Pinocchio协议的优势和局限性**：
     - 优势：在处理复杂计算任务时，Pinocchio协议展示了显著的性能提升。
     - 局限性：尽管有多种优化，但协议在某些场景下仍可能面临计算开销大、实现复杂度高的问题。
  8. **应用场景与未来展望**：
     - Pinocchio协议广泛应用于区块链的隐私保护，如在智能合约中的应用，并有潜力在未来得到更广泛的应用。

## 2024.08.11
- 学习主题：[ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)
- 学习总结：介绍了非交互式零知识协议，特别是SNARKs（简洁非交互式知识论证）。
  1. **SNARKs 概述**：
     - SNARKs 是一种简洁的证明方式，允许证明者在不泄露任何额外信息的情况下，向验证者证明某个声明是正确的。
     - 这种证明既短小又快速，即使基础数据（例如，大小为千兆字节的信息）很大。
  2. **应用**：
     - SNARKs 在商业领域尤其是区块链领域引起了广泛的兴趣。
     - 应用包括**区块链扩展**（如ZK roll-up）和**区块链互操作性**。
     - 它们还支持**交易隐私**，确保在保持交易数据秘密的同时证明其有效性。
     - SNARKs 也适用于非区块链领域，如通过证明媒体中图像的真实性来打击虚假信息。
  3. **技术基础**：
     - SNARKs 需要一个可以信任的**设置阶段**，可能涉及为特定电路生成参数。
     - 不同类型的设置包括：**每个电路的信任设置**、**通用设置**和**透明设置**，其中透明设置最为理想，因为它不依赖于秘密数据。
  4. **SNARK 系统类型**：
     - 各种SNARK系统，如**Groth16**、**Plonk**、**Marlin**、**Bulletproofs**和**STARKs**，在证明大小、验证时间和设置要求方面提供了不同的权衡。
     - 例如，Groth16的证明非常短小，但需要每个电路的信任设置，而STARKs的证明较大，但不需要信任设置。
  5. **构建SNARKs**：
     - SNARKs 是使用**算术电路**构建的，并依赖于**多项式承诺方案**或**功能承诺**。
     - 多项式承诺方案允许对多项式进行承诺，并有效验证其在特定点的评估结果。
  6. **知识完备性**：
     - SNARKs 的一个重要属性是**知识完备性**，这意味着如果验证者接受了一个证明，就确保证明者确实知道该声明的某个见证。
  7. **现代构建范式**：
     - 现代SNARKs通常通过结合**功能承诺方案**和**交互式Oracle证明（IOP）**来构建。
     - 这种模块化方法允许通过首先设计一个IOP，然后将其与适当的承诺方案配对，来为一般电路创建SNARKs。
  8. **实际应用**：
     - 实际上，SNARK电路不是直接编写的。相反，它们是用**领域特定语言（DSL）**编写的，例如Circom或Socrates，然后编译成SNARK友好的格式。

<!-- Content_END -->