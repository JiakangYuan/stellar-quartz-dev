---
title: "Chimera: Improving Generalist Model with Domain-Specific Experts"
authors:
- Tianshuo Peng*
- Mingsheng Li*
- Jiakang Yuan
- Hongbin Zhou
- Renqiu Xia
- Renrui Zhang
- Lei Bai
- Song Mao
- Bin Wang
- Aojun Zhou
- Botian Shi
- Tao Chen
- Bo Zhang
- Xiangyu Yue
date: "2025-06-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "ICCV 2025"
publication_short: "ICCV 2025"
abstract: "Recent advancements in Large Multi-modal Models (LMMs) underscore the importance of scaling by increasing image-text paired data, achieving impressive performance on general tasks. Despite their effectiveness in broad applications, generalist models are primarily trained on web-scale datasets dominated by natural images, resulting in the sacrifice of specialized capabilities for domain-specific tasks that require extensive domain prior knowledge. Moreover, directly integrating expert models tailored for specific domains is challenging due to the representational gap and imbalanced optimization between the generalist model and experts. To address these challenges, we introduce Chimera, a scalable and low-cost multi-modal pipeline designed to boost the ability of existing LMMs with domain-specific experts. Specifically, we design a progressive training strategy to integrate features from expert models into the input of a generalist LMM. To address the imbalanced optimization caused by the well-aligned general visual encoder, we introduce a novel Generalist-Specialist Collaboration Masking (GSCM) mechanism. This results in a versatile model that excels across the chart, table, math, and document domains, achieving state-of-the-art performance on multi-modal reasoning and visual content extraction tasks, both of which are challenging tasks for assessing existing LMMs."
summary: "A scalable and low-cost multi-modal pipeline to boost existing LMMs with domain-specific experts."
tags:
  - Multimodal LLM
  - Domain Experts
category: "LLM & Agent"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/abs/2412.05983
  - type: custom
    label: Project
    url: https://alpha-innovator.github.io/chimera_page/
---
