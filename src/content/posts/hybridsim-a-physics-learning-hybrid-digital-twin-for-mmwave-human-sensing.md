---
title: "HybridSim: A Physics-Learning Hybrid Digital Twin for mmWave Human Sensing"
authors: Weitao Xiong, Tianyu Liu, Peng Li, Kok Chung Chua, Toa Chean Khim, Pu Wang, Hongfei Xue†
published: 2026-03-06T20:25:00.000+08:00
image: /src/assets/images/mmWave_teaser.jpg
coverImage: /src/assets/images/mmWave_teaser.jpg
tags:
  - mmWave Synthesis
  - Inverse Rendering
  - under review
category: Research
draft: false
description: ""
---
High-fidelity simulation of mmWave radar signals for dynamic human motion is valuable for developing radar-based human sensing models; yet collecting accurately labeled measurements for a specific deployment site remains expensive. We present HybridSim, a physics–learning hybrid simulator that synthesizes mmWave radar signals from dynamic human meshes under a fixed indoor room configuration, explicitly decoupling propagation into two components. To parameterize the human subject, we use a TriPlane representation to extract human features and a Graph Convolutional Network to stabilize optimization and mitigate gradient instability. The direct signal path is modeled via an inverse-rendering formulation with a microfacet BRDF to capture primary surface reflections. In parallel, the indirect path is approximated by combining 3D Gaussian Splatting with a virtual-receiver geometry to fit and reproduce site-specific multipath interference patterns, achieving substantially lower computational cost than explicit full ray tracing. Experiments in a fixed-room setting show improved agreement with a physically based reference and consistent gains on downstream radar-based human sensing tasks when using HybridSim for site-specific data augmentation.
