---
title: EEG-based classification models reveal differential neural processing of words and images
title_zh: 基于脑电图的分类模型揭示词汇和图像的不同神经处理
authors: "Morakabati, N. R., Thiha, A. S., Schechtman, E."
date: 2026-06-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.16.712233v3.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 7.0
evidence: 利用机器学习对EEG进行认知类别解码
tldr: 大脑如何区分处理词语与图像类别信息尚不明确。本研究设计类别重复检测任务，采集30名被试观看五类物体图像和词语时的脑电数据，训练支持向量机进行类别解码。结果发现图像分类准确率显著高于词语，且所有图像类别对均可区分，顶叶和左颞电极贡献突出，模式可跨被试泛化。该方法为利用脑电解码类别表征并探索清醒及离线状态下的神经动态提供了有效工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究大脑对词语和图像类别信息的差异化神经处理机制。
method: 采用类别重复检测任务，记录30名被试观看五类物体图像和词语时的EEG数据，训练支持向量机分类器。
result: 图像分类准确率高于词语，所有图像类别对可区分，顶叶和左颞电极贡献更大，且模式能跨被试泛化。
conclusion: EEG结合机器学习能有效解码类别表征，可用于研究清醒和离线状态下的神经表征激活与再激活。
---

## 摘要
背景：利用神经影像数据的机器学习方法可用于监测神经表征的激活。具体而言，它们可用于识别在处理特定类别项目时所涉及的脑网络。这种方法已被应用于功能磁共振成像数据和脑电图（EEG）数据等神经影像数据。
新方法：在此，我们提出了一项任务和分析流程，用于利用脑电图研究类别表征。参与者（N = 30）观看了一系列属于五个类别（动物、工具、食物、场景和车辆）的物体的图像和词汇，并在同一类别的项目连续呈现时作出反应。
结果：我们在参与者内部的脑电图数据上训练了支持向量机，发现图像试次和词汇试次均产生了显著的类别分类准确率，且图像试次的准确率高于词汇试次。在成对比较类别时，图像试次中所有类别对在统计上均可区分，而词汇试次中仅有一对可区分。顶叶和左颞叶电极对图像分类的贡献大于额叶和右颞叶电极。类别特异的活动模式还在图像试次中跨参与者泛化。
与现有方法的比较：我们的数据和分析流程产生了较高的分类准确率（主要针对图像试次），支持脑电图数据在神经解码中的实用性。
结论：这些方法有助于探索清醒时以及可能在离线状态期间类别层面的神经表征的激活和再激活。

## Abstract
Background: Machine learning methods employing neuroimaging data are useful for monitoring the activation of neural representations. Specifically, they can be used to discern the brain networks engaged in processing specific categories of items. This approach has been employed on neuroimaging data, including functional magnetic resonance imaging data and electroencephalography (EEG) data. New method: Here, we present a task and an analytical pipeline for investigating category representations using EEG. Participants (N = 30) viewed a series of images and words of objects belonging to five categories (Animals, Tools, Food, Scenes, and Vehicles) and responded when items from the same category were presented consecutively. Results: We trained support vector machines on EEG data within participants and found that both image trials and word trials yielded significant category classification accuracy, with image trials achieving higher accuracy than word trials. When comparing categories in a pair-wise fashion, all pairs were statistically distinguishable for image trials, whereas only one pair was distinguishable for word trials. Parietal and Left Temporal electrodes contributed more to image classification than Frontal and Right Temporal electrodes. Category-specific activity patterns also generalized across participants for image trials. Comparison with existing methods: Our data and analytic pipeline yielded high classification accuracies, primarily for image trials, providing support for the utility of EEG data for neural decoding. Conclusions: These methods can be instrumental for exploring the activation and reactivation of neural representations at the category level during wakefulness and, potentially, during offline states.