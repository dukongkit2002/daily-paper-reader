---
title: "BCCWJ-Brain: A Multi-Modal fMRI, MEG, and EEG Dataset of Naturalistic Japanese Reading"
title_zh: BCCWJ-Brain：一个自然日语阅读的多模态fMRI、MEG和EEG数据集
authors: "Sugimoto, Y., Asahara, M., Jeong, H., Kanno, A., Koizumi, M., Oseki, Y."
date: 2026-07-09
pdf: "https://www.biorxiv.org/content/10.64898/2026.07.05.736621v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 7.0
evidence: 提供自然阅读任务的EEG数据集，可用于认知任务中的相对功率谱分析
tldr: 自然语言处理的人脑机制探索离不开多模态神经成像数据，但针对日语自然阅读的多模态数据集一直缺失，严重制约了跨语言计算模型比较和脑语言解码研究。BCCWJ-Brain数据集为此构建，招募112名日语母语者分为三组（fMRI 36人、MEG 35人、EEG 41人），在RSVP范式下阅读源自《当代日语书面语均衡语料库》的20篇报纸文章，分别采集了高空间分辨率fMRI和高时间分辨率MEG、EEG信号。由于采用完全相同的自然阅读刺激，该数据集实现了三种模态的有效对齐，为评估大语言模型等计算的脑预测能力提供了关键基准。所有数据已通过OpenNeuro平台开放获取，预期将有力推动认知计算神经科学与自然语言处理的交叉融合研究。
source: biorxiv
selection_source: fresh_fetch
figures_json: "[{\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/fig-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1818, \"height\": 1312, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/fig-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1643, \"height\": 360, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/fig-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1606, \"height\": 539, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/fig-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1575, \"height\": 833, \"label\": \"Figure\"}, {\"url\": \"assets/figures/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/fig-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1575, \"height\": 834, \"label\": \"Figure\"}]"
tables_json: "[{\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/table-001.webp\", \"caption\": \"\", \"page\": 0, \"index\": 1, \"width\": 1632, \"height\": 1332, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/table-002.webp\", \"caption\": \"\", \"page\": 0, \"index\": 2, \"width\": 1635, \"height\": 229, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/table-003.webp\", \"caption\": \"\", \"page\": 0, \"index\": 3, \"width\": 1614, \"height\": 1753, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/table-004.webp\", \"caption\": \"\", \"page\": 0, \"index\": 4, \"width\": 1639, \"height\": 249, \"label\": \"Table\"}, {\"url\": \"assets/tables/biorxiv/biorxiv-10-64898-2026-07-05-736621-v1/table-005.webp\", \"caption\": \"\", \"page\": 0, \"index\": 5, \"width\": 1630, \"height\": 346, \"label\": \"Table\"}]"
motivation: 为给大语言模型等计算模型提供神经认知基准，急需相同自然阅读刺激下的多模态脑成像数据，但日语领域缺乏此类资源。
method: 招募112名日语母语者（fMRI 36人、MEG 35人、EEG 41人），以RSVP范式呈现BCCWJ的20篇报纸文章，分别记录三种模态的神经活动。
result: 构建了BCCWJ-Brain多模态神经影像数据集，包含相同刺激下的fMRI、MEG和EEG数据，已于OpenNeuro平台公开。
conclusion: 该数据集为评估计算模型的脑相似性提供了统一基准，将促进认知计算建模和脑语言解码研究。
---

## 摘要
我们呈现BCCWJ-Brain数据集，这是一个多模态神经影像资源，包含来自以日语为母语的受试者在阅读《现代书面日语平衡语料库》报纸文章时记录的功能性磁共振成像、脑磁图和脑电图数据。神经数据收集自112名参与者（36名fMRI，35名MEG，41名EEG），他们在快速序列视觉呈现范式下阅读二十篇报纸文章。通过提供在相同自然阅读刺激下收集的三种互补神经成像模态，该数据集为大型语言模型等计算模型提供了认知基准。该数据集在OpenNeuro平台上公开可用，为神经科学、自然语言处理和相关研究领域提供了宝贵资源。

## Abstract
We present the BCCWJ-Brain dataset, a multi-modal neuroimaging resource comprising functional magnetic resonance imaging (fMRI), magnetoencephalography (MEG), and electroencephalography (EEG) data recorded from native Japanese speakers reading newspaper articles from the Balanced Corpus of Contemporary Written Japanese (BCCWJ). Neural data were collected from 112 participants (36 fMRI, 35 MEG, and 41 EEG) as they read twenty newspaper articles presented in a Rapid Serial Visual Presentation (RSVP) paradigm. By providing three complementary neuroimaging modalities collected under identical naturalistic reading stimuli, this dataset provides a cognitive benchmark for computational models such as large language models. The dataset is publicly available on the OpenNeuro platform, offering a valuable resource for neuroscience, natural language processing, and related research fields.