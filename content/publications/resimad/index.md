---
title: "ReSimAD: Zero-Shot 3D Domain Transfer for Autonomous Driving with Source Reconstruction and Target Simulation"
authors:
- Bo Zhang*
- Xinyu Cai*
- Jiakang Yuan
- Donglin Yang
- Jianfei Guo
- Xiangchao Yan
- Renqiu Xia
- Botian Shi
- Min Dou
- Tao Chen
- Si Liu
- Junchi Yan
- Yu Qiao
date: "2024-01-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "ICLR 2024"
publication_short: "ICLR 2024"
abstract: "Domain shifts such as sensor type changes and geographical situation variations are prevalent in Autonomous Driving (AD), which poses a challenge since AD model relying on the previous domain knowledge can be hardly directly deployed to a new domain without additional costs. In this paper, we provide a new perspective and approach of alleviating the domain shifts, by proposing a Reconstruction-Simulation-Perception (ReSimAD) scheme. Specifically, the implicit reconstruction process is based on the knowledge from the previous old domain, aiming to convert the domain-related knowledge into domain-invariant representations, e.g., 3D scene-level meshes. Besides, the point clouds simulation process of multiple new domains is conditioned on the above reconstructed 3D meshes, where the target-domain-like simulation samples can be obtained, thus reducing the cost of collecting and annotating new-domain data for the subsequent perception process. For experiments, we consider different cross-domain situations such as Waymo-to-KITTI, Waymo-to-nuScenes, Waymo-to-ONCE, etc, to verify the zero-shot target-domain perception using ReSimAD. Results demonstrate that our method is beneficial to boost the domain generalization ability, even promising for 3D pre-training."
summary: "A Reconstruction-Simulation-Perception scheme for alleviating domain shifts in autonomous driving."
tags:
  - Autonomous Driving
  - Domain Adaptation
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: https://arxiv.org/abs/2309.05527
---
