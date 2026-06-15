---
title: "Consistency-aware Self-Training for Iterative-based Stereo Matching"
authors:
- Jingyi Zhou*
- Peng Ye*
- Haoyu Zhang
- Jiakang Yuan (Project Leader)
- Qiang Rao
- YangChenXu Liu
- Cailin Wu
- Feng Xu
- Tao Chen
date: "2025-02-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "CVPR 2025"
publication_short: "CVPR 2025"
abstract: "Iterative-based methods have become mainstream in stereo matching due to their high performance. However, these methods heavily rely on labeled data and face challenges with unlabeled real-world data. To this end, we propose a consistency-aware self-training framework for iterativebased stereo matching for the first time, leveraging realworld unlabeled data in a teacher-student manner. We first observe that regions with larger errors tend to exhibit more pronounced oscillation characteristics during model prediction. Based on this, we introduce a novel consistencyaware soft filtering module to evaluate the reliability of teacher-predicted pseudo-labels, which consists of a multiresolution prediction consistency filter and an iterative prediction consistency filter to assess the prediction fluctuations of multiple resolutions and iterative optimization respectively. Further, we introduce a consistency-aware softweighted loss to adjust the weight of pseudo-labels accordingly, relieving the error accumulation and performance degradation problem due to incorrect pseudo-labels. Extensive experiments demonstrate that our method can improve the performance of various iterative-based stereo matching approaches in various scenarios. In particular, our method can achieve further enhancements over the current SOTA methods on several benchmark datasets."
summary: "CST-Stereo achieves impressive results in various scenarios including in-domain, domain adaptive and domain generalization."
tags:
  - Stereo Matching
  - Self-Training
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/abs/2503.23747
---
