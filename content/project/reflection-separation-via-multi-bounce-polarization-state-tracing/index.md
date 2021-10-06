---
slides: example
url_pdf: ""
date: 2016-04-27T00:00:00.000Z
summary: "**ECCV 2020** - Reflection Separation via Multi-bounce Polarization
  State Tracing"
url_video: ""
title: Reflection Separation and Removal
subtitle: ""
featured: true
tags:
  - Computational Photography
  - Polarization
  - Reflection Removal
external_link: ""
url_slides: ""
links: []
image:
  caption: ""
  focal_point: Smart
url_code: ""
---
Reflection removal from photographs is an important task
in computational photography, but also for computer vision tasks that
involve imaging through windows and similar settings. Traditionally, the
problem is approached as a single reflection removal problem under very
controlled scenarios. In this paper we aim to generalize the reflection removal to real-world scenarios with more complicated light interactions.
To this end, we propose a simple yet efficient learning framework for
supervised image reflection separation with a polarization-guided ray tracing model and loss function design. Instead of a conventional image
sensor, we use a polarization sensor that instantaneously captures four
linearly polarized photos of the scene in the same image. Through a
combination of a new polarization-guided image formation model and
a novel supervised learning framework for the interpretation of a raytracing image formation model, a general method is obtained to tackle
general image reflection removal problems. We demonstrate our method
with extensive experiments on both real and synthetic data and demonstrate the unprecedented quality of image reconstructions.