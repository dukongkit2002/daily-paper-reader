---
title: "Getting Blood from a Stone: Improving Neural Inferences without Additional Neural Data"
title_zh: 石中取血：无需额外神经数据改善神经推断
authors: "Halpern, D. J., Gureckis, T. M."
date: 2026-06-23
pdf: "https://www.biorxiv.org/content/10.1101/2021.01.21.427334v4.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 展示如何通过收集更多行为数据和使用替代估计器来改进神经影像推断，适用于EEG-认知关联研究
tldr: 认知神经科学中存在大量低统计功效研究，传统改进需追加神经数据。本文提出仅收集行为数据并采用替代估计量，即可提升神经推断精度。模拟与推导表明，行为数据能廉价等效增强统计效力，研究者可平衡扫描与行为被试量，以更低成本获得可靠结论。
source: biorxiv
selection_source: fresh_fetch
motivation: 解决认知神经影像研究因样本量不足导致的推断可靠性问题，探寻无需增加神经数据的新途径。
method: 利用模拟实验与数学推导，分析行为边际分布信息如何改善神经信号映射的估计精度。
result: 精度增益量取决于估计目标与实验参数，合理采集行为数据可取得与增加神经数据相当的改进效果。
conclusion: 研究设计时可灵活调配脑成像与行为实验的被试人数，以更经济方式提升统计效力。
---

## 摘要
近年来，认知神经科学文献因包含许多低统计功效的研究而受到批评，这限制了进行可靠统计推断的能力。通常，提高功效的建议是收集更多带有神经信号的数据。然而，许多认知神经科学研究使用从行为数据估计的参数来推断神经信号（如fMRI BOLD信号）。在本文中，我们探讨认知神经科学家如何通过仅收集行为数据和使用旨在利用这些信息的替代估计量，来更深入地了解其神经影像信号。我们通过模拟和数学推导证明，了解更多关于行为边际分布的信息可以改善对认知过程与神经数据之间映射的推断。我们分析了这种益处的程度，发现它取决于所需的估计目标和几个潜在的研究参数。虽然许多情况下精度的绝对增益可能不大，但我们的结果表明，在现实条件下，额外的行为数据可以比在神经影像研究中额外收集被试数据更便宜、更容易地实现推断精度的同等提升。这意味着在进行神经影像研究时，研究人员现在在设计分析中有了另一个可调节的变量：扫描仪中收集的被试数量，以及扫描仪外（在实验室或线上）收集的行为被试数量。

## Abstract
In recent years, the cognitive neuroscience literature has come under criticism for containing many low-powered studies, limiting the ability to make reliable statistical inferences. Typically, the suggestion for increasing power is to collect more data with neural signals. However, many studies in cognitive neuroscience use parameters estimated from behavioral data in order to make inferences about neural signals (such as fMRI BOLD signal). In this paper, we explore how cognitive neuroscientists can learn more about their neuroimaging signal by collecting data on \textit{behavior alone} and using alternative estimators designed to leverage this information. We demonstrate through simulation and mathematical derivations that knowing more about the marginal distribution of behavior can improve inferences about the mapping between cognitive processes and neural data. We analyze the magnitude of this benefit, finding that it depends on the desired estimand and several underlying study parameters. While in many cases the absolute gains in precision can be modest, our results demonstrate that, in realistic settings, additional behavioral data can lead to the same improvement in the precision of inferences more cheaply and easily than collecting additional data from subjects in a neuroimaging study. This means that when conducting a neuroimaging study, researchers now have another knob to turn in a design analysis: the number of subjects collected in the scanner and the number of behavioral subjects collected outside the scanner (in the lab or online).