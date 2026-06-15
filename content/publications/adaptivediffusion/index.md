---
title: "Training-Free Adaptive Diffusion with Bounded Difference Approximation Strategy"
authors:
- Hancheng Ye*
- Jiakang Yuan*
- Renqiu Xia
- Xiangchao Yan
- Tao Chen
- Junchi Yan
- Botian Shi
- Bo Zhang
date: "2024-09-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "NeurIPS 2024"
publication_short: "NeurIPS 2024"
abstract: "Diffusion models have recently achieved great success in the synthesis of high-quality images and videos. However, the existing denoising techniques in diffusion models are commonly based on step-by-step noise predictions, which suffers from high computation cost, resulting in a prohibitive latency for interactive applications. In this paper, we propose AdaptiveDiffusion to relieve this bottleneck by adaptively reducing the noise prediction steps during the denoising process. Our method considers the potential of skipping as many noise prediction steps as possible while keeping the final denoised results identical to the original full-step ones. Specifically, the skipping strategy is guided by the third-order latent difference that indicates the stability between timesteps during the denoising process, which benefits the reusing of previous noise prediction results. Extensive experiments on image and video diffusion models demonstrate that our method can significantly speed up the denoising process while generating identical results to the original process, achieving up to an average 2~5x speedup without quality degradation."
summary: "AdaptiveDiffusion adaptively reduces noise prediction steps during denoising guided by third-order latent difference."
tags:
  - Diffusion Models
  - Efficient Inference
category: "AIGC"
featured: false
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2410.09873"
  - type: custom
    label: Project
    url: https://jiakangyuan.github.io/AdaptiveDiffusion-project-page/
  - type: code
    url: https://github.com/InternScience/AdaptiveDiffusion
---
