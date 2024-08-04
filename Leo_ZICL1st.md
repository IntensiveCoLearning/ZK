---
timezone: Pacific/Auckland
---

timezone: Asia/Shanghai

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

# Leo
1. 自我介绍
    
    在Web3领域有丰富的设计开发经验，想继续充实ZK相关的知识

2. 你认为你会完成本次残酷学习吗？

    会

3. 目前阶段对于 ZK 的了解？

    基本入门，做过一些ZK应用方面的项目

## Notes

<!-- Content_START -->

### 2024.07.29

学习主题：观看初步理解 ZK 是什么

学习内容小结：零知识证明是一种密码学技术，它允许一方（证明者）向另一方（验证者）证明一个声明是真的，而无需透露任何额外的信息。 简单来说，它就像是一个魔术表演：证明者有一个秘密，比如一个数学问题的答案。他可以让验证者相信他确实知道答案，但不透露答案本身。验证者通过一些互动来确信证明者知道答案，而不获得任何关于答案的细节。

零知识证明有三个主要特点：

- 完整性：如果声明是真的，诚实的证明者可以让验证者相信这一点。
- 可靠性：如果声明是假的，验证者不会被说服。
- 零知识：如果声明是真的，验证者只会知道这一点，不会得到任何其他信息。

这种技术在很多领域都很有用，比如增强区块链的隐私性和安全性。

### 2024.07.30

学习主题：收听 [零知识证明：一场”无知“的游戏]

学习内容小结：对于零知识证明的应用场景有了更近一步的认识

### 2024.07.31

学习主题：学习什么是 zk-SNARK

学习内容小结：zk-SNARK 是 “零知识简洁非交互式知识论证”的缩写（Zero-Knowledge Succinct Non-Interactive Argument of Knowledge）。它是一种密码学技术，允许一方（证明者）向另一方（验证者）证明某个陈述是真实的，同时不泄露关于该陈述的任何其他信息。

zk-SNARK 的核心特性包括：

- 零知识：证明者能够证明其拥有某种信息，而不泄露该信息的内容。

- 简洁性：证明是简洁的，并且验证速度快，不依赖于证明者提供的信息量。

- 非交互式：不需要多次往返的通信。证明者可以生成一次性证明，验证者可以独立验证。

zk-SNARK 广泛应用于区块链和加密货币领域，以增强交易的隐私性和安全性。一个典型的例子是 Zcash，它使用 zk-SNARK 技术来实现隐私保护的交易。

### 2024.08.01

学习主题：学习什么是 zk-STARK

学习内容小结：zk-STARK 是“零知识可扩展透明知识论证”的缩写（Zero-Knowledge Scalable Transparent Argument of Knowledge）。它是 zk-SNARK 的一种改进，具有一些不同的特点和优势：

- 零知识：与 zk-SNARK 一样，zk-STARK 也允许证明者证明其拥有某种信息而不泄露该信息的内容。

- 可扩展性：zk-STARK 设计用于处理大量数据和计算，使其在处理复杂证明时更高效。

- 透明性：zk-STARK 不需要可信设置（trusted setup），这意味着它不依赖于初始设置的秘密参数，降低了安全性风险。

- 抗量子计算攻击：zk-STARK 基于哈希函数的安全性，被认为对量子计算攻击具有更好的抵抗能力。

- 非交互式：类似于 zk-SNARK，zk-STARK 也是非交互式的，允许证明者生成一次性证明，验证者可以独立验证。

zk-STARK 通过解决 zk-SNARK 的一些局限性，特别是在透明性和可扩展性方面的优势，成为一种在区块链和加密货币领域非常有前景的技术。

### 2024.08.02

学习主题：总结 zk-SNARK 证明系统 

学习内容小结：zk-SNARK（零知识简洁非交互式知识论证）是一类证明系统，具有多个不同的实现方式和协议。以下是一些常见的 zk-SNARK 证明系统：

1. Groth16

Groth16 是一种非常高效的 zk-SNARK 方案，其特点是生成的证明非常小，验证也非常快速。
它需要可信设置，但在性能方面表现出色，因此被广泛用于实际应用中。

2. Pinocchio

Pinocchio 是 zk-SNARK 技术的一个早期实现，强调通过结合新颖的工程和算法来优化验证器的性能。
这是第一个实用的 zk-SNARK 实现，启发了后续许多 zk-SNARK 方案的开发。

3. PLONK：

PLONK（Permutations over Lagrange-bases for Oecumenical Noninteractive arguments of Knowledge）是一种通用且可升级的 zk-SNARK 方案。
它改进了可信设置的需求，仅需要一次性的通用设置，而不需要为每个电路重新设置。

4. Marlin：

Marlin 是一个通用的 zk-SNARK 方案，旨在实现较高的证明生成和验证效率。
它的设置阶段非常高效，并支持更复杂的电路和大规模数据处理。

5. Sonic：

Sonic 是一种优化的 zk-SNARK 方案，支持批量验证多个证明，并可以通过一次性设置处理多种电路。
它增强了协议的灵活性和可扩展性。

6. Groth-Maller：

这是对 Groth16 的进一步优化，旨在减小验证密钥的大小并提升验证效率。
它仍然依赖于可信设置，但在效率上有显著改进。
每种 zk-SNARK 方案在性能、可信设置、证明大小、验证效率等方面各有优势和不足。选择哪种方案通常取决于具体应用的需求、性能要求以及安全考虑。

### 2024.08.03

学习主题：学习什么是 R1CS

学习内容小结：R1CS（Rank-1 Constraint System）是一种特定类型的约束系统，广泛应用于构建零知识证明，特别是在 zk-SNARKs（零知识简洁非交互式知识论证）中。R1CS 提供了一种表达计算问题的灵活而高效的方法，允许将问题转化为一组多项式约束。

R1CS 是 zk-SNARKs 中的核心组件，因为它可以将任意计算问题表示为一组约束。通过对这些约束进行适当的处理，可以生成一个证明，证明某个特定的输入满足这些约束，而无需泄露任何关于输入或计算过程的信息。

R1CS 提供了一种强大而灵活的框架，支持复杂计算问题的安全证明和验证，是现代密码学中不可或缺的工具之一。

### 2024.08.04

学习主题：学习什么是 Plonkish Arithmetization

学习内容小结：

<!-- Content_END -->
