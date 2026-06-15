---
title: "Reg-TTA3D: Better Regression Makes Better Test-time Adaptive 3D Object Detection"
authors:
- Jiakang Yuan
- Bo Zhang
- Kaixiong Gong
- Xiangyu Yue
- Botian Shi
- Yu Qiao
- Tao Chen
date: "2024-07-01T00:00:00Z"
publication_types: ['paper-conference']
publication: "ECCV 2024"
publication_short: "ECCV 2024"
abstract: "Domain Adaptation (DA) has been widely explored and made significant progress on cross-domain 3D tasks recently. Despite being effective, existing works fail to deal with rapidly changing domains due to the unpredictable test time scenarios and meanwhile fast response time requirement. Thus, we explore a new task named test-time domain adaptive 3D object detection and propose Reg-TTA3D, a pseudo-labelbased test-time adaptative 3D object detection method. By investigating the factor that limits the detection accuracy, we find that regression is essential in this task. To make better regression, we first design a noiseconsistency pseudo-label generation process to filter pseudo-labels with instability under noise interference and obtain reliable pseudo-labels. Then, confidence-guided regression refinement is introduced, which uses the box regression results of high-confidence boxes to supervise boxes with relatively low confidence, further making the predicted box size gradually approach the distribution of the target domain. Finally, to better update the regression layer and alleviate the class-imbalance issue, a class-balance EMA updating strategy is proposed. Experimental results on multiple cross-domain scenarios including cross-beam, crosslocation, and cross-weather demonstrate that Reg-TTA3D can achieve comparable or even better performance compared to unsupervised domain adaptation works by only updating less than 0.1% parameters within less than 1% time."
summary: "A pseudo-label-based test-time adaptive 3D object detection method exploring a new task of test-time domain adaptive 3D detection."
tags:
  - 3D Object Detection
  - Test-Time Adaptation
category: "3D Vision & Autonomous Driving"
featured: false
links:
  - type: pdf
    url: "https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05971.pdf"
---
