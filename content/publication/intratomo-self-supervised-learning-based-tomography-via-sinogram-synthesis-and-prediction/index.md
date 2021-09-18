---
title: "IntraTomo: Self-supervised Learning-based Tomography via Sinogram
  Synthesis and Prediction"
publication_types:
  - "1"
authors:
  - Guangming Zang
  - Ramzi Idoughi
  - Rui Li
  - Peter Wonka
  - Wolfgang Heidrich
publication: In ICCV. 2021
publication_short: In ICCV, 2021
abstract: |-
  We propose IntraTomo, a powerful framework that com-
  bines the benefits of learning-based and model-based ap-
  proaches for solving highly ill-posed inverse problems in the
  Computed Tomography (CT) context. IntraTomo is composed
  of two core modules: a novel sinogram prediction module,
  and a geometry refinement module, which are applied it-
  eratively. In the first module, the unknown density field
  is represented as a continuous and differentiable function,
  parameterized by a deep neural network. This network is
  learned, in a self-supervised fashion, from the incomplete
  or/and degraded input sinogram. After getting estimated
  through the sinogram prediction module, the density field is
  consistently refined in the second module using local and
  non-local geometrical priors. With these two core modules,
  we show that IntraTomo significantly outperforms existing
  approaches on several ill-posed inverse problems, such as
  limited angle tomography with a range of 45 degrees, sparse
  view tomographic reconstruction with as few as eight views,
  or super-resolution tomography with eight times increased
  resolution. The experiments on simulated and real data
  show that our approach can achieve results of unprecedented
  quality.
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: true
date: 2021-09-18T12:09:03.758Z
---
