---
title: "Sequential Token Merging: Revisiting Hidden States"
authors:
- Yan Wen
- Peng Ye
- Lin Zhang
- Baopu Li
- Jiakang Yuan
- Yaoxin Yang
- Tao Chen
date: "2025-09-19T00:00:00Z"
publication_types: ['article']
publication: "arXiv preprint"
publication_short: "arXiv"
abstract: "Vision Mambas (ViMs) achieve remarkable success with sub-quadratic complexity, but their efficiency remains constrained by quadratic token scaling with image resolution. While existing methods address token redundancy, they overlook ViMs' intrinsic Limited Directional Sequential Dependence (LDSD) - a critical information flow mechanism revealed in our analysis. We further identify Mamba's selective scan enables gradual information aggregation in hidden states. Based on these insights, we propose Sequential Token Merging (STM), featuring: 1) Bidirectional nearest neighbor merging to preserve sequential dependencies through symmetric spatial aggregation, and 2) Hidden states protection to stabilize the hidden states around the class token. STM strategically leverages Mamba's layer-wise loss convergence to convert temporal forgetfulness into stability. Experiments demonstrate STM's superiority: 1.0% accuracy drop for ViM-Ti at 20% token reduction, and only 1.4% degradation for ViM-S at 40% reduction. Our method achieves state-of-the-art efficiency with minimal complexity, while providing new insights into state-space model dynamics."
summary: "Novel sequential token reduction pipeline for Mamba."
tags:
  - Token Reduction
  - Mamba
category: "Others"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2509.22691"
---
