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

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# Draculabo
1. 自我介绍
我叫 Draculabo，有 2 年的 WEB 工作经验，主要是 React，Vue。也搞过 WEB 全栈，后端主要是 NodeJs、Go、.NET。
2. 你认为你会完成本次残酷学习吗？
会
3. 目前阶段对于 ZK 的了解？
对ZK有初步的了解，目前正在看[WTF ZK](https://www.wtf.academy/docs/zk-101/)

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：XXXX
- 学习内容小结：XXXX（鼓励用自己的语言描述学到的知识）

### 2024.07.30
- 学习主题：零知识证明理论
- 学习内容小结：
1. 零知识证明是一种主要用在保护隐私方面的论证，用于告诉他人某些信息，而不透露信息本身的内容。
2. 零知识证明可以分为交互式零知识证明和非交互式零知识证明，交互式证明需要两个角色：验证者和证明者，而非交互式证明只有证明者，证明者会向验证者提出某种信息而不透露信息本身的内容，验证者将会去验证信息的合理性。
3. 例子：地图三染色、数字签名、哈密尔顿环路、匿名投票
4. 三个性质：零知识（证明者不会向验证者透露知识）、完备性（证明者如果有知识，验证者一定能验证该论证）、可靠性（如果证明者造假论证，验证者一定能够发现）
5. zkSnark，一种零知识密码学工具，用于快速根据某个问题生成零知识证明。

### 2024.07.31
- 学习主题：同态加密与模运算
- 学习内容小结：
1. 根据代数基本定理，两个阶数最高为d的多项式，他们的相交点数量一定不会超过d个，而且其中一个多项式的解集合一定是另一个多项式解的子集。
2. 当证明者想向验证者验证它知道验证者的多项式t(x)时，可以通过p(x) = h(x) * t(x)来证明，但是这种方式有碰撞风险（f(x)，为了防止碰撞风险的问题，我们要求h(x)一定是一个整数，即 p(x) / t(x) 不能有余数。
3. 【2.】提到的方案也有风险问题，证明者可以随机构造多项式，以获取在某处与t(x)的交点来爆破t(x)。
4. 为了解决随机碰撞的问题，在[2.]的基础上提出了同态加密的方案。公式为：E(v)=g ^v(mod n)，v为加密的值 ，g为私钥，n为公钥。

### 2024.08.01
- 学习主题：算术电路
- 学习内容小结：
1. 算术电路是指在计算复杂性理论中，计算多项式的一个计算模型。对于一个给定的域F，一个算术电路计算一个在F[x1,...,xn]中的多项式。F={0,...,p - 1}，基于某一素数 p > 2
2. 算术电路是一种有向无环图
3. 性质：固定性（在证明中不可动态增减）、丰富性（传递的是有限域的数字，而不是二进制）、约束性（可以用作计算，也可以用于约束流转信号的状态转换）
4. 学习零知识证明中各种常见的算术电路

### 2024.08.02

- 学习主题：承诺方案
- 学习内容小结：
1. 承诺方案是一个加密协议，用于在不泄露信息的情况下对某个秘密消息进行承诺。它的结构由三个主要组件组成，通常用元组表示：f = (Setup, Commit, Open)。
2. 它保护秘密信息的安全性,也保证消息的完整性和不可否认性。
3. Pedersen 承诺是一个在消息空间 Wq 上具有绑定性和隐藏性的承诺方案
4. 单变量多项式承诺方案是针对消息空间 F <= d x 的一种承诺方案

### 2024.08.03

- 学习主题：承诺方案
- 学习内容小结：
1. 学习承诺方案的各种常见实现

### 2024.08.04

- 学习主题：算术化
- 学习内容小结：
1. 定义：算术化是将计算编码为代数约束来满足问题的过程。
2. 作用：将线性问题妆花为代数问题，以减少检查次数。

### 2024.08.05

- 学习主题：算术化的各种常见实现
- 学习内容小结：
1. R1CS -> QAP，可以将计算问题转为单个多项式恒等式。
2. QAP 是一个二次算术程序，由一个基础多项式与一个目标多项式组成。

### 2024.08.06

- 学习主题：Plonk 算术化原理
- 学习内容小结：
1. 首先通过 Plonkish 将输入输出约束关系转化为 Plonk 能接受的约束表达式。
2. 然后将约束关系通过向量化的等式表示。
3. 再通过多项式编码将各约束式压缩为单个多项式等式的约束关系。
4. 最后使用多项式承诺来验证约束式。

### 2024.08.07

- 学习主题：Plonk 核心实现 [](https://github1s.com/dusk-network/plonk)
- 学习内容小结：
1. 研究 Plonk 代码实现

### 2024.08.08

- 学习主题：Plonk 核心实现 [](https://github1s.com/dusk-network/plonk)
- 学习内容小结：
1. 研究 Plonk 代码实现

### 2024.08.09

- 学习主题：Plonk 核心实现 [](https://github1s.com/dusk-network/plonk)
- 学习内容小结：
1. 研究 Plonk 代码实现
<!-- Content_END -->
