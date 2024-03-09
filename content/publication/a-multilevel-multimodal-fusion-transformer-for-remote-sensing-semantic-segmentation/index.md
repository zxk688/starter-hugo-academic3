---
title: A Multilevel Multimodal Fusion Transformer for Remote Sensing Semantic
  Segmentation
publication_types:
  - "0"
authors:
  - X. Ma
  - X. Zhang*
  - M. -O. Pun and M. Liu
author_notes:
  - "*IEEE Transactions on Geoscience and Remote Sensing*"
doi: 10.1109/TGRS.2024.3373033
abstract: Accurate semantic segmentation of remote sensing data plays a crucial
  role in the success of geoscience research and applications. Recently,
  multimodal fusion-based segmentation models have attracted much attention due
  to their outstanding performance as compared to conventional single-modal
  techniques. However, most of these models perform their fusion operation using
  convolutional neural networks (CNN) or the vision transformer (Vit), resulting
  in insufficient local-global contextual modeling and representative
  capabilities. In this work, a multilevel multimodal fusion scheme called
  FTransUNet is proposed to provide a robust and effective multimodal fusion
  backbone for semantic segmentation by integrating both CNN and Vit into one
  unified fusion framework. Firstly, the shallow-level features are first
  extracted and fused through convolutional layers and shallow-level feature
  fusion (SFF) modules. After that, deep-level features characterizing semantic
  information and spatial relationships are extracted and fused by a
  well-designed Fusion Vit (FVit). It applies Adaptively Mutually Boosted
  Attention (Ada-MBA) layers and Self-Attention (SA) layers alternately in a
  three-stage scheme to learn cross-modality representations of high inter-class
  separability and low intra-class variations. Specifically, the proposed
  Ada-MBA computes SA and Cross-Attention (CA) in parallel to enhance intra- and
  cross-modality contextual information simultaneously while steering attention
  distribution towards semantic-aware regions. As a result, FTransUNet can fuse
  shallow-level and deep-level features in a multilevel manner, taking full
  advantage of CNN and transformer to accurately characterize local details and
  global semantics, respectively. Extensive experiments confirm the superior
  performance of the proposed FTransUNet compared with other multimodal fusion
  approaches on two fine-resolution remote sensing datasets, namely ISPRS
  Vaihingen and Potsdam. The source code in this work is available at
  https://github.com/sstary/SSRS.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-03-09T08:35:51.930Z
---
