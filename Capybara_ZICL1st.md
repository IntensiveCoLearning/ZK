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
	hi 我是Capybara,一个web开发从业者,主要做前端
2. 你认为你会完成本次残酷学习吗？
	大概率能
3. 目前阶段对于 ZK 的了解？
	懂相关概念，看过相关的zk的学习视频

## Notes

<!-- Content_START -->

### 2024.07.29

举例示范：

- 学习主题：初步了解什么是ZKP（零知识证明）
- 学习内容小结：
  第一个视频通过，一个教授分别对应不同阶段的人。进行讲解和引导他们去按照自己的方式去理解零知识证明这个概念。
  零知识证明：我的理解就是一个拥有某项知识技能的人，他不想把这项知识技能泄漏出去。但是同时又要让别人知道活着相信他确实是拥有这项知识技能的一个过程。但是这个过程中最重要的三点。即，A某拥有知识、B某能够在和A某交互的过程中证明他确实拥有该知识、A某不能在交互的过程中泄露知识（也不能在交互的过程中透露的信息，能让B某推断出该知识技能）
  第二个视频主要是不两位博客主播在讲述他们对于零知识的理解，及其应用。
  在这个博客中，我了解到现实的生活中，其实还是有很多地方是可以用得上零知识证明这个算法的。比如在资产认证环节，只针对机构要求的数据进行部分公开，其余的进行加密。然后通过零知识证明的手段达到说服别人这些数据确实为我所有。还有个人病例等等。其中，最让人清晰的理解的就是阿里巴巴和四十大盗的故事让人觉得一下子就醍醐灌顶。

### 2024.07.30

- 学习主题：初探零知识证明系列之一、二
- 学习内容小结：
  此处分两节：
  第一节：【零知识】于【证明】
  本节，主要都在讲述证明的前世今生。从古希腊到 证明 == 洞见，到二十世纪初的 证明 == 符号推理，再到六十年代的 证明 == 程序，后来八十年代的 证明 == 交互。这个过程中也逐渐从知识性证明慢慢的再向零知识证明发展。
  交互证明是一个很重要的证明方式，但是在这个过程中只要，拥有知识的一方在不透露知识的情况下，能够让另外一方（验证者）相信我们就是拥有这一项知识。此处，也引申出零知识证明在币圈的部分应用（应该来说也是比较成功的尝试）。同时，作者还通过三色地图的案例，讲解了整个交互证明过程中的零知识。即，零知识证明。
  而且文章也提到了，模拟的概念，引申出一个平行世界的概念来帮忙理解模拟的概念。从三色地图的交互证明的过程中，我明白Alice拥有某项知识，但是不想让BOB知道但是与此同时又要让BOB相信Alice确实是有这项知识的。那么就是Alice在BOB随机抽取不同边的情况下，总是能让BOB相信结果是正确的。根据概率统计学的计算，随着交互的次数的变多。Alice答对的次数乳沟越多甚至是不错，那么说明Alice拥有某项知识的概率就越大。相反，那么说明Alice并不具有该项知识。因为他的结果无法让BOB相信他具体有该项知识。
  第二节：【模拟】
  本节，延续上一节中的模拟的概念，进一步的说明模拟在零知识证明中的重要性，
  本节，还是用到了上一节的三色地图的例子。但是这次却采用了模拟的形式来说明这个问题。首先假设在平行的世界中有一个对应的Zlice（并不拥有知识，对应现实世界的Alice）和一个我（对应现实世界的我完全诚实的）。同样的证明过程在现实世界和平行世界中，如果两个我都被说服，而且是在经过N轮挑战之后得出结论。经过这个过程我们大致可以确实这个证明过程是零知识的。因为平行世界中的zlice是不具备知识的。同时真的Alice也并没有透露任何真实的信息。那么在平行世界中和你对话的zlice我们可以认为他是一个模拟器。同时文章还指出模拟器具备一个超能力。就是在验证者确定好条件的某一个时刻。立马回退到这一时刻之前讲答案进行“预制”好并提供给验证者。
  最后作者引用两者故事，分别来说明了零知识证明与模拟的关系。
这两篇文章确实很好的也很详尽的描述了零知识证明这个概念，也从不同角度展示了零知识证明。用不同的例子帮助我更好的理解了零知识证明。确实获益匪浅。

### 2024.07.31

- 学习主题：ZKP Lecture 1: Introduction and History of ZKP
- 学习内容小结：
  关于伯克利的零知识证明的介绍和历史。视频是从几个实例入手，慢慢展开讲解了零知识证明的发展。视频中更多的是在用数学和概率的方式讲解零知识证明。并在这个过程中给零知识证明下了定义。和之前的文章一样，此视频也是着重在讲解零知识证明的发展。视频了用大篇幅的内容提及了，交互式零知识证明。就是证明者和验证者之间进行一些必要的交互，从而让验证者能证明或者大概率的相信证明者确实具备某种知识。前提是证明者并没有实际的向验证者透露该知识。视频里面涉及了很多概率的数学知识。感觉更多的是在从概率的看角度在说明零知识证明这件事。但是，该视频感觉专业性太强，数学符号太多。看的有点懵懵的，加上语速还是比较快的所以学起来压力还是比较大。
  不过，从这个视频里面看到了不同的人从不同的角度对零知识证明这件事进行了说明。确实也让我个人对于零知识证明这个东西的理解有所加深。同时视频里也列举了一些零知识证明应用的途径。确实这些场景或者相似的场景引入了零知识证明确实可以给人门带来不一样的安全感。从这里也可以在生活中更多的去尝试着去发现或者发掘零知识证明的可用之处。


### 2024.08.01

- 学习主题：寻找「知识」
- 学习内容小结：
  该文章的理解难度，相较于前两篇大了不少。明显感觉读起来没有像之前一样那么轻松了。言归正传，文中始终贯穿的就是一个事情。那就是针对零知识和可靠性的证明。首先是引入有限域的椭圆曲线，将一些关键信息进行映射，然后达到一定的保密性。从某种程度上来说是为了证明的交互过程中零知识。同时在这个过程中进一步推广，再次的把模拟的概念引入。讨论了现实世界和理想世界的的证明交互。首先理想世界的证明者实际上并不具有知识（即文中的私钥），但是它具备某种超能力（具有时间回溯的能力），可以提前置换掉验证者的随机数。这样一来实际上验证者得到的两个随机数都是证明者给出的。由于验证公式是固定的那么很简单结果基本可以毫无悬念的保障验证通过。这一趴就证明了可靠性（即验证者的可靠）。又进一步在理想的世界中保证证明者世俱杯知识的那么这次由验证者具备超能力（具有时间回溯的能力），此时验证者实际上就有了一个抽取者的角色帮助他去做知识抽取的动作。当经过一次验证之后，验证者立马将时间切换回做完验证的前一刻，再一次发送随机数进行再次验证得出结果。那么抽取者就可以根据前后两次的验证过程和验证结果推算出知识（即文中的私钥）。
  另外，文章还介绍了集中加密算法。以及sony的在加密算法的一次重大的生成漏洞。文章还延伸出，我们所处的现实世界，有可能是外部环境构造的一个理想世界。其实我们生活的世界也有可能是一个由外部吃程序员模拟出来的一个算法世界即理想世界。

### 2024.08.02

- 学习主题：随机「挑战」
- 学习内容小结：
  文章主要讨论了，从交互式证明到非交互式证明的挑战。确实如果一旦实现非交互式证明那么就可以完全不用考虑交互过程中带来的知识泄漏问题。确实是一个很大的挑战。
  同时交互式证明一次也就能保证一个验证者确信。但是非交互式证明则能做到同时让多方确信，而且可以一直去验证。直接做到了跨越时间和空间的限制。
  但是非交互式证明，会引入一个问题那就是可靠性问题。因为交互式证明的时候，证明者和验证者之间的交互就死活一个可靠性的体现。但是非交互式恰恰缺少了这一步骤，这就给可靠性带来了很大的挑战。非交互式证明相当于是讲多步证明简化为一步证明。为了解决这个问题又一次搬出来了模拟，也就是现实世界和理想世界。非交互式证明的理想世界中的模拟器和抽取器缺少了时间回溯的，也就是我们前面说的理想世界中的超能力。没有了超能力那就没办法达到预期的效果。但是人是很聪明的，总能想到解决办法。那么我们会引入一个第三方，✍️明明说不引入第三方的啊。况且怎么保证第三方的可信了，这个不是我该想的😂。但是为了保证超能力所以我们会分别由模拟器和抽取器来劫持这个可信第三方来达到预期的结果。这里只能感叹数学、秘密学真的太深奥了、太难了、也很吸引人。

### 2024.08.03

- 学习主题：埋藏「秘密」
- 学习内容小结：
  数句实话这篇文章难度对我而言难度比较大了，理解起来比较吃力啊。但是还是作者是分了五篇文章来循序渐进式的在讲这一个东西。要不然我觉得我早就放弃了。
  这篇文章主要在讲非交互式证明。同时为了让非交互式证明能让大家都能认可起其，可靠性、完备性、零知识性在做出讨论。文章用了一个哈密尔顿环路的问题在对于零知识证明的东西进行讲解。首先一个公共输入的地图G，然后证明者先对图G进行置换得到G'。然后给予G'构造一个哈密尔顿环路子图C，然后对于C的每一个单元进行加密之后的C'提交给验证者。然后由验证者提出挑战（此处是一个随机数（0，1））。当验证者提出的挑战随机数为0时，那么证明者就将C'对应的哈密尔顿环路矩阵公布给验证者。以供其进行验证。当验证者提出的挑战随机数为1时，那么证明者只需要将C'对应的0区域开放给验证者，以供其进行验证。此时有一个很重要的知识点即，***当图C为图G的子图时（C <= G）,那么图G的补图一定为图C补图的子图（!G <= !C）.***
  该篇文章对于零知识证明的探讨确实比较深刻，涉及很多数学知识。需要多多补充相关的知识技能。


<!-- Content_END -->
