---
abstract: Deep learning (DL) approaches based on convolutional encoder–decoder
  networks have shown promising results in bitemporal change detection. However,
  their performance is limited by insufficient contextual information
  aggregation because they cannot fully capture the implicit contextual
  dependency relationships among feature maps at different levels. Moreover,
  harvesting long-range contextual information typically incurs high
  computational complexity. To circumvent these challenges, we propose
  multilevel deformable attention-aggregated networks (MLDANets) to effectively
  learn long-range dependencies across multiple levels of bitemporal
  convolutional features for multiscale context aggregation. Specifically, a
  multilevel change-aware deformable attention (MCDA) module consisting of
  linear projections with learnable parameters is built based on multihead
  self-attention (SA) with a deformable sampling strategy. It is applied in the
  skip connections of an encoder–decoder network taking a bitemporal deep
  feature hypersequence (BDFH) as input. MCDA can progressively address a set of
  informative sampling locations in multilevel feature maps for each query
  element in the BDFH. Simultaneously, MCDA learns to characterize beneficial
  information from different spatial and feature subspaces of BDFH using
  multiple attention heads for change perception. As a result, contextual
  dependencies across multiple levels of bitemporal feature maps can be
  adaptively aggregated via attention weights to generate multilevel
  discriminative change-aware representations. Experiments on
  very-high-resolution (VHR) datasets verify that MLDANets outperform
  state-of-the-art change detection approaches with dramatically faster training
  convergence and high computational efficiency.
slides: example
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "2"
authors:
  - Xiaokang Zhang
  - Weikang Yu
  - Man-On Pun
author_notes: []
publication: "*IEEE Transactions on Geoscience and Remote Sensing*, 60:1-18"
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Multilevel Deformable Attention-Aggregated Networks for Change Detection
  in Bitemporal Remote Sensing Imagery
doi: ""
featured: false
tags:
  - Source Themes
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
  focal_point: ""
  preview_only: false
date: 2015-09-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
