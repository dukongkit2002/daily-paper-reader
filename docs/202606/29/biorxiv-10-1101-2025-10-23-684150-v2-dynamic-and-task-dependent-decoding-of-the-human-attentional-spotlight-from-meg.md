---
title: Dynamic and task-dependent decoding of the human attentional spotlight from MEG
title_zh: 基于脑磁图的人注意聚光灯动态与任务依赖性解码
authors: "Mostafalu, M., Clausner, T., Ferez, M., Shelepenkov, D., Daligault, S., Schwartz, D., Mattout, J., Ben Hamed, S., Bonnefond, M."
date: 2026-06-24
pdf: "https://www.biorxiv.org/content/10.1101/2025.10.23.684150v2.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 使用MEG基于alpha/theta功率解码注意焦点，揭示任务依赖的频谱动态，与EEG认知任务频谱分析同类
tldr: "大脑通过注意力克服并行处理限制，但其空间焦点如何随任务需求动态变化且能否被非侵入解码尚不清楚。本研究采用高精度脑磁图(MEG)与机器学习，在三项不同有效性及切换规则的空间线索任务中解码隐蔽注意定位。解码性能显著，且随线索有效性降低而下降；注意呈现~8-12 Hz节律性采样，预目标期注意聚焦于提示侧，尤以100%有效条件为甚；个体解码强度与辨别正确率和反应时等行为表现相关。结果证实MEG可非侵入捕获任务依赖的动态注意波动，为注意机制研究及神经反馈等临床应用提供了新途径。"
source: biorxiv
selection_source: fresh_fetch
motivation: 探究人脑空间注意的动态任务依赖性调控能否被非侵入解码，以桥接侵入性动物研究与非侵入人类研究。
method: 利用高精度MEG和机器学习，在三种操纵线索有效性与无效试次切换规则的空间线索任务中解码隐蔽空间注意。
result: 解码精度显著高于随机水平，随线索有效性降低而下降；注意出现α波段节律性采样，预目标期聚焦于提示侧；解码强度个体差异与行为表现（辨别正确率、反应时）显著相关。
conclusion: MEG能非侵入捕获任务依赖的动态注意波动，注意需求重塑神经代码并调节节律采样，影响行为效率；该方法有望用于注意机制研究和神经反馈等临床应用。
---

## 摘要
注意力是使大脑克服并行处理能力限制的基本机制。在非人灵长类动物中，侵入性电生理学研究表明，注意选择以节律性方式运作，主要在 alpha（约 8-12 Hz）和 theta（约 4-5 Hz）频段内。这种精细分辨的控制信号能否在人类中通过非侵入性方式捕捉，以及它们如何适应不断变化的任务需求，目前仍不清楚。我们利用高精度脑磁图（MEG）结合机器学习，对执行三种空间线索任务变体的人类进行了解码，这些任务操纵了线索有效性以及无效试次的切换规则，从而解码了内隐注意的空间位置。

在全脑 MEG 活动中，可以在静态和时间分辨两个尺度上对空间注意进行解码，准确率显著高于随机水平（N = 30）。当线索有效性降低时，解码表现下降，表明任务结构塑造了注意参与。对解码轨迹的分析揭示了所有任务中约 8-12 Hz 的节律性波动，展示了注意的 alpha 频段采样。预目标注意逐渐聚焦于线索提示侧，尤其是在 100% 有效条件下，这与主动定向一致。此外，解码强度的个体差异和任务特异性差异与行为表现的任务间差异相关，将神经注意编码的准确性与辨别准确率和反应时间联系起来。

这些发现表明，MEG 可以非侵入性地捕捉空间注意的动态、任务依赖性波动，这与在非人灵长类动物中观察到的现象类似。它们揭示了注意需求重塑了注意的神经编码，调节了节律性采样，并影响行为效率。这项工作架起了侵入性灵长类动物研究和非侵入性人类研究之间的桥梁，并将基于 MEG 的注意解码确立为机械性和临床应用的潜在工具，包括神经反馈和与注意相关的干预。

## Abstract
Attention is a fundamental mechanism enabling the brain to overcome its limited capacity for parallel processing. In non-human primates, invasive electrophysiology has shown that attentional selection operates rhythmically, primarily within the alpha ([~]8-12 Hz) and theta ([~]4-5 Hz) bands. Whether such finely resolved control signals can be captured non-invasively in humans, and how they adapt to changing task demands, remains unclear. Using high-precision magnetoencephalography (MEG) combined with machine learning, we decoded the spatial locus of covert attention in humans performing three variants of a spatial cueing task that manipulated cue validity as well invalid trial switching rules.

Spatial attention could be decoded from whole-brain MEG activity at both static and time-resolved scales, with accuracies significantly above chance (N = 30). Decoding performance decreased as cue validity was reduced, indicating that task structure shapes attentional engagement. Analysis of decoding trajectories revealed rhythmic fluctuations at [~]8-12 Hz across all tasks, demonstrating alpha-band sampling of attention. Pre-target attention became increasingly focused on the cued side, especially in the 100% Valid condition, consistent with proactive orienting. Furthermore, individual and task-specific differences in decoding strength correlated with task-variations in behavioral performance, linking the accuracy of neural attention codes to both discrimination accuracy and reaction time.

These findings demonstrate that MEG can non-invasively capture dynamic, task-dependent fluctuations in spatial attention that parallel those observed in non-human primates. They reveal that attentional demands reshape the neural code for attention, modulate rhythmic sampling, and influence behavioral efficiency. This work bridges invasive primate and non-invasive human research and establishes MEG-based decoding of attention as a promising tool for mechanistic and clinical applications, including neurofeedback and attention-related interventions.