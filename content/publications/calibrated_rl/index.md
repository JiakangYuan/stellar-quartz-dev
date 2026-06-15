---
title: "From Static Context to Calibrated Interactive RL: Mitigating Distribution Shift in Multi-turn Dialogue with Aligned Simulator"
authors:
- Xiaohua Wang*
- Jiakang Yuan*
- Zisu Huang
- Muzhao Tian
- Changze Lv
- Kaitao Song
- Tao Chen
- Xiaoqing Zheng

date: "2026-05-27T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "A long-standing goal of the research community is to develop highly interactive LLM-based dialogue agents. Recent research focuses on optimizing policies based on fixed offline logs (Static Context RL) or using a prompt-based simulator (Interactive RL). In this work, we theoretically show that both paradigms are fundamentally limited by context distribution shift--a mismatch between dialogue histories observed during training and those encountered in real conversations. This shift compounds quadratically over turns and severely degrades dialogue quality. Specifically, we attribute this shift to two distinct sources: (i) policy-induced shift, arising from training on static histories rather than self-generated trajectories; and (ii) simulator-induced shift, stemming from discrepancies between simulated and real human behaviors. To address these challenges, we propose Calibrated Interactive RL, a unified framework that couples interactive RL with simulator alignment. By aligning the simulator with human interaction patterns, our approach reduces the sim-to-real gap and mitigates compounding distribution shifts. Experiments across multiple dialogue tasks confirm our theoretical analysis: (i) Interactive RL significantly outperforms the Static Context baseline by mitigating policy distribution shift; and (ii) calibrating simulators with our alignment method further bridges the sim-to-real gap, yielding state-of-the-art downstream performance."
summary: "Graph-search-based end-to-end MLE task solver."
tags:
  - Agentic AI
  - Distribution Shift
category: "LLM & Agent"
featured: true
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2605.26403"
---
