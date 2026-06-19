---
title: Stimulus identity rather than emotion drives EEG classification on the FACED dataset
title_zh: FACED数据集上的EEG分类主要由刺激身份而非情绪驱动
authors: "Gerster, M., Sirotina, E., Orlovskii, A., Hertz, A., Champaud, J., Guarino, D., Tulli, S."
date: 2026-06-16
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.12.731889v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 基于EEG的认知/情感状态分类，涉及频谱特征分析
tldr: 脑电解码情绪识别依赖可靠基准数据集，FACED作为最大公开数据集被广泛使用。该研究通过线性分类和深度学习模型发现，FACED上的分类实际反映刺激身份而非情绪：主观报告情绪与标签不符时性能不变，替换个体自报告标签后准确率下降，减少每类视频后准确率反升。研究揭示数据集设计中的三类混淆因素——少刺激、刺激分配标签和同视频时间拆分，导致时间自相关和刺激身份干扰，并据此提出五项改进建议以提升情绪解码研究效度。
source: biorxiv
selection_source: fresh_fetch
motivation: 基准数据集FACED是EEG情绪识别常用标准，但其分类有效性尚未被严格检验，可能存在刺激身份混淆。
method: 采用LinearSVC和CLISA模型，通过比较主观情绪有无、替换自报告标签及减少视频数三个实验评估分类驱动因素。
result: 分类主要受刺激身份而非情绪驱动：主观感受不影响性能，自报告标签降低准确率，减少视频反提高分类。
conclusion: FACED设计导致刺激身份和时间自相关混淆，损害情绪解码有效性；提出五项实验设计建议以规避此类混淆。
---

## 摘要
可靠的基准数据集对于推进基于脑电图（EEG）的情绪识别至关重要。细粒度情感计算EEG数据集（FACED）是最大的公开EEG情绪数据集（123名受试者，九种情绪类别），并被广泛用作基准。我们证明，在FACED上进行的被试内和跨被试分类主要反映的是刺激身份而非情绪。使用线性分类器（LinearSVC）和深度学习模型（CLISA），我们展示：(1) 无论受试者报告是否感受到指定情绪，分类性能相当；(2) 用个体自我报告替代刺激分配的标签时，准确率下降；(3) 当每种情绪只保留一个视频（尽管丢弃了三分之二的数据）时，准确率反而提高。这些结果源于FACED的三个设计选择：每个类别刺激少、使用刺激分配的标签，以及交叉验证中按视频内时间分割。这些因素使数据集易受时间自相关和刺激身份混淆的影响。为引导未来研究，我们提出五项建议——涵盖刺激多样性、时间独立性和标签验证——以设计减轻这些混淆的情绪解码研究。

## Abstract
Reliable benchmark datasets are critical for advancing EEG-based emotion recognition. The Finer-grained Affective Computing EEG Dataset (FACED) is the largest publicly available EEG emotion dataset (123 subjects, nine emotion categories) and a widely adopted benchmark. We demonstrate that both intra-subject and cross-subject classification on FACED primarily reflects stimulus identity rather than emotion. Using a linear classifier (LinearSVC) and a deep learning model (CLISA), we show that (1) classification performance is comparable for trials where subjects reported feeling versus not feeling the assigned emotion; (2) accuracy drops when stimulus-assigned labels are replaced with individual self-reports; and (3) accuracy increases when reducing to one video per emotion despite discarding two-thirds of the data. These results reflect three design choices in FACED: few stimuli per category, stimulus-assigned labels, and within-video temporal splits for cross-validation. Together, these make the dataset susceptible to temporal autocorrelation and stimulus-identity confounds. To guide future work, we propose five recommendations -- spanning stimulus diversity, temporal independence, and label validation -- for emotion-decoding study designs that mitigate these confounds.