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

# spn
1. 自我介绍
XDU大四学生，ZK在学。
1. 你认为你会完成本次残酷学习吗？
会
1. 目前阶段对于 ZK 的了解？
会一些基础部分，希望巩固并继续深入学习。
## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：学习了plonk多项式  
- 学习内容小结：之前有一些基础，今天接着看了安比实验室对应的[课程](https://www.youtube.com/watch?v=bNGac1CJEKM)与[资料](https://github.com/sec-bit/learning-zkp/blob/master/plonk-intro-notebook-zh/2-plonk-lagrange-basis.ipynb),想趁着这次活动将这个系列的课程接着看完，

### 2024.07.30
- 学习主题：学习了plonk中置换证明
- 学习内容小结：接着看了上面课程的第四周以及对应的文章，感觉基础知识这块有很多还不太清楚的点，这两天计划补一下写个笔记
  
### 2024.07.31

- 学习主题：将plonk的前置知识复习了一下
- 学习内容小结:照着学长的[文章](https://snowolf0620.xyz/index.php/zkp/769.html)巩固了一下前置知识

### 2024.08.01

- 学习主题：对plonk协议的核心学习
- 学习内容小结:	1.电路转换：将计算问题表示为一个电路，该电路由一系列门和连线组成。然后，将这些门和连线转换为多项式表示。
	          2.多项式承诺：证明者对电路的多项式表示进行承诺，并生成相应的承诺值。
	          3.生成证明：证明者使用置换证明和多项式承诺生成一个非交互式的零知识证明（通过 Fiat-Shamir 启发式方法将交互式证明转化为非交互式）。
	          4.验证证明：验证者使用证明和多项式承诺值来验证证明的正确性，而无需了解具体计算内容。
            另注：对具体round中的细节还不是很理解得透，接下来还得多看看
            
### 2024.08.02

- 学习主题：plonk等式验证
- 学习内容小结:将plonk遗留的几个等式照着推导验证了一下（安全归约太重要了）

### 2024.08.03

- 学习主题：cairo学习
- 学习内容小结:参考[WTF-cairo](https://github.com/WTFAcademy/WTF-Cairo)学习了一下前14讲

### 2024.08.04

- 学习主题：lookup查询学习
- 学习内容小结:[课程](https://www.youtube.com/watch?v=pmO6p9Q-x6g)与[文章](https://snowolf0620.xyz/index.php/zkp/919.html)感觉推导的时候看图确实比较清晰一点

### 2024.08.05

- 学习主题：cairo学习+
- 学习内容小结:将WTF-cairo的15-28讲速通了一下（基于rust写起来确实顺手不少）
  
### 2024.08.06

- 学习主题：plookup学习
- 学习内容小结:[课程](https://www.youtube.com/watch?v=I6asKtO8Q8E)(向量细节好复杂记不清楚😭)
  
### 2024.08.07

- 学习主题：plonk源码学习
- 学习内容小结:查了下github上star多的plonk协议，进行了一个源码的读（x

### 2024.08.08

- 学习主题：plookup源码学习
- 学习内容小结:根据GitHub的plookup协议进行复现，今天写了KZG10和TranscriptProtocol部分

### 2024.08.09

- 学习主题：plookup源码学习2
- 学习内容小结:看并复现了lookuptable部分，希望能尽自己力再改改（
  
### 2024.08.10

- 学习主题：plookup代码研究和snark学习
- 学习内容小结:自己尝试对plookup代码细节进行理解并进行接口对接，将之前的zksnark接着看了看
  
### 2024.08.11

- 学习主题：snark学习
- 学习内容小结:将这部分[文章](https://learn.z2o-k7e.world/zk-snarks/toc.html)全过了一遍，将知识理了一下（感觉现在自己处于一种似懂非懂的状态？->不能提出有创造性或者精辟的问题😭😭）
  
### 2024.08.12

- 学习主题：安全归约、安全计算、模拟器
- 学习内容小结:看了看k2ok7e下邓燚老师的[文章](https://zhuanlan.zhihu.com/p/268305208),感觉理论层面的安全归约很难弄清楚，得多多理解。（最近还要备考雅思感觉时间有点紧，尽量跟上）
- <!-- Content_END -->
