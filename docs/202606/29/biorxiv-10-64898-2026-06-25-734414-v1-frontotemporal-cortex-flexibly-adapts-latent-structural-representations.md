---
title: Frontotemporal cortex flexibly adapts latent structural representations
title_zh: 额颞叶皮层灵活适应潜在结构表征
authors: "Tertikas, G., Trudel, N., Klein-Flugge, M., Hauser, T. U."
date: 2026-06-28
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.25.734414v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 9.0
evidence: 前内侧额叶皮层（amFC，属mPFC）编码新推断的关联，显示mPFC在灵活结构表征中的核心作用
tldr: 人类通过形成抽象结构表征灵活导航复杂环境，但大脑如何动态重构这些内部模型仍不清楚。本研究使用新型推理任务与fMRI重复抑制，发现内侧眶额皮层（mOFC）编码稳定关系，变化触发海马与前额叶暂态表征；新推断关联由前内侧额叶（amFC）编码并迁移至mOFC，过时关联则暂态激活额极皮层和海马，海马保留记忆痕迹。早期新异信号强度可预测个体行为适应差异，揭示了人脑自适应结构重构机制，对理解精神疾病认知僵化有重要意义。
source: biorxiv
selection_source: fresh_fetch
motivation: 旨在揭示大脑动态重构内部模型以灵活适应隐蔽层次结构变化的机制。
method: 采用新颖推理任务与fMRI重复抑制范式，考察结构变化时的神经表征动态。
result: mOFC编码稳定知识；海马和前额叶编码变化暂态表征；新关联由amFC迁移至mOFC；过时关联由额极和海马处理，海马保留记忆；早期信号预测行为适应。
conclusion: 大脑通过额叶-海马系统动态重构结构表征，新知识从amFC迁移至mOFC固化，过时知识由海马暂留，这为理解认知灵活性与僵化提供神经基础。
---

## 摘要
人类擅长通过形成可随环境变化灵活更新的抽象结构表征来应对复杂环境。本研究考察大脑如何动态重构这些内部模型以应对潜在层级结构的隐蔽变化。利用新颖的推理任务和fMRI重复抑制技术，我们发现，稳定的关系知识编码于内侧眶额皮层（mOFC），而结构变化则在海马和前额叶区域触发短暂表征。新推测的关联首先编码于前内侧额叶皮层（amFC），随后在稳定时腹侧迁移至mOFC。相比之下，过时的关联短暂地调动额极皮层和海马，其中海马而非前额区域保留了残余记忆痕迹。值得注意的是，amFC和海马的早期新信号强度与个体在行为适应上的差异相关。综合来看，这些结果揭示了支持人脑适应性结构重构的机制，对理解精神疾病中的认知僵化具有启示意义。

## Abstract
Humans excel at navigating complex environments by forming abstract structural representations that can be flexibly updated when environments change. Here, we examine how the brain dynamically reconfigures these internal models in response to covert changes in latent hierarchies. Using a novel inference task and fMRI repetition suppression, we find that stable relational knowledge is encoded in medial orbitofrontal cortex (mOFC), while structural changes trigger transient representations across hippocampal and prefrontal regions. Newly inferred associations are first encoded in anterior medial frontal cortex (amFC) and migrate ventrally to mOFC when settling. In contrast, outdated associations transiently engage frontopolar cortex and hippocampus, with the hippocampus, but not frontal areas, retaining a residual memory trace. Notably, the strength of early novel signals in amFC and hippocampus tracks individual differences in behavioural adaptation. Together, these results characterise mechanisms supporting adaptive structural reconfiguration in the human brain, with implications for cognitive inflexibility in psychiatric disorders.

---

## 论文详细总结（自动生成）

以下是基于给定论文的详细中文总结，按指定要点分层展开：

---

### 1. 论文的核心问题与整体含义

- **研究动机**：人类能形成抽象的结构表征（认知地图），并以此灵活应对环境变化。但在充满隐蔽（隐性）变化的动态世界中，大脑如何在不依赖显式提示的情况下，动态地更新这些内部模型，尚不清楚。
- **核心问题**：大脑（特别是额叶-海马网络）如何在潜在的层级结构发生“隐蔽变化”时，灵活地适应并重组其神经表征。
- **整体含义**：揭示大脑支持适应性结构重构的时空动态机制，为理解精神疾病（如强迫症）中常见的认知僵化提供神经层面的解释框架。

### 2. 方法论

- **核心思想**：利用 **fMRI重复抑制（Repetition Suppression, RS）** 原理，即当两个刺激在神经表征上关联时，对第二个刺激的神经响应会减弱。通过测量不同结构关系（稳定、新异、过时）刺激对之间的BOLD信号变化，间接推断它们的神经表征重叠程度。
- **关键技术细节**：
    - **任务设计**：设计了一种**三层级结构推理任务**。被试学习两个隐含三层级关系的结构（第一层/预测物 -> 中间层 -> 第三层/产物）。任务中，部分第一层或第三层的对象会在结构之间发生“隐蔽交换”（变更点），被试需通过有限反馈推断出新结构。
    - **范式**：任务包含两种块：(1) **选择块（Choice Blocks, CBs）**：被试判断展示的预测物-产物对是否属于同一结构，部分试次获得反馈；(2) **抑制块（Suppression Blocks, SBs）**：伪随机呈现所有结构中的刺激对，用于测量重复抑制效应。
    - **分析逻辑**：根据最近一次变更点，将SBs中的刺激对分为四类：**稳定对**（变更前后均关联）、**新异对**（仅在变更后关联）、**过时对**（仅在变更前关联）、**无关对**（从不关联）。通过对比这些类别来追踪表征的涌现、维持与消退。
    - **数据处理**：使用基于FSL的标准GLM分析，结合先验ROI（海马、mOFC、FP、amFC）的TFCE校正和全脑分析。

### 3. 实验设计

- **数据集/被试**：51名神经及精神健康的成年人（年龄 25.6 ± 5.6岁，23名男性），从124名完成在线筛选的人中选出。被试皆完成在线预训和MRI扫描两个阶段。
- **场景（任务）**：基于上述三层级结构推理任务，在MRI扫描仪内完成。
- **Benchmark（对比基准）**：
    - **神经表征基准**：以**无关对**作为基线，测量其他配对类型相对于它的信号降低（表征重叠增强）。
    - **时间进程对比**：分析变更点前（SB-1）、变更点后第一个块（SB+1）和第二个块（SB+2）表征的动态变化。
    - **行为-神经关联**：以基于行为适应速度**中位数划分的高、低表现组**为对比对象，考察其在新异刺激处理上的神经活动差异。
- **对比的方法/区域**：在额叶-海马网络内，系统对比了**稳定 vs. 新异 vs. 过时**等不同表征状态在**mOFC、amFC、FP和海马（前/后部）** 等子区域的时空活动模式。

### 4. 资源与算力

- **本文未明确提及**使用的GPU型号、数量或总训练时长。
- 所有分析均基于已成熟的神经影像数据处理软件（如FSL FEAT, FLAME, TFCE），计算资源消耗符合标准的fMRI组分析范式，文中未将其作为评估重点。

### 5. 实验数量与充分性

- **实验组数概览**：
    - **核心神经分析**：完成了一个**跨任务GLM**（考察稳定/新异/过时 vs. 无关/稳定对）和一个**变更聚焦GLM**（考察新异、过时对在SB-1, SB+1, SB+2的时间进程）。
    - **关键对比组**：至少包含4个以上的关键配对比对（如稳定>无关，新异>稳定，过时>稳定，新异/过时在时间点上的差异等）。
    - **补充与验证分析**：包括1个**行为-神经关联分析**（高 vs. 低表现者），以及将新异/过时信号与无关配对照的补充特异性分析。
    - **ROI与校正**：所有核心结果均在小体积校正（SVC）后的多个先验ROI内报告。
- **实验充分性与客观性**：
    - **充分**：实验设计精细，通过重复抑制范式，用有限的实验对比巧妙分离了表征的**稳定、形成、消解**三种状态，并追踪了其时空动态。行为-神经关联分析增强了结论的生理学意义。
    - **客观公平**：使用TFCE非参数校正，ROIs基于先验文献定义，分析流程透明，保证了统计的客观性。多种控制条件（无关对、稳定对）和补充分析确保了对比的公平性。

### 6. 主要结论与发现

- **稳定结构定位于mOFC**：稳定的层次关系被一致地表征在**内侧眶额皮层（mOFC）**。
- **新关联的动态迁移**：新推断的关联最初被编码于**前内侧额叶皮层（amFC）**，但随着结构稳定，其表征会**腹侧迁移至mOFC**，实现从暂态编码到稳固地图的整合。
- **过时关联的双重处理**：
    - **额极皮层（FP）** 对刚过时的关联表现出**短暂性**激活，可能参与重新评估。
    - **海马**对过时关联保留了**更持久的记忆痕迹**，即使其行为上已不再相关。且新、旧关联在海马前后轴上的表征存在分离（前部处理新异，后部处理过时）。
- **个体差异的神经基础**：在amFC和海马中对新异关联**响应更强的个体**，在行为上能**更快地从结构变化中恢复**，揭示了认知灵活性差异的神经预测因子。

### 7. 优点

- **高生态效度的任务设计**：巧妙结合“隐蔽变化”和“部分反馈”，迫使被试进行结构化推理和灵活更新，而不是简单的刺激-反应学习，更贴近真实世界的复杂认知需求。
- **创新性的分析方法**：将重复抑制范式应用于追踪**抽象结构表征的生命周期（形成、稳定、消解）**，实现了对心理模型动态重构过程的在体测量。
- **时空动态的精细描绘**：不仅定位了不同表征状态的脑区，更有价值地揭示了**表征在不同脑区之间迁移（如新关联从amFC到mOFC的腹侧迁移）** 和**不同脑区对同一事件的不同时间反应模式（如FP的短暂激活与海马的持续表征）**。
- **明确的前后轴分工**：提供了海马长轴功能分化的新证据，阐明前部海马更多参与新异结构绑定，而后部海马则保留个体化、精确的过去记忆痕迹。

### 8. 不足与局限

- **实验覆盖与机制局限**：
    - **任务结构特异性**：结论建立于特定的三层级树状结构任务，其推广到其他类型的抽象结构（如社会网络、环形空间结构）上尚需验证。
    - **因果推断缺失**：fMRI提供了相关性的证据，但无法证明观察到的脑区活动是认知重构的“原因”还是“结果”。未来需结合干扰性技术（如TMS）。
- **偏差风险**：
    - **样本偏差**：被试主要为大学生群体，年龄范围和认知水平相对集中，可能无法完全代表普通人群，在临床转化前需验证。
    - **关注偏差**：研究仅在SBs中分析表征，可能遗漏了在反馈和选择阶段发生的即时加工过程。
- **应用限制**：虽然指出了与精神疾病认知僵化的潜在关联，但本次研究并未在患者群体中进行，其临床预测价值（如对治疗反应的预测）仅停留在假说阶段。

（完）
