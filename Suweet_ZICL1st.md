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

# {Suweet}
1. 一名北邮研究生，对web3感兴趣，想在技术层面有所深入
2. 51%会，49%不会
3. 稍有听闻，具体不详

## Notes

<!-- Content_START -->

### 2024.07.29

- 学习主题：初步理解ZK

- 学习内容小结：

  视频源：[Computer Scientist Explains One Concept in 5 Levels of Difficulty | WIRED](https://www.youtube.com/watch?v=fOGdb1CTu5c)

  Q：视频讲了什么内容？

  A：UCLA（加州大学洛杉矶分校）的计算机科学教授Amit Sahai向五类人群介绍零知识证明ZKP（zero-knowledge proofs），分别是小孩、青少年、大学生、研究生和专家，针对各类人群的理解能力水平各自去解释ZKP和提供案例理解。

  1. 小孩

     存在证明者和验证者两类人，证明者要让验证者相信他知道某些信息但却不透露这些信息给验证者。

     一幅画里有一群企鹅，其中有一只假企鹅，我知道它在哪，但我不告诉你它在哪，我只让你相信我知道它在哪。

     那我该怎么去证明呢？我拿一块有一小洞的不透明板子遮住这幅画，从留出的一个小洞里把那只企鹅露出来，你自然就确定我知道它在哪了，但是你还是不知道它在画里的哪个位置。

     所以ZKP有什么用呢？绝不仅仅是找企鹅，比如你如果使用密码登录电脑，那黑客黑进你的电脑就能拿到你的密码，但如果使用ZKP，你向电脑证明了你是你，但却没有透露密码，那黑客黑进去后也拿不到你的密码。

  2. 青少年

     一个实际案例，有一个被锁上的信箱（可塞纸条进去），要向人证明我知道这个箱子的密码，而不向人透露出密码。那就让那个人写一个只有他知道的信息到纸上并塞进箱里，我只要把那个信息告诉他，那就说明我能够打开箱子，也就是我知道箱子的密码。

     在计算机里的应用就比如非对称密钥，你把一个段信息用一个公钥加密并将密文发给我，我要是能够解开密文把被加密的信息是什么告诉你，那就说明我知道这个公钥对应的私钥。这是一种交互式的ZKP，这是吗？

     非对称密钥的加解密过程从证明私钥由某人拥有的角度来看，我觉得应该就是一种ZKP，但二者不对等，非对称密钥算法和零知识证明算法是两类技术，要解决的目标不同，前者主要为了确保信息的机密性和完整性，后者则是为了证明某种知识的存在而不透露具体信息。

  3. 大学生

     NP完全问题（NP-C问题），Non-deterministic Polynomial Compete Problem，是一类很难计算的问题看，还没有高效的算法式的解决方法。只要解决一类NP-C问题的其中一个，就可以解决这类NP-C问题的其他所有问题。

     教授说，“向别人证明我有0.2BTC但不透露我的地址”和“我知道三色问题（三色图里任两邻国颜色不同）的解，但我不告诉你”都是一类NP-C问题，所以以后者来解释。

     把三色问题各国颜色隐藏，任选两邻国然后把它们颜色暴露给你看，如果不同那就有一定程度信我知道这个解，但肯定也不完全信，需要不断地再选再检查。但是，这样检查下去，你就知道全部邻国颜色了，所以打乱后再给你检查，一遍一遍下去，你就越来越相信了。

     好像我的理解有误，重新想一下，会不会是这样。因为我知道三色问题的解法，我可以得出不同的但是符合要求的解，这样我就能够算出新的不同的解，然后暴露你指定的两个邻国颜色给你去验证，你每次都验证通过了，但这些解又无法让你推理出整幅图的某一个着色解法。

     另外一个应用案例是选举，选举中投票人的每一票都要被计数，又不暴露投票人信息，并且可以确定这一票被算进去。

  4. 研究生

     

  5. 专家

  

  Q：ZKP到底是什么？有什么特性？

  A：

  Q：ZKP目前发展情况？有什么实际应用？

  A：

  Q：在区块链领域中ZKP在哪些项目中落地？效果反响如何？

  A：

  Q：ZKP有哪些挑战和问题？

  A：

### 2024.07.30

<!-- Content_END -->
