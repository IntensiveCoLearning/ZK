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

- 课前学习：
    - 20min 的视频：[初步理解 ZK 是什么](https://www.youtube.com/watch?v=fOGdb1CTu5c)
    - 70min 的播客：[零知识证明：一场”无知“的游戏](https://www.xiaoyuzhoufm.com/episode/6672a76bb6a8412729e0b103)
- 第一周：7 月 29 日 - 8 月 4 日：Introduction and History of ZKP
    - 100min 的视频：[ZKP Lecture 1: Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
    - [（一）初识「零知识」与「证明」](https://learn.z2o-k7e.world/zkp-intro/1/zkp-back.html)
    - [（二）理解「模拟」](https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html)
    - [（三）寻找「知识」](https://learn.z2o-k7e.world/zkp-intro/3/zkp-pok.html)
    - [（四）随机「挑战」](https://learn.z2o-k7e.world/zkp-intro/4/zkp-rom.html)
    - [（五）埋藏「秘密」](https://learn.z2o-k7e.world/zkp-intro/5/zkp-crs.html)
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

本次共学资料前两周的 lecture 来自 [zk-learning](https://zk-learning.org/)，博客来自 [《探索零知识证明系列》](https://learn.z2o-k7e.world/zkp-intro/toc.html)和[《从零开始学习 zk-SNARK》](https://learn.z2o-k7e.world/zk-snarks/toc.html)，第三周的 Circom 部分来自 [0xparc](https://zkiap.com/)，视频讲解为 [ZK Shanghai](https://zkshanghai.xyz/) 的中文版本。学有余力者可以依此找到更多的扩展内容。

### **最后，非常感谢安比实验室郭宇老师对于本次共学资料选择的指导！**

---

# Hazel Gong
1. 自我介绍
   数学和物理专业毕业。之前在做 AI 产品。最近在学习 web3 的技术。
3. 你认为你会完成本次残酷学习吗？
   会。
5. 目前阶段对于 ZK 的了解？
   了解概念。之前学过一些数论、看过 interactive proofs 相关的论文。看完了本次 colearning week1 前几篇文章。

## Notes

<!-- Content_START -->

### 2024.07.29

学习主题：[Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)
学习内容小结：

Basic concepts: 

Interactive proofs:
- There is a prover and a verifier. Both are algorithms. The prover sends a string to the verifier. The verifier decides whether to accept or reject it. 

Efficiently verifiable proofs (NP proofs):
- Proof is short. Verifier has polynomial time to verify. 
- claim x
- short proof w: length |w| is polynomial in |x| (so |w|=|x|^a, a is a number? )
- verifier V is a function. accepts x if V(x, w)=1, else reject. V takes time polynomial in |x|.

Polynomial time: 
- a class of problems whose running time grows polynomially with the size of the input. (用来形容算法复杂度，更加复杂的算法可能会是 exponential time，更简单的算法可能会是 linear time)

NP-Language:
L is an NP-language (or NP-decision problem) if there is a poly(|x|)-time verifier V with completeness (true claims with short proofs evaluates to 1) and soundness (false claims have no proof). 

ZKP: prove that I have the knowledge without giving away the knowledge, using interactive probabilistic proof. 
- through polynomial interactions
- randomness: V is randomized, can err in accept/reject with small probability. 

Interactive proof model
- P, V know the claim x
- V is probabilistic polynomial time
- V takes in x, and all interactions between them to decide whether to accept or reject.


### 2024.07.30

学习主题：[Introduction and History of ZKP](https://www.youtube.com/watch?v=uchjTIlPzFo)

学习内容小结：

Example of an interactive proof: Claim QR = {(N,y): there exists x such that $y=x^2$ mod N}. 

P: choose random r such that $1 \leq r \leq N$ with $gcd(r,N)=1$. Send $s=r^2$ mod N. 

- If P sends square root of both s and sy mod N, then V will know the claim is true but get $\sqrt{y} = x$ mod N. 
- So P instead sends either s or sy mod N, but V chooses which one to send based on  a coin flip.
- If heads, send z=r; if tails, send z=r$\sqrt{y}$ mod N. Here, the random r masks $\sqrt{y}$.
- Then V accepts only if $z^2 = sy^b$ mod N. Since P has sent s.

To show that a proof is a zero-knowledge interactive proof of knowledge, one must show:
- completeness: if the claim is true, V accepts with probability $\geq c$ (usually it's 1). 
- soundness: if the claim is false, V accepts with probability $\leq s$ (usually it's 1/2).
- c and s are polynomial apart $c-s\geq \frac{1}{poly(|x|)}$ (notice that $\frac{1}{poly(|x|)}$ is a measure of magnitude, it's much bigger than $\frac{1}{e^{|x|}}$ for example. )
- zero-knowledge: what the verifier V can compute after the proof = what V can compute before the proof. Prove that the verifier's view can be simulated by a zero-knowledge simulator (compuationally indistinguishable from a simulated view).
- proof of knowledge: we need to make sure P really has the knowledge $x=\sqrt{y}$ given his actions (proof using an extractor who can use a rewinding technique, record the randomness, and perform both actions, then recover the knowledge of P. )

Intuitions of the proof: 
- There are many possible proofs, depending on the random r chosen by P.
- Each proof has 2 parts, seeing either gives zero knowledge, seeing both implies 100% correctness.
- Verifier chooses at random which of the two parts he wants. Verifies over and over again. The ability of the P to give him either part of the answer convinces V that P has the knowledge. But the whole process is zero-knowledge.


### 2024.07.31
学习主题： 
1. Lecture 1 最后 40min 没有完全理解，也许看一些别的材料里面的例子，再回来理解。
2. 略读 Week 1 blog article #4: https://learn.z2o-k7e.world/zkp-intro/4/zkp-rom.html#%E9%87%8D%E5%BB%BA%E4%BF%A1%E4%BB%BB--%E9%9A%8F%E6%9C%BA%E9%A2%84%E8%A8%80%E7%B2%BE%E7%81%B5

学习内容小结：
1. Every NP-decision problem has a zero-knowledge interactive proof (I skipped the proof for this). Applications.
2. Interactive ZK 可以通过多轮交互来确保 prover 作弊成功的可能性可忽略不计。随机数挑战是交互式证明的信任根基。NIZK 是单轮交互的证明。在这里面，prover 通过单向函数 hash function 生成一个难以事先预测的随机数，来代替在 interactive ZK 中 verifier 提供的随机数。



### 2024.08.03
学习主题：https://learn.z2o-k7e.world/zkp-intro/2/zkp-simu.html 博客文章第二篇

学习内容小结：用模拟来证明零知识。Prover Alice 与无知识的 Simulator Zlice 不可区分，而后者没有知识，只有超能力。这是在证明，所谓「零知识证明」确实零知识。「证明的零知识过程，等价于构造（寻找）一个「模拟」算法，这个算法能够让模拟器来模拟出一个「没有知识」的理想世界。如果这个算法存在，而且两个世界不可区分，那么就证明完毕。」
所谓模拟器不能是全能的，它是一个图灵机、模拟机，可以做到时光倒流，但不能篡改 Verifier Bob 收到的答案。
证明零知识，就是寻找一个算法，它运行在外部真实的计算系统，但却实现了零知识的模拟机的功能，因此等价于一个零知识的系统，所以它是零知识的。
模拟证明了零知识，定义了安全性。


### 2024.08.04
学习主题：Proof of Knowledge 如何证明 prover 掌握知识，Schnorr 协议

学习内容小结：
1. 证明 prover 掌握知识：在理想世界中，一个作弊者是否可以复原出 prover 的知识。
2. Schnorr 协议
- 原理：Alice 拥有一个秘密数字，a，我们可以把这个数字想象成「私钥」，然后把它「映射」到椭圆曲线群上的一个点 a*G，简写为 aG。这个点我们把它当做「公钥」。sk = a, PK = aG.
给任意一个有限域上的整数 r，我们就可以在循环群中找到一个对应的点 rG，或者用一个标量乘法来表示 r*G。但是反过来计算是很「困难」的。
也就是说，如果任意给一个椭圆曲线循环群上的点 R，那么到底是有限域中的哪一个整数对应 R，这个计算是很难的，如果有限域足够大，比如说 256bit 这么大，我们姑且可以认为这个反向计算是不可能做到的。
Schnorr 协议充分利用了有限域和循环群之间单向映射，实现了最简单的零知识证明安全协议：Alice 向 Bob 证明她拥有 PK 对应的私钥 sk。
- Protocol:
  ![image](https://github.com/user-attachments/assets/06f0b8cf-ad89-49e9-9fa6-aaf58c82c5bd)
- 此 Protocol 的关键：
  a. Bob 的随机数，保证 Alice 必须使用知识进行证明：如果我们把挑战数 c 看成是一个未知数，那么 r+a*c=z 可以看成是一个一元一次方程，其中 r 与 a 是方程系数。请注意在 c 未知的前提下，如果 r + a*x = r' + a'*x 要成立，那么根据 Schwatz-Zippel 定理[3]，极大概率上 r=r'，a=a' 都成立。也就是说， Alice 在 c 未知的前提下，想找到另一对不同的 r',a' 来计算 z 骗过 Bob 是几乎不可能的。这个随机挑战数 c 实现了r 和 a 的限制。虽然 Bob 随机选了一个数，但是由于 Alice 事先不知道，所以 Alice 不得不使用私钥 a 来计算 z。这里的关键： c 必须是个随机数。
  b. Alice 的随机数，保证 Bob 无法复原 Alice 的知识。Bob 不知道 r，但是他知道 r 映射到曲线上的点R；Bob 也不知道 a，但是他知道 a 映射到曲线群上的点 PK，即 a*G。通过同态映射与Schwatz-Zippel 定理，Bob 可以校验 z 的计算过程是否正确，从而知道 Alice 确实是通过 r 和 a 计算得出的 z，但是又不暴露 r 与 a 的值。
  
### 2024.08.07

[ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)

SNARKS are succinct non-interactive proofs. What snarks are, what they are good for, and how to construct them. 

- SNARK: the proof is short and fast to verify. 
- zk-SNARK: te proof reveals nothing about the message. 


### 2024.08.08


Blockchain applications: 
- Scale the L1 blockchain chain using the zkRollup. Off-chains service processes a batch of transactions, L1 chain verifies a succinct proof that those transactions were processed correctly. There might be thousands of transactions, so this applications scales the speed of the L1 chain, since it doesn't have to verify the transactions one by one, just verify this succinct proof that is short and fast to verify.
- private Tx on a public blockchain needs a zk proof to validate.


### 2024.08.09

zk-SNARK article 1: https://learn.z2o-k7e.world/zk-snarks/1-Polynomial-Interaction-and-Proof.html

多项式是 zk-SNARK 核心的部分。可信度几乎 100%。任何多项式在任意点的计算结果都可以看做是其唯一身份的表示（Schwatz-Zippel 定理：我们不可能找到共享连续段的两条不相等曲线，也就是任何多项式在任意点的计算结果都可以看做是其唯一身份的表示。也就是说只要能证明多项式上的某个随机点就可以证明这个多项式（只有在知道了多项式，才能算出这个点对于的值），这个性质是我们下面所有证明的核心）。

Naive 协议：
利用上述多项式的性质（任何多项式在任意点的计算结果都可以看做是其唯一身份的表示），可以用以下协议来验证 prover 有一个多项式的某些根（包含在 t(r) 里）：
- verifier 挑选一个随机值 r , 计算 t=t(r) (即，求值) ，然后将 r 发送给 prover。
- prover 计算 h(x)=p(x)/ t(x) ，并对 p(r) 和 h(r) 进行求值，将计算结果 p, h 提供给 verifier。
- verifier 验证 p=t⋅h ，如果多项式相等，就意味着 t(x) 是 p(x) 的因式。

但是此协议存在漏洞：一旦 prover 知道了 t(r) ，他就可以反过来任意构造任何一个可以整除 t(r) 的 p(r)，prover 知道了点 (r,  t(r)⋅h(r)) 的值，就可以构造经过这一点的任意(高次)多项式，同样满足校验。

强同态加密的 motivations: 
如果 verifier 给出的这个 r 值像放在黑盒里一样不可见的话就完美了，有点类似哈希函数，从计算结果就很难再回到原始值上。
所以用到强同态加密。可以选择一个基数，一个指数，加上一个模，来加密一个选定的 r 值。基数是公开的。加上模运算之后，从运算结果回到初始值不容易。


在同态加密中: $ E(v) = g^v (mod p) $ 
- 模数 p 是双方都知道的。它通常是写在加密代码中的
- 生成元 g 是一个整数，作为一个基用来生成一系列的数字(密钥，用来对数据进行加密)
- v 就是我们要加密的值


### 2024.08.10

最后的协议没有完全理解。
<img width="406" alt="Screenshot 2024-08-09 at 23 51 11" src="https://github.com/user-attachments/assets/d243a8b5-1894-4573-aaeb-f4d9e0ac470f">

### 2024.08.11

blog 2 - 5: 用 blog 1 的 proof 构建通用 zk-SNARK 的协议。没有完全理解。待梳理。

### 2024.08.14

看 [ZKP Lecture 2: Overview of Modern SNARK Constructions](https://www.youtube.com/watch?v=bGEXYpt3sj0)。


<!-- Content_END -->
