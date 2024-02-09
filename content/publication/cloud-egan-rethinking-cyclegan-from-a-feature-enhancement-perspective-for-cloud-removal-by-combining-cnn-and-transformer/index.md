---
title: "Cloud-EGAN: Rethinking CycleGAN From a Feature Enhancement Perspective
  for Cloud Removal by Combining CNN and Transformer"
publication_types:
  - "0"
authors:
  - X Ma
  - Y Huang
  - admin*
  - MO Pun
  - B Huang
doi: 10.1109/JSTARS.2023.3280947
publication: "*IEEE Journal of Selected Topics in Applied Earth Observations and
  Remote Sensing*"
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: Cloud cover presents a major challenge for geoscience research of
  remote sensing images with thick clouds causing complete obstruction with
  information loss while thin clouds blurring the ground objects. Deep learning
  (DL) methods based on convolutional neural networks (CNNs) have recently been
  introduced to the cloud removal task. However, their performance is hindered
  by their weak capabilities in contextual information extraction and
  aggregation. Unfortunately, such capabilities play a vital role in
  characterizing remote sensing images with complex ground objects. In this
  work, the conventional cycle-consistent generative adversarial network
  (CycleGAN) is revitalized from a feature enhancement perspective. More
  specifically, a saliency enhancement (SE) module is first designed to replace
  the original CNN module in CycleGAN to re-calibrate channel attention weights
  to capture detailed information for multi-level feature maps. Furthermore, a
  high-level feature enhancement (HFE) module is developed to generate
  contextualized cloud-free features while suppressing cloud components. In
  particular, HFE is composed of both CNN- and transformer-based modules. The
  former enhances the local high-level features by employing residual learning
  and multi-scale strategies, while the latter captures the long-range
  contextual dependencies with the Swin transformer module to exploit high-level
  information from a global perspective. Capitalizing on the SE and HFE modules,
  an effective Cloud-Enhancement GAN, namely Cloud-EGAN, is proposed to
  accomplish thin and thick cloud removal tasks. Extensive experiments on the
  RICE and the WHUS2-CR datasets confirm the impressive performance of
  Cloud-EGAN.
date: 2023-02-05T15:21:00.000Z
---
