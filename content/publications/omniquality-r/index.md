---
title: "Omniquality-R: Advanced Reward Models through All-Encompassing Quality Assessment"
authors:
- Yiting Lu
- Fengbin Guan
- Yixin Gao
- Yan Zhong
- Xinge Peng
- Jiakang Yuan
- Yihao Liu
- Bo Zhang
- Xin Li
- Zhibo Chen
- Weisi Lin
date: "2025-10-12T00:00:00Z"
publication_types: ['paper-conference']
publication: "ICML 2026"
publication_short: "ICML 2026"
abstract: "Current visual evaluation approaches are typically constrained to a single task. To address this, we propose OmniQuality-R, a unified reward modeling framework that transforms multi-task quality reasoning into continuous and interpretable reward signals for policy optimization. Inspired by subjective experiments, where participants are given task-specific instructions outlining distinct assessment principles prior to evaluation, we propose OmniQuality-R, a structured reward modeling framework that transforms multi-dimensional reasoning into continuous and interpretable reward signals. To enable this, we construct a reasoning-enhanced reward modeling dataset by sampling informative plan-reason trajectories via rejection sampling, forming a reliable chain-of-thought (CoT) dataset for supervised fine-tuning (SFT). Building on this, we apply Group Relative Policy Optimization (GRPO) for post-training, using a Gaussian-based reward to support continuous score prediction. To further stabilize the training and improve downstream generalization, we incorporate standard deviation (STD) filtering and entropy gating mechanisms during reinforcement learning. These techniques suppress unstable updates and reduce variance in policy optimization. We evaluate OmniQuality-R on three key IQA tasks: aesthetic quality assessment, technical quality evaluation, and text-image alignment."
summary: "A unified reward modeling framework that transforms multi-task quality reasoning into continuous and interpretable reward signals ."
tags:
  - Image Quality Assesment
  - Reinforcement Learning
category: "Others"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2510.10609"
  - type: code
    url: "https://github.com/yeppp27/OmniQuality-R"
  - type: dataset
    url: "https://huggingface.co/yeeeeeyy/OmniQuality-R"
---
