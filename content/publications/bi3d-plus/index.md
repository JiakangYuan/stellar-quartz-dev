---
title: "Bi3D++: Hybrid Bi-domain Active Learning for Cross-domain 3D Object Detection"
authors:
- Jiakang Yuan
- Xiangchao Yan
- Botian Shi
- Bo Zhang
- Feng Xu
- Yu Qiao
- Tao Chen
date: "2026-02-01T00:00:00Z"
publication_types: ['article-journal']
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence (T-PAMI) 2026"
publication_short: "T-PAMI 2026"
abstract: "Domain adaptation has been widely explored in 3D detection tasks recently. Previous works mainly use unsupervised domain adaptation (UDA) techniques to deal with domain discrepancies. Despite large improvements, the performance still largely falls behind the model trained on the fully annotated target domain which is because of the larger domain discrepancies caused by different sensors and changing surrounding environments. In this paper, we fully exploit the characteristics in autonomous driving scenarios (i.e., similar scenes and class-imbalance distribution) and explore a new task, named active domain adaptation (ADA) in 3D object detection which selects partial-yet-important target data and annotates them to further improve the performance on the target domain. To this end, we propose a hybrid bi-domain active learning strategy, namely Bi3D++, to sample valuable data from both source and target domains and transfer the knowledge learned from the source domain to the target domain. Bi3D++ first samples target-like source data by measuring scene-level and instance-level similarity between the source and target domains to avoid interference with irrelevant source data. Then a hybrid active target sampling strategy is introduced to sample target data that comprehensively considers rare-class similarity, intra-frame, and inter-frame diversity to sample diverse frames with diverse instances and focus more on rare classes in autonomous driving scenarios at the same time. Experiments on multiple cross-domain settings including cross-beam and cross-location demonstrate that our Bi3D++ can outperform existing state-of-the-art UDA methods with only 1% labeled target and consistently improve the performance with the increase of annotated target data."
summary: "A Bi-domain active learning approach which selects samples from both source and target domain to solve cross-domain 3D object detection."
tags:
  - 3D Object Detection
  - Domain Adaptation
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11498459
---
