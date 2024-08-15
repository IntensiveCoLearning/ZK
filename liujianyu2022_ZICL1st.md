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

# liujianyu2022
1. 一个练习时长两年半的前端开发者，通过自学，目前已掌握区块链相关的理论知识；掌握了solidity、ethersjs、hardhat等web3开发的常用技术栈。
2. 会完成本次学习。
3. 只知道一些zk的概念，了解一些简单的算术电路

## Notes

<!-- Content_START -->

### 2024.07.29
1. finite field  有限域

The finite field is the foundation of cryptography, and the motivation behind of that is because of precision problems. 
In order to solve the precision problem, a new numbers system had been designed, and there are some objectives:
1st: it will only use "whole number", such as 0, 1, 2, 3, ...;
2nd: only a limited number of the "whole number", which means that it's a finite set.
3rd：All arithmetic operations, like addition, subtraction, multiplication, division, exponentiation and logarithm, that can do with real number sould be defined with new number system.



- 学习主题：有限域
- 学习内容小结：为什么需要提出有限域这个概念，以及有限域的一些特性

### 2024.07.30
离散对数
离散对数（Discrete Logarithm）是数论和密码学中的一个重要概念。简单来说，离散对数是以下问题的解：

给定一个素数 p 和一个整数 g 以及 g 的一个幂次 g ^ x = h mod p。
找到整数 x。这个整数 x 就是离散对数。

对于实数域中的指数方程，形如：a ^ x = b，对于给定了a和b，求解x可以使用类似于二分法的思想，因为指数函数在实数域中是单调函数。

当把实数域转到有限域，并且对指数运算的结果取模运算之后，可以看到此时图中的点是无规律的分布的。那么此时给定了a和b，再想计算x就只能暴力枚举了。

![image](https://github.com/user-attachments/assets/1329c65b-72b7-475e-940b-b69c7527401c)

离散对数问题的结论：在有限域内解对数非常困难。
解决离散对数问题是一个已知的困难问题，这也是这些密码学算法安全性的基础。


### 2024.07.31
circom的初次尝试。
安装相关依赖       npm install --save circom snarkjs

// 1. all the inputs are the signals;
// 2. every time you multiply two signals together, you have to define a new signal;
// 3. only two signals can be multiplied at once
// 4. all the outputs are the signals

//  =   用于定义常量或固定值的信号。                
//          signal x = 10;                              x 是一个信号，它的值被固定为 10
//          component poseidon = Poseidon(1);           实例化 Poseidon 哈希函数组件

// <==  赋值运算符。用于将右侧表达式的值赋给左侧信号。
//          signal x;
//          signal y;
//          y <== x + 1;                                将 x + 1 的值赋给 y

// ===  约束运算符。用于表示电路中的约束，要求两边的值相等。

// <--  输入运算符。用于表示电路的外部输入信号。
//          signal input x <-- 10;                      x 是一个输入信号，值由外部输入，这里设定为 10（在实际应用中，这个值是由调用电路的外部系统提供的）

// f(x, y) = x^2 * y + x * y^2 + 17

template F(){
    signal input x;         // 2
    signal input y;         // 3
    signal output o;

    signal m1 <== x * x;    // 4
    signal m2 <== m1 * y;   // 12

    signal m3 <== y * y;    // 9
    signal m4 <== m3 * x;   // 18

    o <== m2 + m4 + 17; 
}

component main = F();



// compile     npx circom circuit.circom --r1cs --wasm --sym
// run         npx snarkjs wtns calculate circuit.wasm input.json witness.wtns
//             npx snarkjs wtns export json witness.wtns witness.json


下面是一个简单的 mimc5 加密算法：

template MiMC5(){
    signal input x;         // 输入的明文或初始值
    signal input k;         // 密钥
    signal output h;        // 输出的哈希值

    var rounds = 10;                                        // 总共进行 10 轮加密操作
    var c[rounds] = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9];         // 

    signal lastOutput[rounds + 1];                          // 存储每一轮的中间输出值
    var base[rounds];                                       // 每一轮的基数，即当前值加上 密钥k 和 轮常数c[i] 的结果
    signal base2[rounds];                                   // 每一轮基数的平方值
    signal base4[rounds];                                   // 每一轮基数的四次方值

    lastOutput[0] <== x;

    for(var i = 0; i < rounds; i++){
        base[i] = lastOutput[i] + k + c[i];                 // 当前轮的基数 base，即 前一轮的输出值 加上 密钥 和 轮常数
        base2[i] <== base[i] * base[i];
        base4[i] <== base2[i] * base2[i];

        lastOutput[i + 1] <== base4[i] * base[i];           // 5th power
    }

    h <== lastOutput[rounds] + k;                           // 最后一轮的输出值加上密钥，得到最终的哈希值 h
}


component main = MiMC5()


// compile     npx circom .\circuit.circom --r1cs --wasm
// run         npx snarkjs wtns calculate circuit.wasm input.json witness.wtns
//             npx snarkjs wtns export json witness.wtns output.json


- 学习主题：circom
- 学习内容小结：circom目前还是比较low level的层次，没有太多的语法糖。需要注意：=  <==  ===  <-- 运算符的使用

### 2024.08.02
有限域的一些特性
在数学和密码学中，Zp表示整数Z模p的有限域 ，其中p 是一个素数。这个有限域包含 p 个元素，分别是 {0,1,2,…,p−1}，并且这些元素在模 p 意义下进行加法和乘法运算。
对于任何素数 p，有限域 Zp 都满足加法逆元、乘法逆元和闭合性的性质。这是有限域（也称为伽罗瓦域，Galois Field）的一般特性。

Zp的性质：
加法和乘法：在 Zp 中，所有的加法和乘法运算都是模 p 进行的。例如， 
对于 a,b ∈ Zp
a+b ≡ (a+b) mod p
a⋅b ≡ (a⋅b) mod p

加法逆元：
对于每个元素 a,b ∈ Zp，存在一个加法逆元 −a∈Zp，使得 a+(−a) ≡ 0 mod p。

乘法逆元：对于每个非零元素 a ∈Zp，存在一个乘法逆元 a^-1 ，使得 a⋅a^−1 ≡ 1 mod p。

闭合性：加法和乘法运算在 Zp 中是闭合的，即任何两个元素的加法或乘法结果仍然在 Zp 中

举例：设 p=7，则 Z7 = {0,1,2,3,4,5,6}。

加法逆元：
0 的加法逆元是 0     0 + 0 ≡ 0 mod 7

1 的加法逆元是 6     1 + 6 ≡ 7 ≡ 0 mod 7

2 的加法逆元是 5     2 + 5 ≡ 7 ≡ 0 mod 7

3 的加法逆元是 4     3 + 4 ≡ 7 ≡ 0 mod 7

...

乘法逆元
1 的乘法逆元是 1     1 ⋅ 1 ≡ 1 mod 7

2 的乘法逆元是 4     2 ⋅ 4 ≡ 8 ≡ 1 mod 7

3 的乘法逆元是 5     3 ⋅ 5 ≡ 15 ≡ 1 mod 7

...

可以看到a的加法逆元是 p - a
a的乘法逆元可以采用扩展欧几里得算法


### 2024.08.04
kzg承诺方案
假设我们使用一个椭圆曲线 E 上的有限域 Fp，以及一个双线性配对 𝑒: 𝐺1 × 𝐺2 → 𝐺𝑇，其中 𝐺1 、 𝐺2 、 𝐺𝑇 是三个循环群，且生成元为 𝑔1 ∈ 𝐺1，g2 ∈ G2
​具体步骤如下：

![dbf23c96ef57446314e9525b00aa650](https://github.com/user-attachments/assets/00fec876-3fde-4e76-9978-a1ce40cf5543)


### 2024.08.05
双线性映射的相关特性：
e(g1^a, g2^b) = e(g1^a*b, g2) = e(g1, g2^a*b) = e(g1, g2)^a*b
e(g1, g2)^a * e(g1, g2)^b = e(g1, g2)^(a+b) = e(g1^(a+b), g2) = e(g1, g2^(a+b))


### 2024.08.06
kzg的证明步骤：

![78147a9f9aa4bde646aa02db2963146](https://github.com/user-attachments/assets/2ff2440d-2f5a-4885-86f6-fc2d78af34a0)


### 2024.08.08
今天学习内容为R1CS转为QAP
P(X) = L(X) * R(X) - O(X)


### 2024.08.09
椭圆曲线 y^2 = x^3 + a*x + b，生成元G(x0, y0)
那么椭圆曲线在G点的切线斜率为 k = (3*x^2 + a) / (2*y)
如果 2G = (x1, y1)
那么 x1 = k^2 - 2x0
     y1 = k(x0 -x1) - y0

一般的，椭圆曲线上两个点 P(x0, y0)、Q(x1, y1)，满足 R(x2, y2) = P + Q
那么 k = (y2 - y1) / (x2 - x1)
x2 = k^2 - x0 - x1
y2 = k(x0 - x2) - y0

### 2024.08.10
今天的学习内容：
复习有限域、椭圆曲线相关的内容

### 2024.08.13
今天学习内容：
复习承诺方案，包括kzg承诺方案的证明

### 2024.08.14
今天学习内容：
复习circom代码

### 2024.08.15
今天学习内容：
编写简单的circom代码


<!-- Content_END -->
