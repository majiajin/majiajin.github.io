---
layout: post
title: "动态随机一般均衡 (DSGE) 模型简介"
date: 2019-05-16 08:00
categories: 经世济民
permalink: /archivers/dsge_introduction
---

动态随机一般均衡 (Dynamic Stochastic General Equilibrium，DSGE) 模型是现代主流宏观经济理论的基本研究范式，不仅在学术领域中占据主导地位，同时也在中央银行的政策分析和经济预测中发挥巨大作用。


## 1. DSGE 模型的优点

如其名称所示，DSGE 模型具有三大特征：

(1) 动态 (Dynamic) ：模型中各经济主体基于其偏好、技术和约束条件求解跨期最优化问题，从而得以探讨各个宏观经济变量如何随时间变化而变化的动态性质；

(2) 随机 (Stochastic) ：模型中包含多种外生随机冲击，如全要素生产率冲击、劳动供给冲击、货币政策冲击等，刻画了现实经济中存在的各种不确定性；

(3) 一般均衡 (General Equilibrium) ：模型中所有市场同时出清，从而得以分析各经济主体和经济变量之间的相互联系与相互影响。

<!--more-->

传统的计量经济模型存在一些难以忽视的缺点，例如：在模型设定上不是从经济个体的最优化行为决策出发，缺乏微观经济理论基础；微观经济分析和宏观经济分析基本处于割裂状态，模型缺乏良好的整体性；模型中通常采用静态预期或自适应预期，而不是理性预期，从而影响模型的模拟结果和政策分析；通常是非结构性模型，因此无法避免卢卡斯批判等。相比之下，DSGE 模型具有理论上的严谨性和一致性，在建模框架上呈现出显性的结构特点，在政策分析上具有优越性 (刘斌，2008) 。

DSGE 模型主要有三方面的作用：讲故事、政策实验以及经济预测 (Del Negro & Schorfheide，2013) 。三者相辅相成，不可分割：构建符合现实的理论模型，以此探讨各经济变量之间的相互作用与联动关系，此谓「讲故事」；政策实验需要依托于设定良好的模型，从而考察不同经济政策对实际经济运行造成的影响；经济预测的准确性是检验模型设定是否合理的评判标准之一，而且更好的经济预测手段可以让央行和政府及早发现经济问题，及时采取合适的经济政策，从而更好地稳定经济。


## 2. DSGE 模型的类型

按照发展阶段和模型设定的不同，DSGE 模型大致可分为两大类：真实经济周期 (Real Business Cycle，RBC) 模型和新凯恩斯主义 (New Keynesian，NK) 模型。二者目前均被广泛使用，通常根据研究目的的不同而选择采用相应的模型。下面参照 Galí (2015) 的经典综述，简单介绍 RBC 模型与 NK 模型的历史渊源和异同。

### 2.1 真实经济周期 (RBC) 模型

在 Kydland & Prescott (1982) 的开创性论文发表之后，RBC 模型逐步成为分析经济周期波动的主要分析框架和宏观经济理论的核心工具。

RBC 模型对宏观经济理论带来的冲击主要体现在以下三个方面：

(1) 经济周期的有效性。在工业化国家中所观察到的大部分经济波动都可以被解释为在一个完全竞争和无摩擦的市场环境中，经济对实际变量的外生变化所做出的反应而导致的均衡结果。经济的周期性波动并非意味着资源配置的无效率，实际上，由标准的 RBC 模型所产生的波动反而是最优的。这一观点得出了一个重要推论：稳定化政策可能是不必要或不合意的，甚至可能会适得其反。这与经济波动的传统解释相冲突，回溯到凯恩斯，衰退被视作资源被无效率地过低利用的时期，并且可以被旨在扩张总需求的经济政策所终结。

(2) 技术冲击作为经济波动来源的重要性。这一论断源自于基本的RBC模型在生成总产出以及其他宏观经济变量的「实际」波动方面的能力，即使当全要素生产率 (经校准以匹配索洛余值) 的变化被假定为唯一的外生推动力时。对经济波动的这样一种解释与如下的传统观点形成了鲜明对比，即技术变动是长期经济增长的源泉，而与短期经济周期无关。

(3) 货币因素的有限作用。RBC 模型试图在不考虑货币因素，甚至是不需要货币部门存在的情况下，来解释经济波动。

尽管在学术界的研究者中产生了重要影响，RBC 模型对中央银行以及其他政策机构的作用有限。这些机构仍然继续依赖于大规模的宏观计量模型，尽管这些模型对于政策评估的有用性已经受到了挑战，或者是在识别这些模型的估计所面临的约束时具有很大的随意性。

一些研究者尝试在一个传统的 RBC 模型中引入货币部门，同时仍然保留完全竞争以及完全灵活的价格和工资的设定。但是这并没有产生一个可用于政策分析的框架。这一框架，也称古典货币模型，通常预测货币政策是中性或接近中性的。然而，古典货币模型的这一结论与已被广泛接受的观念是不一致的，即货币政策至少在短期内会影响总产出和就业，这一观念获得了大量实证研究的支持。

古典货币模型的规范含义也使得许多经济学家怀疑这一模型作为政策评估的框架的适用性。古典货币模型通常得到的规范含义是弗里德曼规则 (中央银行将短期名义利率保持在零的常数水平) 的最优性，而这一政策规则和绝大多数中央银行所追求的货币政策大相径庭。中央银行货币政策的特征是经常大幅度地调整利率，以应对通货膨胀和经济活动的指标对其目标水平的偏离，即泰勒规则。

理论预测和实证结果之间的冲突以及规范含义和政策实践之间的冲突，表明古典货币模型中缺失了实际经济中的一些重要因素。在保留 RBC 模型的设定作为基础结构的同时，这些缺陷正是导致引入某些凯恩斯主义假定背后的主要动因。

### 2.2 新凯恩斯主义 (NK) 模型

无论是标准形式抑或更加复杂的扩展形式，NK 模型与 RBC 模型具有许多相似的核心设定：(1) 一个无限期生存的代表性家庭在跨期预算约束下，试图最大化基于消费和闲暇的效用；(2) 大量厂商具有相同的、并且服从外生随机变动的技术；(3) 均衡具有随机过程的形式，在给定家庭和厂商的目标和约束条件下，经济中所有的内生变量与家庭和厂商的最优跨期决策相一致，同时所有市场出清。

但是 NK 模型在 RBC 模型具有的 DSGE 结构特征的基础上，增加了一些不同于古典货币模型的关键假设：

(1) 垄断竞争。价格和工资由经济个体最大化其目标函数来决定，而非由匿名的瓦尔拉斯拍卖者按照瞬时出清所有竞争性市场来决定。

(2) 名义刚性。厂商在调整商品价格的频率方面受到一些约束，或者说，厂商可能面临一些价格调整成本。同样的摩擦也适用于工人，当出现粘性工资时。

(3) 货币政策的短期非中性。由于存在名义刚性，短期内名义利率 (无论是由中央银行直接决定，还是由货币供给和需求的变动所导致) 并不会与预期通货膨胀率同等变化，从而导致实际利率发生变动。实际利率的变动引起消费、投资、总产出和就业的变动，因为厂商调整产品供给以满足新的需求水平。但是在长期中，所有的价格和工资都将调整，经济将回归到其自然均衡。

NK 模型具有与 RBC 模型不同的经济和政策含义：(1) 经济对于冲击的反应通常的无效率的；(2) 由于存在名义刚性而导致的货币政策非中性，使得货币当局纠正市场扭曲、增进社会福利的干预措施有了用武之地；(3) 模型适用于不同货币政策的分析和比较，而不受卢卡斯批判的制约。


## 3. DSGE 模型在中央银行中的应用

随着 DSGE 模型在模型设定、求解技术以及参数估计等方面的巨大进步，中央银行开始在政策分析和经济预测中广泛应用 DSGE 模型。DSGE 模型能够为政策讨论和分析提供一个强有力的一致性框架，帮助识别经济波动的来源，评估不同政策的潜在效果，并具备与传统宏观计量模型相当的预测能力。

全球主要经济体的中央银行均开发了分析本国或全球经济的 DSGE 模型，并在官方网站上公布了模型的具体设定甚至程序代码。表 1 列示了部分中央银行所使用的最新模型，并附上具体链接，以供参考。

<center> 表 1 部分中央银行所使用的 DSGE 模型 </center>

| <center> 中央银行 </center>	            | DSGE 模型                                 |
|:------------------------------------------|:-----------------------------------------:|
| 美国联邦储备局 (Federal Reserve Board)	| [EDO][EDO], [SIGMA][SIGMA]                |
| 加拿大银行 (Bank of Canada)	            | [ToTEM II][ToTEM II], [BoC-GEM][BoC-GEM]  |
| 欧洲中央银行 (European Central Bank)	    | [NAWM II][NAWM II], [EAGLE-FLI][NAWM II]  |
| 英格兰银行 (Bank of England)	            | [COMPASS][COMPASS]                        |
| 瑞典中央银行 (Sveriges Riksbank)	        | [Ramses II][Ramses II]                    |
| 挪威银行 (Norges Bank)	                | [NEMO][NEMO]                              |


## 扩展阅读

2008 年全球金融危机之后，宏观经济学家们就 DSGE 模型开展了多轮辩论，李向阳 (2018) 中的「0.2.3 DSGE 分析框架的表扬与批评」对此做了简要评述。

Galí (2015) 是 DSGE 模型的经典教科书，本章中的「2. DSGE 模型的类型」便是该书第一章的浓缩，建议认真阅读原文。

> [1] 0.2.3 DSGE 分析框架的表扬与批评
> 
> [http://www.tup.com.cn/upload/books/yz/074344-01.pdf](http://www.tup.com.cn/upload/books/yz/074344-01.pdf)
> 
> 李向阳. (2018). 动态随机一般均衡 (DSGE) 模型：理论、方法和Dynare实践
>
> [2] Chapter 1: Introduction
> 
> [http://assets.press.princeton.edu/chapters/s10495.pdf](http://assets.press.princeton.edu/chapters/s10495.pdf)
> 
> Galí, Jordi. (2015). Monetary Policy, Inflation, and the Business Cycle: An Introduction to the New Keynesian Framework and Its Applications (Second Edition)


## 参考文献

[1]	DEL NEGRO M, SCHORFHEIDE F. DSGE Model-Based Forecasting [M] // Elliott G, Timmermann A. Handbook of Economic Forecasting. Elsevier. 2013: 57-140.

[2]	GALí J. Monetary Policy, Inflation, and the Business Cycle: An Introduction to the New Keynesian Framework and Its Applications (Second Edition)[M]. Princeton University Press, 2015.

[3]	KYDLAND F E, PRESCOTT E C. Time to Build and Aggregate Fluctuations[J]. Econometrica, 1982, 50(6):1345-1370.

[4]	刘斌. 我国DSGE模型的开发及在货币政策分析中的应用[J]. 金融研究, 2008, (10):1-21.

[EDO]:       https://www.federalreserve.gov/econres/edo-models-about.htm
[SIGMA]:     https://www.federalreserve.gov/pubs/ifdp/2005/835/revision/IFDP835r.pdf
[ToTEM II]:  https://www.bankofcanada.ca/2013/10/technical-report-100
[BoC-GEM]:   https://www.bankofcanada.ca/2007/09/technical-report-no98
[NAWM II]:   https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2200.en.pdf
[EAGLE-FLI]: https://www.ecb.europa.eu/pub/pdf/scpwps/ecbwp1923.en.pdf
[COMPASS]:   https://www.bankofengland.co.uk/working-paper/2013/the-boes-forecasting-platform-compass-maps-ease-and-the-suite-of-models
[Ramses II]: https://www.riksbank.se/en-gb/press-and-published/publications/working-paper-series/occasional-paper-series/occasional-paper-series-no.-12-ramses-ii--model-description
[NEMO]:      https://www.norges-bank.no/en/topics/Monetary-policy/Models-for-monetary-policy-analysis-and-forecasting/NEMO
