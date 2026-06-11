---
title: Working Memory as Programmable Fast Weight Computation
title_zh: 工作记忆作为可编程快速权重计算
authors: "Jiang, L., Zhu, Y., Liu, J."
date: 2026-06-08
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.02.729709v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 7.0
evidence: 研究背外侧前额叶皮层在工作记忆中的神经几何，涉及高阶执行功能
tldr: 工作记忆的存储与检索机制尚不明确。本研究结合猕猴前额叶皮层神经几何分析与循环快速权重编程器模型，验证工作记忆是否通过快速权重计算实现。神经数据表明，记忆位置的几何表征在样本期强烈表达，延迟早期消退，随后在需求前于不同记忆子空间重新出现。循环快速权重编程器模型成功复现该动态，揭示了突触可塑性作为存储基质并随时间组织记忆。该发现统一了存储与检索过程，指出生物工作记忆与Transformer架构共享可编程临时记忆原理。
source: biorxiv
selection_source: fresh_fetch
motivation: 工作记忆的存储和检索机制尚不统一，亟需生物与计算层面的机制解释。
method: 结合猕猴前额叶皮层神经几何分析与循环快速权重编程器建模，测试工作记忆的动态快速权重假设。
result: 记忆位置几何在样本期表达、延迟早期消退、需求前于不同子空间重现，模型复现了该动态，并揭示了突触可塑性的核心作用。
conclusion: 生物工作记忆与Transformer共享可编程临时记忆原理，为存储和检索提供了统一框架。
---

## 摘要
工作记忆在感觉输入消失后储存信息，随后以任务相关格式检索信息，但整合储存与检索的机制仍不清楚。在此，我们将猕猴背外侧前额叶皮层在视觉空间延迟匹配样本任务中的神经几何分析与计算建模相结合，以检验工作记忆是否可以实施为循环快速权重计算。我们发现记忆位置的关联几何在样本呈现期间强烈表达，在早期延迟期间退化，并在需求之前于部分不同的记忆子空间中重新出现。一个循环快速权重编程器模型，实现了一种与线性Transformer计算密切相关的动态快速权重记忆形式，再现了这些潜伏到记忆的动力学。对模型的直接检查和扰动揭示，神经活动将刺激信息写入快速可修改的突触状态，突触动力学随时间组织这种潜伏记忆，循环读出查询不断变化的状态以生成任务相关活动。这些发现为工作记忆的储存与检索提供了统一解释，并表明生物工作记忆与Transformer家族架构共享可编程临时记忆的算法原理。

## Abstract
Working memory (WM) stores information after sensory input disappears and later retrieves it in a task-relevant format, but the mechanism unifying storage and retrieval remains unclear. Here we combine neural geometry analyses of macaque dorsolateral prefrontal cortex activity during a visuospatial delayed-match-to-sample task with computational modeling to test whether WM can be implemented as recurrent fast-weight computation. We found that the relational geometry of remembered locations was strongly expressed during sample presentation, degraded during the early delay, and reemerged before requirement in a partially distinct mnemonic subspace. A recurrent fast-weight programmer model, which implements a form of dynamic fast-weight memory closely related to linear Transformer computation, reproduced these latent-to-mnemonic dynamics. Direct inspection and perturbation of the model revealed that neural activity writes stimulus information into rapidly modifiable synaptic states, synaptic dynamics organize this latent memory over time, and recurrent readout queries the evolving state to generate task-relevant activity. These findings provide a unified account of WM storage and retrieval and suggest that biological WM and Transformer family architectures share an algorithmic principle of programmable temporary memory.