# 第一章引文核验说明

本说明只对应第一章实际使用到的文献。

核验口径说明：
- “原文可核对位置”优先指论文题目与摘要（Abstract）。第一章中的多数引用承担的是研究背景、研究对象、方法框架和主要结论的综述功能，题目与摘要通常已经足以支撑这些表述。
- 如需进一步深挖细节，可直接通过 DOI 打开期刊或会议官方页面，再按题目或摘要中的关键词定位正文。
- 本说明只写已经实际出现在第一章中的文献，和 `ref_paper.bib` 保持一致。

## 1.1 研究背景及意义

- `bockelmann2016mmtc`：用于说明 mMTC 场景具有海量终端、短包和可扩展接入需求。原文可先核对题目，再看摘要中关于 5G mMTC、海量连接和可扩展接入挑战的概述。DOI：10.1109/MCOM.2016.7565189
- `yates2021survey`：用于说明 AoI 适用于网络化感知、控制与低时延状态更新系统，也用于支撑 AoI 作为系统级新鲜度指标的背景论述。原文可核对摘要中对 AoI 应用场景、评估方法与优化框架的综述性描述。DOI：10.1109/JSAC.2021.3065072
- `kaul2012real`：用于引出 AoI 的基本定义，即接收端最新信息距离生成时刻已过去多久。原文可直接核对题目与摘要中的 status update age metric 描述。DOI：10.1109/INFOCOM.2012.6195689
- `sun2017update`：用于支撑“零等待并不总能最小化 AoI”这一论断。原文可核对摘要中关于 zero-wait policy not always optimal 的结论。DOI：10.1109/TIT.2017.2735804
- `zhang2023aoi`：用于说明除了平均 AoI 之外，AoI 违规概率同样重要。原文可核对题目与摘要中关于 violation probabilities、PDF 以及多源 IoT 状态更新系统的表述。DOI：10.1109/JIOT.2023.3297617
- `berioli2016modern`：用于说明随机接入在短包、突发业务和大规模接入中的工程价值。原文可核对题目与导论摘要中关于现代随机接入协议的广泛应用背景与碰撞处理思想。DOI：10.1561/1300000047
- `bianchi2002performance`：在 1.1 中用于说明标准 CSMA 的经典解耦分析框架。原文可核对题目与摘要中对载波侦听型随机接入解析建模对象的说明。DOI：10.1109/49.840210

## 1.2 国内外研究现状

- `yates2021survey`：用于概括 AoI 研究从概念、模型到优化框架的总体演进。原文可核对摘要中的 survey scope。DOI：10.1109/JSAC.2021.3065072
- `wang2023age`：用于说明近年研究已将 AoI 推进到更具体的帧时隙 ALOHA 场景。原文可核对题目与摘要中关于四类 FSA 版本、AoI 分析和最优帧长的表述。DOI：10.1109/TCOMM.2023.3244214
- `wang2024analytical`：用于说明近年研究已推进到更实用的 802.11 类 CSMA 网络建模。原文可核对题目与摘要中关于 practical CSMA network、SHS model 与 collision probability 的描述。DOI：10.1109/INFOCOM52122.2024.10621330
- `zhang2023aoi`：用于说明近期研究开始重视违规概率与分布指标。原文可核对题目与摘要中关于 violation probabilities 和 PDF 的描述。DOI：10.1109/JIOT.2023.3297617

## 1.2.1 集中式接入机制的研究现状

- `kadota2018scheduling`：用于说明集中式 AoI 调度中，最大年龄优先在对称广播网络下可最优，并可构造随机化、最大权重和 Whittle 指数等策略。原文可核对摘要中的 symmetric network optimality 与 low-complexity policies。DOI：10.1109/TNET.2018.2873606
- `hsu2019scheduling`：用于说明随机到达、无线广播和无缓存场景下，AoI 最小化可以被表述为结构化 MDP/Whittle 指数问题。原文可核对题目与摘要中的 random arrivals、wireless broadcast 和 scheduling algorithms。DOI：10.1109/TMC.2019.2936199
- `maatouk2020optimality`：用于说明 Whittle 指数策略在特定多用户极限条件下具有全局最优性。原文可核对题目与摘要中的 global optimality of Whittle's index policy。DOI：10.1109/TIT.2021.3121257
- `bockelmann2016mmtc`：用于说明 mMTC 场景中集中式控制面临海量终端和可扩展性压力。原文可核对摘要中关于 scalable connectivity challenge 的表述。DOI：10.1109/MCOM.2016.7565189

## 1.2.2 随机接入机制的研究现状

### ALOHA 方向

- `berioli2016modern`：用于概括随机接入协议的总体工程背景和机制演化。原文可核对导论与摘要中关于 modern random access protocols 的综述性描述。DOI：10.1561/1300000047
- `chen2022randomaccess`：用于说明年龄增益（age-gain）驱动的分布式随机接入策略。原文可核对题目与摘要中关于 decentralized age-efficient transmission policies 和 age-gain threshold 的描述。DOI：10.1109/TIT.2022.3180965
- `yavascan2021analysis`：用于说明阈值 ALOHA 中“AoI 超过阈值后再参与竞争”的基本思路与稳态分析。原文可核对题目与摘要中关于 age threshold、fixed probability 和 analytical characterization 的描述。DOI：10.1109/JSAC.2021.3065043
- `saha2021minimum`：用于说明 IRSA 在 grant-free mMTC 场景中可从平均 AoI 角度优化帧长、重复分布与负载。原文可核对摘要中关于 minimum average age of information in IRSA 的表述。DOI：10.1109/JSAC.2021.3065065
- `wang2023age`：用于说明帧时隙 ALOHA 的细化 AoI 理论模型以及最优帧长结论。原文可核对摘要中关于 four versions of frame slotted ALOHA 和 optimum frame length 的描述。DOI：10.1109/TCOMM.2023.3244214
- `ahmetoglu2022mista`：用于说明 MiSTA 协议通过迷你时隙控制序列和碰撞感知后退避来优化 AoI。原文可核对摘要中关于 minislot short control sequence、collision sensing 和 backoff probability 的描述。DOI：10.1109/JIOT.2022.3179132
- `mollahosseini2024effect`：用于说明变量退避、尤其是年龄相关退避，会对平均 AoI 和峰值 AoI 产生不同影响。原文可核对题目与摘要中关于 variable backoff algorithms、average AoI 与 peak AoI 的比较。DOI：10.1109/TMC.2024.3351054
- `pan2022crra`：用于说明冲突解析型随机接入能够在一定条件下改善平均 AoI。原文可核对题目与摘要中关于 collision-resolution random access 和 average AoI improvement 的描述。DOI：10.1109/TVT.2022.3189399
- `xie2025distributed`：用于说明把 AoI 与在线激活控制结合起来的近期研究方向。原文可核对题目与摘要中关于 distributed real-time control、ADAC/T-ADAC 和 minimizing AoI in random access networks 的描述。DOI：10.1109/JIOT.2024.3513408

### CSMA 方向

- `maatouk2020age`：用于说明 CSMA 环境下平均 AoI 的闭式分析、回退优化和 SLEEP 模式思路。原文可核对题目与摘要中关于 average age in a CSMA environment、closed-form result 和 SLEEP mode 的描述。DOI：10.1109/TNET.2020.2971350
- `baiocchi2020age`：用于说明一跳广播 CSMA 网络与部分感知条件下的 AoI 分析。原文可核对题目与摘要中关于 one-hop broadcast communications、CSMA network 和 vehicular beacon use case 的描述。DOI：10.1109/LCOMM.2020.3022090
- `tripathi2023fresh`：用于说明 Fresh-CSMA 试图以分布式方式逼近最大权重调度，并讨论现实碰撞与开销。原文可核对题目与摘要中关于 distributed protocol for minimizing age of information、max-weight mimicry 以及 collisions/overhead 的描述。DOI：10.23919/JCN.2023.000032
- `wang2024analytical`：用于说明更实用的标准 CSMA 网络中，可以把碰撞概率显式纳入 SHS 模型。原文可核对摘要中关于 practical CSMA、finite buffer、SHS model 和 collision probability 的描述。DOI：10.1109/INFOCOM52122.2024.10621330

## 1.2.3 性能分析的研究现状

- `bianchi2002performance`：用于说明标准 CSMA 的经典解耦分析框架，即通过发送概率与碰撞概率的自洽关系建立稳态模型。原文可核对摘要中关于 simple and accurate analytical model、finite number of stations 和 throughput evaluation 的描述。DOI：10.1109/49.840210
- `yates2018age`：用于说明 SHS 已成为 AoI 分析的重要方法论工具。原文可核对题目与摘要中关于 SHS-based age analysis for multiple sources 的描述。DOI：10.1109/TIT.2018.2871079
- `maatouk2020age`：用于举例说明 SHS/混合系统方法在 CSMA 平均 AoI 闭式分析中的使用。原文可核对摘要中关于 closed-form average age 的表述。DOI：10.1109/TNET.2020.2971350
- `wang2024analytical`：用于举例说明 SHS 被推进到更实际的 CSMA/802.11 类场景。原文可核对摘要中关于 practical CSMA network 和 SHS model 的表述。DOI：10.1109/INFOCOM52122.2024.10621330
- `wang2023age`：用于举例说明马尔可夫链/更新间隔分析也已被用于 ALOHA 类协议的 AoI 理论刻画。原文可核对摘要中关于 comprehensive AoI analysis for FSA 的描述。DOI：10.1109/TCOMM.2023.3244214
- `mollahosseini2024effect`：用于举例说明退避参数对平均 AoI 和平均峰值 AoI 的影响可被系统分析。原文可核对摘要中关于 backoff algorithms and AoI 的描述。DOI：10.1109/TMC.2024.3351054
- `zhang2023aoi`：用于说明 AoI 违规概率和分布已经在多源队列系统中得到研究，但仍不普遍。原文可核对题目与摘要中关于 violation probabilities、PDF 和 optimal arrival rate allocation 的描述。DOI：10.1109/JIOT.2023.3297617
- `fiems2024age`：用于说明经典时隙 ALOHA 已出现 AoI 分布、矩与概率质量函数的递推分析。原文可核对题目与摘要中关于 moments、peak AoI 和 PMF algorithm 的描述。DOI：10.1109/ACCESS.2024.3486769

## 补充说明

- 第一章中关于“现有工作仍存在不足”的判断，是在上述文献已公开结论基础上，结合本文研究对象作出的归纳性评价。换句话说，这部分不是单篇文献的原句复述，而是对已有研究覆盖范围与本文切入点之间差异的总结。
- 若您后面准备正式送审，我建议再做一轮“逐篇打开 DOI 页面核对摘要关键词”的人工复核。这个清单已经把最值得核对的位置压缩到题目与摘要层面，复核成本会低很多。
