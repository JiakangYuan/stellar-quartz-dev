---
title: "Trust Your Instincts: Confidence-Driven Test-Time RL for Vision-Language-Action Models"
authors:
- Siyao Chen
- Jiakang Yuan
- Jiaxin Wang
- Tao Chen
date: "2026-07-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "ECCV 2026"
publication_short: "ECCV 2026"
abstract: "Reinforcement learning (RL) has become indispensable for pushing Vision-Language-Action Models (VLAs) beyond static imitation learning. However, existing RL methods typically require external environmental feedback, relying on predefined success signals to guide policy updates. In this work, we show that VLA models possess useful internal evaluative capabilities: in discrete-action VLAs, trajectories with higher generation confidence are significantly more likely to succeed. Based on this observation, we introduce T^2VLA (Test-time VLA), an architecture-agnostic test-time RL framework that enables VLA models to achieve self-bootstrapping policy improvement. Instead of relying on external rewards, T^2VLA leverages trajectory-level similarity to high-confidence expert demonstrations as an intrinsic reward signal. In addition, we propose a Confidence-Driven Dual Expert Bootstrapping mechanism, which dynamically balances a Local Pseudo-Expert for exploration and a Global Expert Pool for training stability. Extensive experiments on the LIBERO and RoboTwin benchmarks show that T^2VLA consistently outperforms supervised baselines and approaches oracle RL performance with ground-truth rewards, achieving effective improvement without external reward feedback. Furthermore, T^2VLA adapts to distinct VLA paradigms, including both OpenVLA-OFT and the pi series."
summary: "Test-time reinforcement learning for vision-language-action models."
tags:
  - embodied AI
  - Test-Time Learning
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2606.29892"
---
