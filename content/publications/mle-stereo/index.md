---
title: "MLG-Stereo: ViT Based Stereo Matching with Multi-Stage Local-Global Enhancement"
authors:
- Haoyu Zhang
- Jingyi Zhou
- Peng Ye
- Jiakang Yuan
- Lin Zhang
- Feng Xu
- Tao Chen
date: "2026-04-22T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "With the development of deep learning, ViT-based stereo matching methods have made significant progress due to their remarkable robustness and zero-shot ability. However, due to the limitations of ViTs in handling resolution sensitivity and their relative neglect of local information, the ability of ViT-based methods to predict details and handle arbitrary-resolution images is still weaker than that of CNN-based methods. To address these shortcomings, we propose MLG-Stereo, a systematic pipeline-level design that extends global modeling beyond the encoder stage. First, we propose a Multi-Granularity Feature Network to effectively balance global context and local geometric information, enabling comprehensive feature extraction from images of arbitrary resolution and bridging the gap between training and inference scales. Then, a Local-Global Cost Volume is constructed to capture both locally-correlated and global-aware matching information. Finally, a Local-Global Guided Recurrent Unit is introduced to iteratively optimize the disparity locally under the guidance of global information. Extensive experiments are conducted on multiple benchmark datasets, demonstrating that our MLG-Stereo exhibits highly competitive performance on the Middlebury and KITTI-2015 benchmarks compared to contemporaneous leading methods, and achieves outstanding results in the KITTI-2012 dataset."
summary: "Unlocking the full potential of ViT-based stereo matching."
tags:
  - Stereo Matching
  - Vision Foundation Models
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/pdf/2604.20393
---
