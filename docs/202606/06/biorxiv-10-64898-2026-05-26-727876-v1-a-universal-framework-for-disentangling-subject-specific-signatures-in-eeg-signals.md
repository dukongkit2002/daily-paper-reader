---
title: A UNIVERSAL FRAMEWORK FOR DISENTANGLING SUBJECT-SPECIFIC SIGNATURES IN EEG SIGNALS
title_zh: 一种用于解耦脑电信号中个体特异性特征的通用框架
authors: "Pei, Z."
date: 2026-05-29
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.26.727876v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 用于解缠个体特异性EEG特征的深度学习框架，可用于认知倾向评估中的个体差异分析
tldr: 从原始脑电信号中提取稳定的被试特异性特征仍面临巨大挑战，主要源于其与瞬态脑状态的深度纠缠。针对此问题，本文提出一个通用神经网络框架，通过解耦模块和交叉重建学习目标，有效分离被试固有属性与状态依赖成分。在基于EEG的生物特征识别任务中，采用两个公开数据集和留一状态交叉验证策略，该框架在四种不同骨干架构上均显著提高了分布外辨识准确率，展现了即插即用的跨模型泛化能力。该工作为个性化神经科技应用中可靠的神经指纹提取奠定了基础。
source: biorxiv
selection_source: fresh_fetch
motivation: 提取稳定被试特异性特征因与瞬态脑状态纠缠而充满挑战，迫切需要一种通用解耦方案。
method: 采用解耦模块与交叉重建损失，从原始EEG中分离出被试固有神经签名，可即插即用于不同骨干网络。
result: 在两个公开数据集上，留一状态交叉验证，四种骨干模型分布外识别率均显著提升，验证即插即用通用性。
conclusion: 该框架实现了可靠神经签名提取，促进了即插即用的个性化神经技术应用，为EEG解码奠定基础。
---

## 摘要
由于脑电信号与瞬态脑状态纠缠在一起，从中提取稳定的个体特异性特征仍然具有挑战性。我们提出了一种通用神经框架，用于将原始脑电信号中的个体特异性特征与状态依赖成分解耦。我们的方法采用解耦模块，以交叉重构为目标隔离个体特异性表征。我们在脑电生物特征识别上验证了该框架，使用两个公共数据集，并采用留出一状态交叉验证。结果表明，在四种不同的骨干模型上，分布外识别准确率均显著提高，证实了该方法的通用性和即插即用能力。这项工作推动了面向个性化神经技术应用的神经特征可靠提取。

## Abstract
Extracting stable subject-specific features from EEG signals remains challenging due to their entanglement with transient brain states. We propose a universal neural framework that disentangles subject-specific features from state-dependent components in raw EEG signals. Our approach employs a disentanglement module with a cross-reconstruction objective to isolate subject-specific representations. We validate our framework on EEG-based biometric recognition using two public datasets with leave-one-state-out cross-validation. Results demonstrate significant improvements in out-of-distribution identification accuracy across four different backbone models, confirming our methods universality and plug-and-play capability. This work advances reliable extraction of neural signatures for personalized neurotechnology applications.