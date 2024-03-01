---
title: Compressing repeated content within large-scale remote sensing images
authors:
- Wei Hua
- Rui Wang
- Xusheng Zeng
- Ying Tang
- Huamin Wang
- Hujun Bao
date: '2012-06-01'
publishDate: '2024-03-01T07:51:40.592007Z'
publication_types:
- article-journal
publication: '*Vis. Comput. (Computer Graphics International)*'
doi: 10.1007/s00371-012-0710-3
abstract: Large-scale remote sensing images, including both satellite and aerial photographs,
  are widely used to render terrain scenes in real-time geographic visualization systems.
  Such systems often require large memories in order to store fine terrain details
  and fast network speeds to transfer image data, if they are built as web applications.
  In this paper, we propose a progressive texture compression framework to reduce
  the memory and bandwidth cost by compressing repeated content within and among large-scale
  remote sensing images. Different from existing image factorization methods, our
  algorithm incrementally find similar regions in new images so that large-scale images
  can be more efficiently compressed over time. We further propose a descriptor, the
  Gray Split Rotate (GSR) descriptor, to accelerate the similarity search. The reconstruction
  quality is finally improved by compressing residual error maps using customized
  S3TC-like compression. Our experiment shows that even with the error maps, our system
  still has higher compression rate and higher compression quality than using S3TC
  alone, which is a typical compression solution in most existing visualization systems.
tags:
- Image epitomes
- Large-scale remote sensing image
links:
- name: URL
  url: https://doi.org/10.1007/s00371-012-0710-3
---