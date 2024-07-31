---
timezone: Europe/Paris # 中欧标准时间 (UTC+2)
---

# Chloe
1. 自我介绍
    Hi I'm Chloe, Core contributor of ETHPanda & EIP Fun. Passionate about zk and privacy.
    Twitter：https://x.com/Chloe_zhuX
    TG：chloe_zhu

2. 你认为你会完成本次残酷学习吗？
    Ofc

3. 目前阶段对于 ZK 的了解？
    Had some brief overview of zk landscape/ projects/ tools. Would love to dig deep into the underlying tech.


## Notes

<!-- Content_START -->

### 2024.07.29

Video: [Computer Scientist Explains One Concept in 5 Levels of Difficulty | WIRED](https://www.youtube.com/watch?v=fOGdb1CTu5c)

Notes
- zkp is a way for prover to convince the verifier that some statement is true, yet reveal no additional info beyond the fact the statement is true
- 5 levels to explain zkp
    - **Child:** The prover proves that there is a puffin within a group of penguins in the photo through a hole to the verifier, without revealing the location of the puffin.
    - **Teen:** The prover proves he know the password to a box, without revealing the exact pwd.
    - **College student:**
        - NP-complete problems: a class of computational problems where an efficient, algorithmic solution has yet to be found
        - 3-colour problem: Prove that no blocks that share the border will have same colour. Make it impossible to put the pieces together and guess the whole map.
        - A probabilistic proof
        - zkp is not about making sth more efficient, but about doing things that can’t be done before, i.e. proving things without revealing any additional info
    - **Grad student:**
        - Proof is an interactive game.
        - Randomness can be useful for proving sth. The unpredictability can be utilized to generate proof and hide info.
        - Challenge: The main bottleneck lies on the prover
        - The power of MPC is to bring people together who are mutually distrustful
    - **Expert:**
        - Why zero-knowledge, not zero-data or zero-info; nuance between knowledge, data, and info
        - Transition from theoretical to applied zk

MoonMath
- Installed SageMath
    - /usr/local/bin/sage
    - [https://www.sagemath.org/index.html](https://www.sagemath.org/index.html)
    - SageMath is a free open-source mathematics software system licensed under the GPL. It builds on top of many existing open-source packages: NumPy, SciPy, matplotlib, Sympy, Maxima, GAP, FLINT, R and many more. Access their combined power through a common, Python-based language or directly via interfaces or wrappers.
- Walked through Chapter 1 intro

### 2024.07.30

- 播客：DAOrayaki 对话姚翔，zkp 的前世今生 [https://www.xiaoyuzhoufm.com/episode/62fc7ad931313a22da88ecfd](https://www.xiaoyuzhoufm.com/episode/62fc7ad931313a22da88ecfd)
- Notes
    - 两个问题
        - 什么样的问题需要去证明
        - 有没有可能构造出一种证明，让 prover 知道 verifier 有实际能力推演出证明过程，但 verifier 在过程中，不能学到如何去证明（或学习到如何伪造一个证明过程），i.e. 当答卷人是 prover 1，改卷人是 verifier 1，verifier 1可以确认 prover 1知道证明过程x，但是 verifier 1在验证后不能构造出一个证明（即证明过程伪x，甚至是证明过程x），让 verifier 2相信 verifier 1（此时他是 prover 2）知道如何来证明
    - 1985年发表的论文《交互式证明系统的知识复杂性》（[The Knowledge Complexity of Interactive Proof Systems](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Proof%20Systems/The_Knowledge_Complexity_Of_Interactive_Proof_Systems.pdf), by Goldwasser, Micali, Rackoff）
    - NP 问题
        - NP 问题：指多项式时间内，验证某个解是不是正确的问题。
            - 和 NP 问题对应的 P 问题，是指在多项式时间内，可以解决的问题
            - NP 问题，即求解它是困难的，但是验证解的正确性是容易的
        - 对于 verifier，在多项式时间内，可以比较简单的验证解的正确性，但没有办法在多项式时间内找出它的解（即 verifier 不知道这个知识）
    - 特殊的证明体系
        - 交互式证明系统
            - prover 和 verifier 之间有多轮交互进行验证
            - 允许有极小的误差，i.e. 有小概率 prover 可能欺骗 verifier
            - 不可区分性，密码学常用工具用于定义零知识
    - zkp 的应用
        - 与区块链的结合
            - 区块链：解决分布式网络对一个状态的共识，但关于状态的变化以及状态内容的保护做的还有欠缺
            - zkp：
                - 可以将区块链由计算驱动的 state transition，变成由验证驱动的 state transition，i.e. 状态从 s 到 s’ 不再需要全节点知道计算细节，只需要知道计算是正确的
                - 可以让节点在不知道具体状态的情况下，执行、验证状态变化的有效性，从而保护 tx 的隐私性
        - zk rollup
            - 核心点：网络中的节点不需要再计算，只需要提供一个证明，证明中包含的数据是：S到S1’这件事一定是对的，然后区块链其他什么也不用做，只需要把S变成S1‘就可以
            - 优势
                - 全节点不需要保存所有的状态数据（理想情况）
                - proof 生成的过程，可以用定型的方法，或者通过硬件和软件的优化来加速
            - 劣势
                - 通常通过 sequencer 生成证明，对 sequencer 的硬件软件设备要求很高，因此可能会存在单点故障
                - 以及额外攻击，如 mev、针对交易的审查
