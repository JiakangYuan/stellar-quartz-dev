---
title: "Segment-Aligned Policy Optimization for Multi-Modal Reasoning"
authors:
- Lei Gao
- Zhuoming Li
- Mengxi Jia
- Jiakang Yuan
- Hongbo Sun
- Hao Sun
- Xuelong Li
date: "2026-05-07T00:00:00Z"
publication_types: ['paper-conference']
publication: "ICML 2026"
publication_short: "ICML 2026"
abstract: "Existing reinforcement learning approaches for Large Language Models typically perform policy optimization at the granularity of individual tokens or entire response sequences. However, such formulations often misalign with the natural step-wise structure of reasoning processes, leading to suboptimal credit assignment and unstable training in multi-modal reasoning tasks. To bridge this gap, we propose Segment-Aligned Policy Optimization (SAPO), a novel reinforcement learning paradigm that treats coherent reasoning steps, rather than tokens or full sequences as fundamental units of policy update. SAPO introduces a step-wise Markov decision process abstraction over reasoning segments, accompanied by segment-level value estimation, advantage computation, and importance sampling mechanisms that are semantically aligned with reasoning boundaries. Experiments on representative reasoning benchmarks demonstrate that SAPO consistently outperforms token-level and sequence-level policy optimization methods, achieving significant accuracy improvements while exhibiting better training stability and value estimation consistency. Our work underscores the importance of aligning reinforcement learning updates with the intrinsic structure of reasoning, paving the way for more efficient and semantically grounded policy optimization in complex reasoning tasks. Codes and models will be released to ensure full reproducibility."
summary: "A comprehensive benchmark specifically designed to evaluate the reasoning capability of MLLMs."
tags:
  - Multimodal LLM
  - Reinforcement Learning
category: "LLM & Agent"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/pdf/2505.21327
  - type: code
    url:  https://github.com/Graysonicc/SAPO
---
