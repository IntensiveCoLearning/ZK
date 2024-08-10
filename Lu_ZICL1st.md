---
timezone: Asia/Bangkok
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

# Lu Zhiyuan 路致远
1. 自我介绍
   参与过L2的空投，也做过L2的项目方。除了赚钱外，也想从技术上对ZK有更多了解。个人说明书见 https://p1i72gf0sn.feishu.cn/wiki/WdSMwvDOeiULi5kyhO9cXT5onGc
2. 你认为你会完成本次残酷学习吗？
   会
3. 目前阶段对于 ZK 的了解？
   仅限皮毛，知道这个东西存在和有用

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：what is ZK?
- 学习内容：
1. What is ZK -> Zero-Knowledge?
lt is a proof. A prover can convince a verifier that sth is true without additiona info.
data -> info -> kowledge.
it is called kowledge, not data or info, coz it could predict the future -> 像是哲学里的先验
2. Why ZK and why it is good? 
not for efficiency, but for building more trust& keep secret.
Examples can be seen in elections, multi-partycomputation and so on.
lt uses randomness to bring ppl together. Non-interactive nature + varifiability. lt is counter-intuitive·
3. 遗留的问题:
any other proofs?
what's the diffrence btw blockchains &cryptocurrencies?
Concept of NP-complete problems & map threecoloring

### 2024.07.30

**1. zkSNARK VS zkSTARK**
1.1 zkSNARK
S: Succinct; N: Non-interactive; ARK: ARgument of Knowledge
利用：BA有保证金
不太透明

**1. zkSNARK VS zkSTARK**
1.1 zkSNARK
S: Succinct; N: Non-interactive; ARK: ARgument of Knowledge
利用：BA有保证金。缺点是不太透明
1.2 zkSTARK
S: Scalable; T: Transparent
够透明
**2. ZK Rollups VS Optimistic Rollups**
Optimistic Rollups  相信人本善
quicker transaction processing

### 2024.07.31

今天学习的内容从文字格式、文章排版和信息密度三块都好喜欢。（对里面的例子理解与否则是另外一方面）

**What is Proof, Knowledge, and Zero Knowledge**
1. What is Proof
   1.1 Greece
   Proof的对立面是反权威 -> 理性思潮崛起
   1.2 二十世纪初
   proof = 符号 -> 人们试图让「理性」有迹可循/规范化/自动化
   1.3 六十年代
   Proof = code -> 证明在计算机方面有概率被大规模运用，问题变成了「寻找Proof」和「验证proof」，后者可以交给机器辅助
   1.4 八十年代
   Proof = interactive -> 这有点像是科学实验中的可重复性，若证明成立，则这个证明在A和B那边当然得同时满足
2. Benefits of ZKP
 略
3. Info VS Knowlegde
 Info = randomness -> 用「无序」的「信息」保证「隐私」安全，以及交叉验证

### 2024.08.01

今天学的内容是四天内最抽象的。例子都很好看，但不明白为什么打这个比方。

# ZKP 2  模拟

- 计算机科学中的两个重要方法论
1）抽象；2）模拟

`为什么要选择模拟，为什么模拟在计算机科学和ZKP中都很重要？`

- 1. 安全 & 不可区分性

交互 -> 对话 -> 传递信息
想要有隐私的对话 -> 信息的传递有限 -> 安全前提`理解成隐藏前提也行？` -> 什么是安全 `1、完美安全；2、语义安全`

何为「语义安全」：假设你是一个攻击者，你通过密文在多项式时间内「计算不出来」任何有价值的信息。

计算不出来 -> 不可区分性 -> 概率学的不可区分

- 2. 如何证明一个交互式系统是「零知识」？

零知识成立 = 无法区分「模拟」出来的「理想世界」和「现实世界」 ->  依靠「算法和代码」，在「模拟」出来的「理想世界」里实现信息传递

eg1. 阿里巴巴、洞穴与芝麻开门 中电视台通过「剪辑」——「模拟」，模拟出了一个「理想世界」，实现信息传递——欺骗观众试验成功。

`零知识证明保护了知识拥有者的权益，那么知识获得者的权益又由谁来保护？`

### 2024.08.02
今天的看了一会儿没看懂，明天再继续看。

没想到交互系统（安全协议）的三个性质竟然是从prover角度出发。

### 2024.08.03
今天和昨天学习内容一致。

交互系统、安全协议的三个性质中，「完备性」和「可靠性」的定义具有「对称性」 （逆反命题？），「完备性」不言而喻，所以本文主要探讨「可靠性」和「零知识」—— 定义to know

例子：Schnorr 协议
Why这个例子：它是ZKPoD的核心技术之一（也就意味着这是实际应用场景）

Schnorr协议的几个概念：「映射」、「同态映射」、「椭圆曲线」、「循环群」、「有限域」。
- 「椭圆曲线」群「有限域」之间存在着一种「同态映射」关系  
- 「有限域」 = Zq （素数q是指有限域的大小，从0开始）  
- 在「椭圆曲线」上，通过一个基点，G，可以产生一个「循环群」，标记为 0G, G, 2G, …, (q-1)G，正好是数量为q个曲线点的集合
- 叫「循环群」，因为把群的最后一个元素 (q-1)G，再加上一个 G就回卷到群的第一个元素 0G。  
- 把q改成R，很容易在「循环群」里找到对应的RG，相反却很困难——这是个叫做「离散对数难题」的「密码学难题」  
`好吧我的脑细胞在这里烧干了，为什么相反过来很难？`  

Sony PlayStation 3的事情可以看这个链接，主要讲的是「乔治·霍兹」的故事，对方不仅破解过Sony，还破解过苹果(https://www.sohu.com/a/656641356_121648941)，也就是后文发布演讲大会的Geohot。

思考一下还是不花力气试图理解这节的例子了，明天继续推进新的章节学习。

### 2024.08.04

- Proofs -> Classical Proofs VS ZKP - proof as an interactive process, prover + verifier
- focus on verifier
- intro: 用了三个NP的例子
- New Proof Modle: interaction + randomness
看了27分钟，明天间断性再继续吧。

### 2024.08.06
开了中英文双语字幕、跳着看的。
比起最开始了解学习到的ZKP，现在我知道了ZKP的交互是多次的（多项式运算），交互性也就意味着可以通过时间倒流的手段进行「欺骗」（待确定）
NP不仅仅可以作为例子，也是被证明具有ZK的性质。
交互系统不仅仅是个证明系统，更是证明知识的系统。

### 2024.08.07
跳过视频直接继续往下推进，今天看的是「1-Polynomial-Interaction-and-Proof」。
- 结论：多项式依然是 zk-SNARK 核心的部分
- 原因 任何多项式在任意点的计算结果都可以看做是其唯一身份的表示 -> 对于一个 d 阶多项式 , prover 如果不知道该多项式的 d 个解 , 撞到x（也就是结果）的可能性极低=不可能 -> 不知道就是不知道，知道就是知道，这种情况下只需要一轮检验就可以得出结论。
- 反面例子：位数组。位数组需要逐个、多个的验证才能得出结论。

### 2024.08.08
接着昨天的课程
- 前面已知多项式因为其唯一性所以是zk-SNARK核心的部分，相反的是数位组。那么什么是多项式？
- 多项式是什么 & 多项式的「知识」= 系数 & 「知道」多项式 = 知道系数
- 多项式容易被破解 -> 如何加密？
- 同态加密的弊端 -> 模运算

### 2024.08.09
本来想进行新的课程的，看了一下新的课程是在1的基础上继续深入，那还是看1。

- 加密方式： 1. 同态加密； 2. 模运算
- 理解同态加密和同态加密的可能方式：加法、乘法
我的误区：同态加密就是把计算变得复杂了，进而解密难度就更高了。
GPT解释：同态加密的解谜过程固定。难度是受解密密钥和算法影响。
- 模运算理解三个词：模 𝑛（Modulo n）、取模（Modular Operation）、逆（Modular inverse）
- 例如，17 = 3*5+2，所以 17 Mod 5 =2。这个过程就是取模，17模5=2。模就是做除法但是结果只看余数。例如，3*b Mod 7 = 1，b=5 ，所以5是3在模7下的逆元。
- GPT说模运算中的 = 符号并不是真的等于，而是模等价。模等价意味着两边的值在除以某个数后有相同的余数。（我看了一下英文论文也是用 = 符号，但如果解释说明这个是模等于，会更友好些）

剩下一块加密函数了！看了三天总算觉着第一块内容有点摸到边。明天重新再过一遍。

### 2024.08.10
想了下ZKP还是不完全跟着课程节奏来了，基础材料多看看打基础。
尝试理解「群论」- 「如何给高中生解释群论？」「抽象代数的举例子」「结构是什么意思」
- 1. 群是抽象的，抽象往往探究的是「共性」与「本质」
`点了。和人讨论问题的时候要注意大家是在讨论抽象层面的本质还是现实层面的应用。`  
- 2. 从正方体的全部摆放动作（24种）理解群
2.1 置换群 = 对一组元素的排列或重新排序 = 正方体的全部摆放动作 = 24
 GPT提醒：并不是所有置换群都具有可迁移性，有些置换群只包含某些特定的置换。
2.2 稳定元 = 4 = 确定一个面后，正方体能旋转4次却不改变面的位置
2.3 轨道 = 1 -> 1个单一的、连续的轨道，轨道大小 = 6 = 可被移动的面 = 互换性 & 对称性
- 3. 同构 = 结构相同而名字不同，同态 = 名字相同罢了，同构是同态的一种特殊表现形式，即映射且一一对应。
 `点了。看似不同的数学对象之间其实有深层次联系。`  
<!-- Content_END -->
