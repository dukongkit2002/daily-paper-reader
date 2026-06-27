---
title: Bayesian Nonparametric Identification of Frequency-Selective Neural Oscillatory States
title_zh: 频率选择性神经振荡状态的贝叶斯非参数识别
authors: "Yamada, S., Nagel, S. E., Kobeleva, X., Schmidt, R."
date: 2026-06-25
pdf: "https://www.biorxiv.org/content/10.64898/2025.12.20.695571v3.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 贝叶斯非参数方法识别频段特异性神经振荡
tldr: 神经振荡识别对于理解大脑认知过程至关重要，但传统方法依赖预定义频带和阈值，而隐马尔可夫模型需预先设定状态数，易导致欠拟合或过拟合。本研究提出一种结合时间延迟嵌入与狄利克雷过程高斯混合模型的贝叶斯非参数方法，能够自动推断状态数量并捕获频率特异性结构。在模拟神经信号和静息态运动皮层MEG数据上，该方法成功识别出多种频率选择性振荡状态，并揭示了个体间的异质性。该框架无需事先指定频带或状态数，为神经振荡的无监督发现提供了新途径。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统神经振荡检测需人工设定频带和状态数，限制了无监督发现未知状态的能力。
method: 结合时间延迟嵌入与狄利克雷过程高斯混合模型，通过自协方差捕捉频率特异性，自动推断状态数。
result: 在合成数据与静息态MEG上识别出多种频率选择性振荡状态，且发现个体间存在显著异质性。
conclusion: 提供了一种无监督贝叶斯非参数框架，无需预定义频带或状态数，有助于发现新的神经振荡状态。
---

## 摘要
识别神经振荡对于将快速脑动态与底层认知过程联系起来至关重要。然而，这具有挑战性，因为振荡事件可能短暂、嵌入在类似1/f的背景活动中，并且可能包含数量未知的频谱不同状态。传统方法通常对一个或几个预定义的频带应用窄带带通滤波器，然后使用幅度阈值来识别振荡事件，但检测结果可能对这些选择高度敏感。尽管最近基于隐马尔可夫模型（HMM）的无监督替代方案解决了这些局限性，但它们仍然需要事先指定状态数量，并且在数量指定错误时可能导致欠拟合或过拟合。我们提出了一种贝叶斯非参数方法，可以在直接从数据推断合适状态数量的同时识别不同的振荡状态。该方法结合了时延嵌入（TDE）和狄利克雷过程高斯混合模型（DP-GMM）。TDE通过增加信号的时移副本增强信号，使DP-GMM能够捕获频率特定的局部自协方差结构，而狄利克雷过程先验通过修剪非活跃成分来自适应调整模型复杂度。我们使用模拟神经时间序列（例如EEG、MEG和局部场电位）的单通道合成数据对该方法进行了基准测试，这些数据包含多个频率成分并被类似1/f的噪声掩盖。在此设置下，所提出的模型在噪声条件下可靠地恢复了多个不同的频率成分，同时推断出振荡状态的数量。将模型应用于静息态运动皮层MEG数据集，识别出多个频率选择性的短时振荡状态以及具有不同频谱特征的明显非周期性状态。这些状态在峰值频率、发生率和功率方面表现出显著的个体间异质性。总体而言，这提供了一个无监督框架，用于发现频率选择性的振荡状态，而无需预定义频段或固定状态数量。

## Abstract
Identifying neural oscillations is essential for linking fast brain dynamics to underlying cognitive processes. However, this is challenging because oscillatory events can be brief, embedded in 1/f-like background activity, and may comprise an unknown number of spectrally distinct states. Conventional approaches often apply narrowband band-pass filters to one or a few predefined frequency bands and then use amplitude thresholding to identify oscillatory events, but detection outcomes can be highly sensitive to these choices. Although recent unsupervised alternatives based on hidden Markov models (HMMs) address these limitations, they still require the number of states to be specified in advance and can underfit or overfit when this number is misspecified. We propose a Bayesian nonparametric method that identifies distinct oscillatory states while inferring an appropriate number of states directly from the data. This method combines time-delay embedding (TDE) with the Dirichlet-process Gaussian mixture model (DP-GMM). TDE augments the signal with time-shifted copies, enabling the DP-GMM to capture frequency-specific local autocovariance structures, while the Dirichlet-process prior adapts model complexity by pruning inactive components. We benchmarked the approach against a filter-based thresholding method and the time-delay embedded HMM using single-channel synthetic data designed to mimic neural time series (e.g., EEG, MEG, and local field potentials), with multiple frequency components masked by 1/f-like noise. In this setting, the proposed model reliably recovered multiple distinct frequency components under noisy conditions while also inferring the number of oscillatory states. Applied to a resting-state motor-cortex MEG dataset, the model identified multiple frequency-selective, short-lived oscillatory states alongside distinct aperiodic states with different spectral profiles. These states exhibited substantial inter-individual heterogeneity in peak frequency, occurrence rate, and power. Overall, this provides an unsupervised framework for discovering frequency-selective oscillatory states without predefining frequency bands or fixing the number of states.