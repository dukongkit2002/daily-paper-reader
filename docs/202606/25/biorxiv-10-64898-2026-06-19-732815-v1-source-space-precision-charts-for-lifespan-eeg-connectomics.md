---
title: Source-space precision charts for lifespan EEG connectomics
title_zh: 全生命周期EEG连接组学的源空间精度图谱
authors: "Jin, Y., Reyes, R. G., Wang, Y., Bringas Vega, M. L. L., Valdes-Sosa, P. A."
date: 2026-06-24
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.19.732815v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: JSPACE方法用于源空间EEG连接组学，从头皮交叉谱估计多频源精度矩阵
tldr: 源空间脑电图连接组学面临泄漏和间接中介的挑战，需要可靠的条件交互估计。本研究提出JSPACE框架，从头皮交叉谱联合估计多频率源精度矩阵，采用稀疏正则化与随机优化。模拟中JSPACE降低相干膨胀，提升支持恢复。应用于1935名参与者构建寿命图谱，揭示非对角线形态沿年龄、频率和强度连续轴变化，对角线保持alpha波谷形态，delta梯度与感觉运动关联组织对齐，并在最老群体出现偏差。
source: biorxiv
selection_source: fresh_fetch
motivation: 源空间EEG连接组学需要可靠估计条件交互，以克服泄漏、公共驱动和间接中介问题。
method: 提出JSPACE，联合源交叉谱估计与稀疏正则化精度拟合，并采用随机活动集优化。
result: 模拟中JSPACE减少相干膨胀，提升支持恢复；寿命图谱显示连续非对角线形态和保守alpha波谷。
conclusion: JSPACE为频率解析的源精度图谱提供可扩展框架，揭示皮质连接的发育模式与老化偏差。
---

## 摘要
源空间脑电图（EEG）连接组学旨在从头表和导联场混合的传感器交叉谱中估计皮层发生源之间的交互。该任务困难在于边缘源协方差或相干性可能残留泄漏、共同驱动和间接中介，而发育映射需要可在大型队列中重复估计的条件交互。我们开发了JSPACE（联合源空间精度与交叉谱估计），一种从头皮交叉谱估计多频源精度矩阵的频域反演框架。JSPACE将后验源交叉谱估计与标准化精度拟合、稀疏频率平滑解剖正则化、随机活动集优化及后选择重拟合相结合。仿真中其优势具有目标特异性：JSPACE降低了相干膨胀，并在前向神经群体基准中实现了最低的虚部相干和峰值频率误差。当真实精度矩阵已知时，它取得了最高的精确、边折叠及泄漏感知的支持恢复。我们将JSPACE应用于来自1935名年龄5.17至97.00岁参与者的HarMNqEEG交叉谱数据，涵盖47个频率区间和360个皮层分区。通过仿射不变的Karcher切空间协调，将个体水平估计重建成包含360条对角线和64,620个源对年龄-频率曲面的全生命周期图谱。该图谱揭示了连续的非对角线形态景观，其中年龄方向、频率偏好和交互强度表现为重叠轴而非离散边类。相比之下，对角线精度曲面在各分区共享保守的alpha波谷形态。代表性实精度通路捕获了后顶叶、感觉运动-顶叶、额极和视觉-顶叶等模式。Delta频段梯度与从儿童期至成年晚期的皮层感觉运动-联合（S-A）组织中度对齐，并在最稀疏年龄范围内出现候选的最老老年偏差。JSPACE为全生命周期EEG中频率分辨的源精度制图提供了一个可扩展框架。

## Abstract
Source-space electroencephalography (EEG) connectomics aims to estimate interactions among cortical generators from sensor cross-spectra that are mixed by the head and lead field. This task is difficult because marginal source covariance or coherence can retain leakage, common drive and indirect mediation, whereas developmental mapping requires conditional interactions that can be estimated repeatedly across large cohorts. We developed JSPACE (Joint Source-space Precision And Cross-spectral Estimation), a frequency-domain inverse framework for estimating multi-frequency source precision matrices from scalp cross-spectra. JSPACE couples posterior source cross-spectral estimation with standardized precision fitting, sparse frequency-smooth anatomical regularization, stochastic active-set optimization and post-selection refitting. In simulations, its advantage was target-specific: JSPACE reduced coherence inflation and achieved the lowest imaginary-coherence and peak-frequency errors in a forward neural-mass benchmark. When the ground-truth precision matrix was known, it achieved the highest exact, edge-collapsed and leakage-aware support recovery. We applied JSPACE to HarMNqEEG cross-spectral data from 1,935 participants aged 5.17--97.00 years, spanning 47 frequency bins and 360 cortical parcels. Affine-invariant Karcher tangent harmonization reconstructed subject-level estimates into a lifespan atlas of 360 diagonal and 64,620 source-pair age-frequency surfaces. The atlas revealed a continuous off-diagonal morphology landscape, in which age direction, frequency preference and interaction strength varied as overlapping axes rather than discrete edge classes. In contrast, diagonal precision surfaces shared a conserved alpha-trough morphology across parcels. Representative real-precision pathways captured posterior parietal, sensorimotor-parietal, frontopolar and visual-parietal motifs. Delta-band gradients were moderately aligned with the sensorimotor-association (S-A) organization of cortex from childhood through late adulthood, with a candidate oldest-old deviation in the sparsest age range. JSPACE provides a scalable framework for frequency-resolved source-precision charting in lifespan EEG.