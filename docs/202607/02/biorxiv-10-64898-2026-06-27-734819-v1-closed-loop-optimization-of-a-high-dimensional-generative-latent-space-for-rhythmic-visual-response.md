---
title: Closed-loop optimization of a high-dimensional generative latent space for rhythmic visual response
title_zh: 用于节律性视觉反应的高维生成潜在空间的闭环优化
authors: "Livezey, J. A., Su, Y., Wolfer, S., Ingster, A., Klein, D. J., Hanina, A."
date: 2026-07-02
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.27.734819v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 6.0
evidence: 使用EEG测量稳态视觉诱发电位的相对功率
tldr: 神经振荡伴随多种认知过程，对其进行调制具有重要研究和临床价值，但传统闭环方法通常依赖侵入式记录，且偏重放电率而非节律性调制。本研究提出闭环优化高维生成潜在空间，以非侵入脑电图(EEG)测量的稳态视觉诱发电位(SSVEP)相对功率为目标，实时调整图像刺激参数。在alpha和theta频段，10、20、40维潜在空间均成功实现了节律功率的增强，优化刺激可泛化至新被试，并揭示了低频空间功率特征以相反方向驱动theta和alpha节律。该工作证明了闭环刺激优化作为非侵入性节律神经调制方法的可行性。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统闭环视觉神经调制依赖侵入式记录，且以最大化放电率为目标，缺乏对节律性响应的直接优化。
method: 采用非侵入EEG的SSVEP，在生成潜在空间中闭环优化图像刺激参数，以增强相对SSVEP功率。
result: 在alpha和theta频段，10、20、40维潜在空间成功调制节律功率，刺激泛化到新被试，且低频空间功率反向影响theta和alpha。
conclusion: 闭环刺激优化为非侵入性节律神经调制提供了新途径，具有广泛的应用潜力。
---

## 摘要
神经振荡伴随广泛的认知状态和行为，包括感知、记忆和运动，并且对它们的调制在基础神经科学和临床研究中日益受到关注。先前闭环调制视觉神经反应的演示主要依赖侵入式记录，并聚焦于最大化发放率而非节律性调制。在此，我们展示，使用易于获取的非侵入式脑电图测量的稳态视觉诱发电位（SSVEP）的相对功率，可以在闭环中作为图像刺激参数的函数，在单个参与者的单次实验中进行调制。在Alpha和Theta频段的闪烁频率下，刺激优化在10、20和40维潜在空间中均获成功。我们还证明，当在开环中展示时，优化后的刺激可泛化至新参与者。最后，我们刻画了调制相对SSVEP功率的视觉特征，并发现图像中的低频空间功率以相反方向驱动Theta和Alpha。总之，我们的结果表明，闭环刺激优化是一种使用非侵入式神经成像方法进行节律性神经调制的可行方法。

## Abstract
Neural oscillations accompany a wide range of cognitive states and behaviors including perception, memory, and movement, and modulating them is of growing interest for both basic neuroscience and clinical research. Previous demonstrations of closed-loop modulation of visual neural responses mainly relied on invasive recordings and focused on firing-rate maximization rather than rhythmic modulation. Here, we show that the relative power of steady-state visual evoked response (SSVEP), measured with readily-available, non-invasive electroencephalography, can be modulated in closed-loop as a function of image stimulus parameters for single participants within a single session. Stimulus optimization with flicker frequencies in the alpha and theta bands was successful in 10, 20, and 40 dimensional latent spaces. We also show that optimized stimuli generalize to new participants when shown in open-loop. Finally, we characterize the visual features that modulate relative SSVEP power and find that low-frequency spatial power in the image drives theta and alpha in opposite directions. Together, our results show that closed-loop stimulus optimization is a viable method for rhythmic neural modulation using noninvasive neuroimaging methods.