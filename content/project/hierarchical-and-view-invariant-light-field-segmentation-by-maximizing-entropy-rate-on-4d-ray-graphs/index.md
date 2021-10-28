---
slides: example
url_pdf: ""
date: 2016-04-27T00:00:00.000Z
summary: "**Siggraph Asia 2019** - Hierarchical and View-invariant Light Field
  Segmentation by Maximizing Entropy Rate on 4D Ray Graphs"
url_video: ""
title: Light Field Segmentation, Depth Refinement
subtitle: ""
featured: true
tags:
  - Light Field
  - Segmentation
  - Depth
  - Submodular Function
external_link: ""
url_slides: ""
links: []
image:
  caption: ""
  focal_point: Smart
url_code: ""
---
Image segmentation is an important first step of many image processing,
computer graphics, and computer vision pipelines. Unfortunately, it remains
difficult to automatically and robustly segment cluttered scenes, or scenes
in which multiple objects have similar color and texture. In these scenarios,
light fields offer much richer cues that can be used efficiently to drastically
improve the quality and robustness of segmentations.
In this paper we introduce a new light field segmentation method that
respects texture appearance, depth consistency, as well as occlusion, and
creates well-shaped segments that are robust under viewpoint changes.
Furthermore, our segmentation is hierarchical, i.e. with a single optimization, a whole hierarchy of segmentations with different numbers of regions
is available. All this is achieved with a submodular objective function that allows for efficient greedy optimization. Finally, we introduce a new tree array type data structure, i.e. a disjoint tree, to efficiently perform submodular optimization on very large graphs. This approach is of interest beyond
our specific application of light field segmentation.
We demonstrate the efficacy of our method on a number of synthetic and
real data sets, and show how the obtained segmentations can be used for
applications in image processing and graphics.