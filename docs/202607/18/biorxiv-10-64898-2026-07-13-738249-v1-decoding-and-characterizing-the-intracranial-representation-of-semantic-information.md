---
title: Decoding and Characterizing the Intracranial Representation of Semantic Information
title_zh: 语义信息颅内表征的解码与特征描述
authors: "Smith, C., Inchyna, S., Barrentine, B., Nelson, M. J."
date: 2026-07-15
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.13.738249v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 从经历语义加工任务的sEEG局部场电位中提取高伽马功率
tldr: "脑机接口在解码运动/发音信号上进步显著，但高层语义信息能否从皮层活动中解码尚不清楚。本研究利用sEEG记录患者执行语义任务时的颅内神经活动，从局部场电位提取高gamma功率作为特征，通过监督机器学习进行单试次分类。结果显示，15个语义类别的平均分类准确率达29.8%，远超随机水平。该发现证明了颅内群体记录中可获取语义信息，为概念驱动的语言脑机接口和分布式语言网络机制研究提供了新方向。"
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-13-738249-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1235, \"height\": 1127, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-13-738249-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1027, \"height\": 1011, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-13-738249-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1139, \"height\": 1114, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-13-738249-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1534, \"height\": 1586, \"label\": \"Figure\"}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-13-738249-v1/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1336, \"height\": 1100, \"label\": \"Table\"}]"
motivation: 揭示高层语义信息能否从颅内皮层活动中解码，弥补BCI在概念层面研究的不足。
method: 对sEEG记录的局部场电位提取高gamma功率，构建单试次特征，采用监督机器学习进行语义分类。
result: "15类语义分类平均准确率29.8%，显著高于随机水平6.7%，证实高gamma活动编码了语义类别信息。"
conclusion: 语义信息可从颅内神经群体活动中解码，为概念驱动的语言BCI提供了可行性证据，并有助于理解分布式语义表征。
---

## 摘要
脑机接口（BCIs）通过解码与言语产生相关的运动和发音信号，已取得令人瞩目的性能。然而，对于是否能从人类皮层活动中解码出更高层次的语义表征，我们知之甚少。展示语义解码将促进我们对语言组织的理解，并推动依赖概念信息而非纯粹发音信息的脑机接口的发展。我们记录了因临床癫痫监测而接受立体定向脑电图（sEEG）的患者在执行需要语义处理的语言任务时的颅内神经活动。从局部场电位中提取高γ功率，用于生成试次级别的特征，以进行监督机器学习分类。分类性能通过交叉验证进行评估。语义类别信息被显著解码，高于随机水平，在15个语义类别中的平均分类准确率达到29.8%（随机水平为6.7%）。这些发现表明，高γ活动包含有关概念类别归属的信息，这些信息可在单个试次上被提取。这些结果提供了证据，表明语义信息可以从颅内群体记录中获取，并支持语义解码作为未来语言脑机接口的一个互补方向的可行性。除了神经假体应用，这项工作有助于理解概念知识如何在分布式人类语言网络中表征。

## Abstract
Brain-computer interfaces (BCIs) have achieved impressive performance by decoding motor and articulatory signals associated with speech production. However, considerably less is known about whether higher-level semantic representations can be decoded from human cortical activity. Demonstrating semantic decoding would advance both our understanding of language organization and the development of BCIs that rely on conceptual rather than purely articulatory information. We recorded intracranial neural activity from patients undergoing stereotactic electroencephalography (sEEG) for clinical epilepsy monitoring while they performed language tasks requiring semantic processing. High-gamma power was extracted from local field potentials and used to generate trial-level features for supervised machine-learning classification. Classification performance was evaluated using cross-validation. Semantic category information was decoded significantly above chance, with mean classification accuracy reaching 29.8% across 15 semantic categories (chance = 6.7%). These findings demonstrate that high-gamma activity contains information about conceptual category membership that can be extracted on individual trials. These results provide evidence that semantic information is accessible from intracranial population recordings and support the feasibility of semantic decoding as a complementary direction for future language BCIs. Beyond neuroprosthetic applications, this work contributes to understanding how conceptual knowledge is represented in the distributed human language network.