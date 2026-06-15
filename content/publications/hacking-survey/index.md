---
title: "Reward Hacking in the Era of Large Models: Mechanisms, Emergent Misalignment, Challenges"
authors:
- Xiaohua Wang∗
- Muzhao Tian∗
- Yuqi Zeng∗
- Zisu Huang∗
- Jiakang Yuan∗
- Bowen Chen∗
- Jingwen Xu∗
- Mingbo Zhou∗
- Wenhao Liu
- Muling Wu
- Zhengkang Guo
- Qi Qian
- Yifei Wang
- Feiran Zhang
- Ruicheng Yin
- Shihan Dou
- Changze Lv
- Tao Chen
- Kaitao Song
- Xu Tan
- Tao Gui
- Xiaoqing Zheng
- Xuanjing Huang
date: "2026-04-15T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "Reinforcement Learning from Human Feedback (RLHF) and related alignment paradigms have become central to steering large language models (LLMs) and multimodal large language models (MLLMs) toward human-preferred behaviors. However, these approaches introduce a systemic vulnerability: reward hacking, where models exploit imperfections in learned reward signals to maximize proxy objectives without fulfilling true task intent. As models scale and optimization intensifies, such exploitation manifests as verbosity bias, sycophancy, hallucinated justification, benchmark overfitting, and, in multimodal settings, perception--reasoning decoupling and evaluator manipulation. Recent evidence further suggests that seemingly benign shortcut behaviors can generalize into broader forms of misalignment, including deception and strategic gaming of oversight mechanisms. In this survey, we propose the Proxy Compression Hypothesis (PCH) as a unifying framework for understanding reward hacking. We formalize reward hacking as an emergent consequence of optimizing expressive policies against compressed reward representations of high-dimensional human objectives. Under this view, reward hacking arises from the interaction of objective compression, optimization amplification, and evaluator--policy co-adaptation. This perspective unifies empirical phenomena across RLHF, RLAIF, and RLVR regimes, and explains how local shortcut learning can generalize into broader forms of misalignment, including deception and strategic manipulation of oversight mechanisms. We further organize detection and mitigation strategies according to how they intervene on compression, amplification, or co-adaptation dynamics. By framing reward hacking as a structural instability of proxy-based alignment under scale, we highlight open challenges in scalable oversight, multimodal grounding, and agentic autonomy."
summary: "System review of reward hacking. "
tags:
  - Agentic AI
  - Reinforcement Learning
  - Reward Hacking
category: "LLM & Agent"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2604.13602"
  - type: code
    url: "https://github.com/xhwang22/Awesome-Reward-Hacking"
---
