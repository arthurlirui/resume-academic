---
slides: example
url_pdf: ""
date: 2016-04-27T00:00:00.000Z
summary: Cluster Sensing Superpixel and Grouping
url_video: ""
title: Effiicient Superpixel and Grouping
subtitle: ""
featured: true
tags:
  - Computer Vision
  - Segmentation
  - Grouping
external_link: ""
url_slides: ""
categories:
  - segmentation
links: []
image:
  caption: ""
  focal_point: Smart
url_code: ""
---
Superpixel algorithms have shown significant potential
in computer vision applications since they can be used to
accelerate other computationally demanding algorithms.
However, in contrast to the original purpose of superpixels,
many upper layer methods still suffer from computational
problems when incorporating superpixel for speedup. In
this paper, we present a cluster sensing superpixel (CSS)
method to efficiently generate superpixel bricks. Based on
the insight of pixel density, cluster centers generally have
properties of representativeness (i.e., local maximal pixel
density) and isolation (i.e., large distance from other cluster
centers). Our CSS method efficiently identifies ideal cluster
centers via utilizing pixel density. We also integrate superpixel cues into a bipartite graph segmentation framework
and apply it to microscopy image segmentation. Extensive
experiments show that our CSS method achieves impressive efficiency, being approximately five times faster than
the state-of-the-art methods and having comparable performance in terms of the standard metrics. Application on
microscopy image segmentation also benefits our efficient
implementation.