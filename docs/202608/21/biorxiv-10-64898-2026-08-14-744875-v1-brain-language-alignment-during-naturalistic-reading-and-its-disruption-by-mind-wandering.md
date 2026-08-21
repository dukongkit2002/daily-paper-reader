---
title: Brain-Language Alignment During Naturalistic Reading and Its Disruption by Mind-Wandering
title_zh: 自然阅读中的脑-语言对齐及其受心智游移的干扰
authors: "Sun, H., Jangraw, D. C."
date: 2026-08-19
pdf: "https://www.biorxiv.org/content/10.64898/2026.08.14.744875v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 9.0
evidence: 在自然阅读认知任务中分析EEG频谱功率和注视相关电位
tldr: 自然阅读中EEG脑-语言对齐是否可检测及受心游荡影响尚不明确。本研究使用ROAMM数据集44名被试的同时EEG和眼动记录，以岭回归编码模型结合五种词嵌入预测注视相关EEG特征。结果发现可靠脑-语言对齐，上下文嵌入优于静态嵌入，且在alpha/低β频段及注视后200-300ms最强。心游荡显著降低对齐，对频谱特征影响更大，表明注意力波动是编码研究中被低估的变异性来源。
source: biorxiv
selection_source: fresh_fetch
motivation: 自然阅读中EEG脑-语言对齐是否可检测，以及心游荡如何影响它，尚不清楚。
method: 基于ROAMM数据集44名被试的同时EEG和眼动追踪，用岭回归编码模型融合五种词嵌入预测注视对齐EEG频谱功率和FRP。
result: 发现可靠脑-语言对齐，上下文嵌入更优；频谱对齐在α/低β频段最强，FRP在注视后200-300ms最强；心游荡降低对齐，对PSD影响更大。
conclusion: 现代语言模型表征在自然阅读EEG中可检测，注意力波动是脑-语言编码研究中被低估的变异性来源。
---

## 摘要
编码模型为将语言的计算表征与神经活动联系起来提供了一个原则性框架，但大多数关于脑-语言对齐的脑电图（EEG）证据来自严格控制的逐词阅读范式。这种对齐在自然阅读中是否可检测，以及它如何受到注意力涣散的影响，仍不清楚。我们使用ROAMM数据集来解决这些问题，该数据集是一个多模态数据集，包含44名参与者在阅读自然文本时同步采集的EEG和眼动追踪记录，以及时间分辨的心智游移（MW）注释。我们训练岭回归编码模型，从五种词嵌入模型（GloVe、word2vec、BERT、GPT-2和Llama 3）中预测注视对齐的EEG频谱功率和注视相关电位（FRPs）。通过使用置换检验并进行错误发现率校正，我们发现在两种特征类型上均存在统计上可靠的脑-语言对齐，且上下文嵌入优于静态嵌入。频谱对齐在顶叶电极的alpha和低beta频段最强，而基于FRP的对齐在注视开始后200-300毫秒在中央和顶枕区域达到峰值。利用ROAMM的跨度级MW注释，我们进一步表明，在MW期间，脑-语言对齐被系统性降低，且这种效应对于振荡（PSD）特征远大于事件相关（FRP）特征。这些发现表明，尽管脑电图模态存在固有噪声，现代语言模型表征在自然阅读过程中仍反映在EEG活动中，并且注意力的波动是脑-语言编码研究中一个被低估的变异性来源。

## Abstract
Encoding models offer a principled framework for linking computational representations of language to neural activity, but most electroencephalography (EEG) evidence for brain--language alignment comes from tightly controlled, word-by-word reading paradigms. Whether such alignment is detectable during naturalistic reading, and how it is affected by lapses in attention, remains unclear. We addressed these questions using ROAMM, a multimodal dataset containing simultaneous EEG and eye-tracking recordings with time-resolved mind-wandering (MW) annotations from 44 participants reading naturalistic texts. Ridge regression encoding models were trained to predict fixation-aligned EEG spectral power and fixation-related potentials (FRPs) from five word-embedding models (GloVe, word2vec, BERT, GPT-2, and Llama 3). Using permutation testing with false discovery rate correction, we found statistically reliable brain--language alignment across both feature types, with contextual embeddings outperforming static embeddings. Spectral alignment was strongest in the alpha and low-beta bands over parietal electrodes, while FRP-based alignment peaked 200--300 ms after fixation onset over central and parietal-occipital regions. Leveraging ROAMM's span-level MW annotations, we further show that brain--language alignment is systematically reduced during MW, an effect that was substantially larger for oscillatory (PSD) than for event-related (FRP) features. These findings demonstrate that modern language-model representations are reflected in EEG activity during naturalistic reading despite the modality's inherent noise, and that fluctuations in attention constitute an underappreciated source of variability in brain--language encoding studies.

---

## 论文详细总结（自动生成）

# 论文总结：自然阅读中的脑-语言对齐及其受心智游移的干扰

> 说明：由于提供的 PDF 全文未能成功提取，以下总结基于论文摘要、元数据及 TLDR 信息。若需更精确的数值与细节，建议获取完整原文。

## 1. 论文的核心问题与整体含义

- **研究动机与背景**：
  - 编码模型为将语言计算表征与神经活动联系起来提供了原则性框架。
  - 已有脑-语言对齐的 EEG 证据大多来自严格控制的逐词阅读范式，缺乏自然阅读场景下的验证。
  - 自然阅读更接近真实语言加工，但 EEG 信号噪声更大，因此“自然阅读中是否存在可靠的脑-语言对齐”尚未明确。
  - 注意力波动（尤其是心智游移，mind-wandering）如何干扰脑-语言对齐，也是该领域中被忽视的问题。

- **整体含义**：
  - 本研究试图回答：在自然阅读中，现代语言模型表征能否从 EEG 活动中被检测到；以及心智游移如何改变这种对齐。
  - 其意义在于证明即使在自然、嘈杂的阅读条件下，EEG 仍能捕捉语言表征信息；同时提示注意力状态是编码研究中一个重要的、但被低估的变异性来源。

## 2. 论文提出的方法论

- **核心思想**：
  - 使用岭回归编码模型，将词嵌入表征映射到注视对齐的 EEG 特征上。
  - 比较不同词嵌入模型对 EEG 活动的预测能力，以检测脑-语言对齐。
  - 利用时间分辨的心智游移注释，检验注意力状态对对齐程度的调节作用。

- **关键技术细节**：
  - **词嵌入模型**：使用五种模型，覆盖静态嵌入与上下文嵌入：
    - 静态：GloVe、word2vec
    - 上下文 / 现代语言模型：BERT、GPT-2、Llama 3
  - **EEG 特征**：
    - 注视对齐的频谱功率（PSD）
    - 注视相关电位（FRPs）
  - **编码模型**：
    - 岭回归（ridge regression）从词嵌入预测 EEG 特征。
    - 通过置换检验（permutation testing）建立显著性基准。
    - 使用错误发现率（FDR）校正多重比较。

- **算法流程（文字描述）**：
  1. 提取自然阅读过程中每个注视对应的 EEG 信号。
  2. 分别计算注视锁时的频谱功率和注视相关电位。
  3. 对每个词获取五种词嵌入向量。
  4. 训练岭回归模型，以词嵌入为输入，以 EEG 特征为输出。
  5. 使用置换检验获得零分布，判断预测性能是否显著高于随机水平。
  6. 比较不同嵌入、不同频段、不同时间窗、不同脑区的对齐强度。
  7. 根据心智游移注释，将注视划分为正常注意状态与心智游移状态，分别比较模型预测表现。

## 3. 实验设计

- **数据集 / 场景**：
  - 使用 **ROAMM 数据集**。
  - 包含 **44 名参与者**。
  - 同时采集 **EEG 和眼动追踪**。
  - 阅读材料为自然文本。
  - 具有 **时间分辨的心智游移（MW）注释**，即记录阅读过程中注意力涣散的时段。

- **Benchmark 与对比方法**：
  - 对比静态词嵌入与上下文词嵌入：GloVe、word2vec vs. BERT、GPT-2、Llama 3。
  - 对比两类 EEG 特征：频谱功率（PSD）与注视相关电位（FRP）。
  - 对比不同频段、不同时间窗、不同脑区上的对齐强度。
  - 对比心智游移状态与非心智游移状态下的脑-语言对齐。
  - 统计基准来自置换检验 + FDR 校正。

## 4. 资源与算力

- 根据目前提供的摘要和元数据，**未明确说明**使用的 GPU 型号、数量、训练时长或总计算资源。
- 由于研究采用岭回归编码模型，且样本规模为 44 名被试的自然阅读 EEG 数据，计算量可能相对可控；但具体算力信息需查阅原文。

## 5. 实验数量与充分性

- **大致实验覆盖范围**：
  - 5 种词嵌入模型。
  - 2 类 EEG 特征：频谱功率和注视相关电位。
  - 多种频段、时间窗和脑区分析。
  - 正常注意 vs. 心智游移的对比。
  - 置换检验 + FDR 多重比较校正。

- **充分性与客观性评价**：
  - 设计上覆盖了静态与上下文嵌入、振荡与事件相关特征、注意力状态调节，维度较为全面。
  - 统计检验采用置换检验和 FDR 校正，对多重比较控制较严谨。
  - 使用自然阅读和同步眼动追踪，生态效度较高。
  - 但由于当前仅有摘要，无法判断是否存在更多消融实验、控制分析或跨数据集验证。
  - 整体看，核心实验设计较充分；但概括性和可复现性仍需原文补充。

## 6. 论文的主要结论与发现

- 在自然阅读中，EEG 活动存在 **统计上可靠的脑-语言对齐**。
- **上下文嵌入（BERT、GPT-2、Llama 3）优于静态嵌入（GloVe、word2vec）**，说明语言模型的上下文表征与大脑语言加工更一致。
- 对齐的时间-空间-频段特征：
  - 频谱对齐在 **顶叶电极** 的 **alpha 和低 beta 频段** 最强。
  - FRP 对齐在 **注视开始后 200–300 ms**，于 **中央和顶枕区** 达到峰值。
- **心智游移显著降低脑-语言对齐**。
- 心智游移对 **振荡特征（PSD）** 的影响远大于对 **事件相关特征（FRP）** 的影响。
- 总体结论：
  - 尽管 EEG 模态存在固有噪声，现代语言模型表征仍能在自然阅读过程中被检测到。
  - 注意力波动是脑-语言编码研究中一个重要的、被低估的变异性来源。

## 7. 优点

- **生态效度高**：使用自然阅读文本和同时眼动追踪，比逐词呈现范式更接近真实语言加工。
- **多模态数据**：同步 EEG 与眼动记录，可以精确对齐注视与神经活动。
- **模型对比全面**：同时纳入静态嵌入与现代上下文语言模型，能够检验上下文表征的增量价值。
- **特征类型丰富**：同时分析频谱功率和注视相关电位，覆盖振荡与事件相关两类神经信号。
- **关注注意力状态**：利用 ROAMM 的时间分辨心智游移注释，直接量化注意力波动对脑-语言对齐的影响，具有新颖性。
- **统计严谨性**：使用置换检验 + FDR 校正，降低假阳性风险。

## 8. 不足与局限

- **数据集单一**：仅使用 ROAMM 一个数据集，结果的外推性和跨数据集泛化性尚未验证。
- **样本规模有限**：44 名被试虽然不算小，但对个体差异、跨语言/跨材料效应的检验能力可能有限。
- **具体数值缺失**：当前摘要未提供效应量、具体统计值、编码模型性能等，限制了对结果强度的判断。
- **因果推断限制**：编码模型是相关性分析，不能说明语言表征与 EEG 活动之间的因果方向。
- **心智游移注释可靠性**：时间分辨的 MW 注释可能受主观报告影响，存在噪声或偏差。
- **自然阅读伪迹问题**：自然阅读伴随眼动、眨眼和肌电活动，EEG 预处理和伪迹去除策略是否充分尚不清楚。
- **算力信息缺失**：未说明训练资源与计算可行性细节。
- **未充分展示局限控制**：摘要未提到是否控制阅读难度、词频、词长、句法复杂度等潜在混淆变量。

（完）
