---
title: "Bi3D: Bi-domain Active Learning for Cross-domain 3D Object Detection"
authors:
- Jiakang Yuan
- Bo Zhang
- Xiangchao Yan
- Tao Chen
- Botian Shi
- Yikang Li
- Yu Qiao
date: "2023-02-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "CVPR 2023"
publication_short: "CVPR 2023"
abstract: "Unsupervised Domain Adaptation (UDA) technique has been explored in 3D cross-domain tasks recently. Though preliminary progress has been made, the performance gap between the UDA-based 3D model and the supervised one trained with fully annotated target domain is still large. This motivates us to consider selecting partial-yet-important target data and labeling them at a minimum cost, to achieve a good trade-off between high performance and low annotation cost. To this end, we propose a Bi-domain active learning approach, namely Bi3D, to solve the cross-domain 3D object detection task. The Bi3D first develops a domainness-aware source sampling strategy, which identifies target-domain-like samples from the source domain to avoid the model being interfered by irrelevant source data. Then a diversity-based target sampling strategy is developed, which selects the most informative subset of target domain to improve the model adaptability to the target domain using as little annotation budget as possible. Experiments are conducted on typical cross-domain adaptation scenarios including cross-LiDAR-beam, cross-country, and cross-sensor, where Bi3D achieves a promising target-domain detection accuracy (89.63% on KITTI) compared with UDAbased work (84.29%), even surpassing the detector trained on the full set of the labeled target domain (88.98%)."
summary: "A Bi-domain active learning approach which selects samples from both source and target domain to solve cross-domain 3D object detection."
tags:
  - 3D Object Detection
  - Domain Adaptation
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/abs/2303.05886
---
