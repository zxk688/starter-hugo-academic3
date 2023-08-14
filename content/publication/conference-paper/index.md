---
abstract: Deep convolutional neural networks (DCNNs) have become the leading
  tools for object extraction from very-high-resolution (VHR) remote sensing
  images. However, the label scarcity problem of local datasets hinders the
  prediction performances of DCNNs, and privacy concerns regarding remote
  sensing data often arise in the traditional deep learning schemes. To cope
  with these problems, we propose a novel federated learning scheme with
  prototype matching (FedPM) to collaboratively learn a richer DCNN model by
  leveraging remote sensing data distributed among multiple clients. This scheme
  conducts the federated optimization of DCNNs by aggregating clients’ knowledge
  in the gradient space without compromising data privacy. Specifically, the
  prototype matching method is developed to regularize the local training using
  prototypical representations while reducing the distribution divergence across
  heterogeneous image data. Furthermore, the derived deviations across local and
  global prototypes are applied to quantify the effects of local models on the
  decision boundary and optimize the global model updating via the
  attention-weighted aggregation scheme. Finally, the sparse ternary compression
  (STC) method is used to alleviate communication costs. Extensive experimental
  results derived from VHR aerial and satellite image datasets verify that the
  FedPM can dramatically improve the prediction performance of DCNNs on object
  extraction with lower communication costs. To the best of our knowledge, this
  is the first time that federated learning has been applied for remote sensing
  visual tasks.
slides: example
url_pdf: https://ieeexplore.ieee.org/abstract/document/9883127
publication_types:
  - "2"
authors:
  - admin
  - X Zhang
  - B Zhang
  - W Yu
  - X Kang
author_notes: []
publication: "*IEEE Transactions on Geoscience and Remote Sensing* 61, 1-16"
summary: ""
url_dataset: ""
url_project: ""
publication_short: "*IEEE Transactions on Geoscience and Remote Sensing* 61, 1-16"
url_source: ""
url_video: ""
title: Federated Deep Learning With Prototype Matching for Object Extraction
  From Very-High-Resolution Remote Sensing Images
doi: 10.1109/TGRS.2023.3244136
featured: false
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/IgpMkNfsfys)"
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2022-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2022-07-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
