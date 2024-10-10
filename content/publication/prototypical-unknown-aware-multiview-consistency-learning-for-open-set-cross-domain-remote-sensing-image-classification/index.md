---
title: Prototypical Unknown-Aware Multiview Consistency Learning for Open-Set
  Cross-Domain Remote Sensing Image Classification
publication_types:
  - "2"
authors:
  - admin
  - W. Wu
  - M. Zhang
  - W. Yu and P. Ghamisi
doi: 10.1109/TGRS.2024.3476151
publication_short: IEEE Transactions on Geoscience and Remote Sensing, 2024.
abstract: Developing a cross-domain classification model for remote sensing
  images has drawn significant attention in the literature. By leveraging the
  open-set Unsupervised Domain Adaptation (UDA) technique, the generalization
  performance of deep learning models has been improved with the capability to
  recognize unknown categories. However, it remains challenging to explore
  distribution patterns in the target domain using uncertain category-wise
  supervision from unlabeled datasets while reducing negative transfer caused by
  unknown samples. To develop a robust open-set UDA framework, this paper
  presents Prototypical Unknown-aware Multiview Consistency Learning (PUMCL)
  designed for remote sensing scene classification across heterogeneous domains.
  Specifically, it employs a consistency learning scheme with multiview and
  multilevel perturbations to improve feature learning from unlabeled target
  samples. An entropy separation strategy is utilized to facilitate open-set
  detection and recognition during adaptation, enabling unknown-aware feature
  alignment. Furthermore, the introduction of prototypical constraints optimizes
  pseudo-label generation through online denoising and promotes a compact
  category-wise feature subspace for improved class separation across domains.
  Experiments conducted on six cross-domain scenarios using AID, NWPU, and UCMD
  datasets demonstrate the method’s superior performance compared to nine
  state-of-the-art approaches, achieving a gain of 4.5% to 21.2% in mIoU. More
  importantly, it shows promising class separability with clear boundaries
  between different classes and compact clustering of unknown samples in the
  feature space. The source code will be available at https://github.com/zxk688.
draft: false
featured: true
image:
  filename: abstract.png
  focal_point: Smart
  preview_only: false
date: 2024-10-10T04:40:08.075Z
---
