---
title: Cross-domain landslide mapping from large-scale remote sensing images
  using prototype-guided domain-aware progressive representation learning
publication_types:
  - "0"
authors:
  - admin*
  - Xiaokang Zhang
  - Man-On Pun
  - Wenzhong Shi
doi: https://doi.org/10.1016/j.isprsjprs.2023.01.018
abstract: Landslide mapping via pixel-wise classification of remote sensing
  imagery is essential for hazard prevention and risk assessment.
  Deep-learning-based change detection greatly aids landslide mapping by
  identifying the down-slope movement of soil, rock and other materials from
  bitemporal images, benefiting from the feature representation capabilities of
  convolutional neural networks. However, these networks rely on large amounts
  of pixel-level annotated data to achieve their promising performance and they
  normally exhibit weak generalization capability on heterogeneous image data
  from unseen domains. To address these issues, we propose a prototype-guided
  domain-aware progressive representation learning (PG-DPRL) method for
  cross-domain landslide mapping from large-scale remote sensing images based on
  the multitarget domain adaptation (MTDA) technique. PG-DPRL attempts to learn
  a shared landslide mapping network that performs well in multiple target
  domains with no additional effort for sample annotation. Specifically, PG-DPRL
  adopts a near-to-far adaptation strategy to gradually align the representation
  distributions of all target domains with the source domain, considering
  discrepancies between them. On this basis, cross-domain prototype learning is
  exploited to generate reliable domain-specific pseudo-labels and aggregate
  representations across domains to learn a shared decision boundary. In each
  DPRL step, the prototype-guided adversarial learning (PGAL) algorithm is
  performed to achieve category-wise representation alignment and improve the
  discriminative capability of representations by introducing the Wasserstein
  distance metric and cross-domain prototype consistency (CPC) loss. Experiments
  on a global very-high-resolution landslide mapping (GVLM) dataset consisting
  of 17 heterogeneous domains from different landslide sites demonstrate the
  effectiveness and robustness of PG-DPRL. It considerably improves the
  transferability of landslide mapping networks and outperforms several
  state-of-the-art approaches in terms of total and average accuracy metrics
  among all target domains.
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-03-20T02:01:34.512Z
---
