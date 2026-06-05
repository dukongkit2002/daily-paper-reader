---
title: A spectral partial information decomposition framework for quantifying information about cognitive variables in oscillatory brain networks
title_zh: 量化振荡脑网络中认知变量信息的频谱部分信息分解框架
authors: "Lima Cordeiro, V., Marinazzo, D., Brovelli, A."
date: 2026-05-14
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.13.724846v1.full.pdf"
tags: ["query:cog-eeg-mpfc"]
score: 9.0
evidence: 引入谱部分信息分解框架，量化振荡脑网络中认知变量在功率和相位贡献中的信息
tldr: 神经振荡在编码认知信息中的作用机制尚不明确，尤其缺乏方法同时量化频域中相位和振幅的贡献及其交互。本文提出谱部分信息分解框架NeOPID，可量化功率和相位中的任务相关信息，并分解冗余与协同编码。在模拟和猕猴工作记忆数据上验证表明，β频段振幅共调制是主要信息载体，且高阶相位交互在记忆延迟期存在冗余与协同结构。该工具为深入理解振荡网络的信息架构提供了新途径。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有方法无法在频域同时量化相位同步和振幅共调制的认知信息贡献，以及高阶交互中的冗余和协同编码结构。
method: 提出一种谱部分信息分解框架NeOPID，可分离功率和相位中的信息成分，并量化成对及高阶脑网络关系中的冗余和协同信息。
result: 模拟验证准确恢复编码方案；在猕猴工作记忆LFP数据中，β频段振幅共调制是主要刺激信息载体，高阶相位交互展现冗余和协同结构。
conclusion: NeOPID为剖析振荡脑网络在认知过程中的信息架构提供了有原则的量化工具，揭示了相位和振幅的互补编码机制。
---

## 摘要
神经振荡被认为在大规模脑网络中编码和传递认知信息起着核心作用，但相位同步和振幅共调制对分布式编码的相对贡献仍不清楚。一个关键障碍是缺乏能够在频域中同时量化任务相关信息，并在成对及高阶交互中分离其相位和振幅成分的工具。在此，我们提出了一个频谱部分信息分解框架（命名为NeOPID），用于量化功率和相位贡献中关于认知变量的信息，并量化脑关系中的冗余和协同信息，从成对到高阶交互。我们在Kuramoto和Stuart-Landau振子网络上验证了该方法，包括受猕猴解剖连接约束的全脑模型。NeOPID准确地恢复了真实编码方案，并揭示了相位关系和振幅共调制作为具有冗余和协同成分的互补编码通道。NeOPID进一步将这种分解扩展到高阶功能交互，从而能够描述认知信息如何通过冗余和协同编码在多个振荡边上集体分布。为了展示生物学适用性，我们将NeOPID应用于猕猴额顶网络在工作记忆任务中记录的局部场电位。在该数据集中，NeOPID识别出β频段振幅共调制是刺激信息的主要载体，并揭示在记忆延迟期间高阶相位相互作用表现出冗余和协同结构。这些结果确立了NeOPID作为剖析振荡脑网络认知过程信息架构的原则性工具。

## Abstract
Neural oscillations are thought to play a central role in encoding and transmitting cognitive information across large-scale brain networks, yet the relative contributions of phase synchrony and amplitude co-modulations to distributed coding remain unclear. A key obstacle is the absence of tools that can simultaneously quantify task-relevant information in the frequency domain and disentangle its phase and amplitude components across pairwise and higher-order interactions. Here, we introduce a spectral partial information decomposition framework (named NeOPID) for quantifying information about cognitive variables in power and phase contributions, and to quantify redundant and synergistic information in brain relations, from pairwise to higher-order interactions. We validated the approach on Kuramoto and Stuart-Landau oscillator networks, including a whole-brain model constrained by macaque anatomical connectivity. NeOPID accurately recovers ground-truth encoding schemes and reveals that phase relations and amplitude co-modulations act as complementary coding channels with both redundant and synergistic components. NeOPID further extends this decomposition to higher-order functional interactions enabling the characterization of how cognitive information is collectively distributed across multiple oscillatory edges via redundant and synergistic encoding. To illustrate biological applicability, we applied NeOPID to local field potentials (LFPs) recorded from the macaque fronto-parietal network during a working memory task. In this dataset, NeOPID identified beta-band amplitude co-modulations as the primary carrier of stimulus information, and revealed that higher-order phase interactions exhibit both redundant and synergistic structure during the memory delay. These results establish NeOPID as a principled tool for dissecting the informational architecture about cognitive processes of oscillatory brain networks.