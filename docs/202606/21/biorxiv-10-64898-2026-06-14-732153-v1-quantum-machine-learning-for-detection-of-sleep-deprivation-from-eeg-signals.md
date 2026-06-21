---
title: Quantum machine learning for detection of sleep deprivation from EEG signals
title_zh: 基于量子机器学习的EEG信号睡眠剥夺检测
authors: "Sarma-Sarkar, P., Saini, R., Roy, P. P."
date: 2026-06-18
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.14.732153v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 使用EEG频谱带功率和带比值对睡眠剥夺进行分类，体现了认知状态下的相对功率谱分析。
tldr: "睡眠问题困扰印度约50%人口，睡眠剥夺严重损害认知与神经功能。脑电图可客观记录神经改变，适合构建自动检测系统。本研究使用量子支持向量机和混合量子神经网络，通过频谱功率、带比率、Hjorth参数和功能连接提取特征，并将特征编码为量子态构建量子核进行分类。在基于epoch的评估中，混合量子网络准确率达96.88%，QSVM达93.75%；在subject级评估中，HQNN达81.25%，QSVM为75.00%，HQNN显著超越先前最佳结果（68.23%）。这些结果表明量子机器学习在EEG睡眠剥夺检测中表现优异，为生物医学诊断提供了新工具。"
source: biorxiv
selection_source: fresh_fetch
motivation: "睡眠剥夺EEG检测方法准确率有限（先前最高95.72%），本研究探索量子支持向量机与混合量子神经网络以提升分类效果。"
method: 通过提取频谱功率、带比率、Hjorth参数及功能连接特征，编码为量子态构建量子核，采用QSVM和HQNN模型，在epoch和subject两种数据划分下评估。
result: "HQNN在epoch级和subject级分别达96.88%和81.25%准确率，均优于QSVM（93.75%、75.00%）及此前最优结果（68.23%和95.72%）。"
conclusion: 量子机器学习在基于EEG的睡眠剥夺检测中展现出高准确率与潜力，为生物医学现实应用开辟了新方向。
---

## 摘要
据估计，印度约50%的人口存在睡眠相关障碍。睡眠剥夺是一种普遍状况，会对认知表现、神经功能和整体健康产生负面影响。脑电图（EEG）提供了一种客观手段来捕捉与睡眠不足相关的神经变化，使其非常适合用于自动化检测框架。在本研究中，我们探索了量子支持向量机和混合量子神经网络在利用静息态EEG信号分类睡眠剥夺与充分休息状态中的应用。

我们采用了一套全面的特征提取流程，包括频谱带功率、频带比率、Hjorth参数和功能连接度量。这些特征随后被编码为量子态以构建量子核，并用于分类。模型性能在基于时段（epoch-level）和基于受试者（subject-level）的数据划分方案下进行评估。

混合量子神经网络（HQNN）在两种评估设置下均取得了最高性能，时段级准确率达到96.88%，受试者级准确率达到81.25%。QSVM模型在时段级和受试者级评估中分别达到93.75%和75.00%的准确率。在受试者级和时段级评估中，HQNN均优于之前报告的结果（分别为68.23%和95.72%）。总体而言，这些发现突显了量子机器学习作为基于EEG的睡眠剥夺检测的一种有竞争力方法的潜力，对现实世界的生物医学应用具有广阔前景。

## Abstract
Approximately 50% of the population in India is estimated to experience sleep-related disorders. Sleep deprivation is a prevalent condition that adversely impacts cognitive performance, neural functioning, and overall health. Electroencephalography (EEG) offers an objective means of capturing neural alterations associated with sleep loss, making it well-suited for automated detection frameworks. In this study, we explore the application of a Quantum Support Vector Machine and Hybrid Quantum Neural Networks to classify sleep-deprived and well-rested states using resting-state EEG signals.

A comprehensive feature extraction pipeline is employed, incorporating spectral band power, band ratios, Hjorth parameters, and functional connectivity measures. These features are subsequently encoded into quantum states to construct a quantum kernel, which is then utilized for classification. Model performance is evaluated under both epoch-level and subject-level data partitioning schemes.

The Hybrid Quantum Neural Network (HQNN) achieves the highest performance across both evaluation settings, attaining an accuracy of 96.88% at the epoch level and 81.25% at the subject level. The QSVM model achieves accuracies of 93.75% and 75.00% for epoch-level and subject-level evaluations, respectively. At subject-level and epoch -level evaluation, HQNN outperforms previously reported results (68.23% and 95.72%). Overall, these findings highlight the potential of quantum machine learning as a competitive approach for EEG-based sleep deprivation detection, with promising implications for real-world biomedical applications.