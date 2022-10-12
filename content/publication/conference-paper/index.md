---
abstract: Despite its impressive performance on semantic segmentation of remote
  sensing imagery, deep learning requires a large amount of labeled data for
  model training, which is both laborious and timeconsuming for an individual
  institution. To cope with this obstacle, federated Learning (FL) has been
  proposed to enable multiple institutions to train a global model
  collaboratively without violating privacy rules. However, the performance of
  FL is poor in the presence of heterogeneous training data, i.e. the data is
  not independently and identically distributed (non-i.i.d) among participating
  clients, especially for remote sensing images with high spatial and spectral
  heterogeneity. In this paper, we propose an FL algorithm combined with
  prototype-based hierarchical clustering (Fed-PHC). Instead of updating a
  single global model to capture the shared knowledge of all clients, we utilize
  a mixture of multiple global models to handle the heterogeneity between
  various clients using hierarchical clustering (HC) based on the prototypical
  representations of clients' datasets. As a result, FedPHC can reduce the
  domain discrepancy within each group and obtain more representative models for
  heteroge-neous datasets. Extensive experiments on the Inria Aerial Image
  Dataset confirm the effectiveness of FedPHC.
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - Boning Zhang
  - admin
  - Man-On Pun
  - Ming Liu
author_notes: []
publication: In *2022 IEEE International Geoscience and Remote Sensing Symposium*
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_project: ""
publication_short: In *2022 IEEE International Geoscience and Remote Sensing Symposium*
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com
title: Prototype-Based Clustered Federated Learning for Semantic Segmentation of
  Aerial Images
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
