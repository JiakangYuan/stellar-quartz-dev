---
title: "3DET-Mamba: Causal Sequence Modelling for End-to-End 3D Object Detection"
authors:
- Mingsheng Li*
- Jiakang Yuan*
- Sijin Chen
- Lin Zhang
- Anyu Zhu
- Xin Chen
- Tao Chen
date: "2024-09-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "NeurIPS 2024"
publication_short: "NeurIPS 2024"
abstract: "Transformer-based architectures have been proven successful in detecting 3D objects from point clouds. However, the quadratic complexity of the attention mechanism struggles to encode rich information as point cloud resolution increases. Recently, state space models (SSM) such as Mamba have gained great attention due to their linear complexity and long sequence modeling ability for language understanding. To exploit the potential of Mamba on 3D scene-level perception, for the first time, we propose 3DET-Mamba, which is a novel SSM-based model designed for indoor 3d object detection. Specifically, we divide the point cloud into different patches and use a lightweight yet effective Inner Mamba to capture local geometric information. To observe the scene from a global perspective, we introduce a novel Dual Mamba module that models the point cloud in terms of spatial distribution and continuity. Additionally, we design a Query-aware Mamba module that decodes context features into object sets under the guidance of learnable queries. Extensive experiments demonstrate that 3DET-Mamba surpasses previous 3DETR on indoor 3D detection benchmarks such as ScanNet, improving AP25/AP50 from 65.0%/47.0% to 70.4%/54.4%, respectively."
summary: "Exploit the potential of Mamba architecture on 3D scene-level perception for the first time."
tags:
  - 3D Object Detection
  - State Space Model
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: ""
---
