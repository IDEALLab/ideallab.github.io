---
layout: paper
title: "Automatically Discovering Mechanical Functions from Physical Behaviors Via Clustering"
year: "2021"
shortref: "Kevin Chiu, David Anderson, and Mark Fuge <i>ASME IDETC</i> 2021"
nickname: BehaviorClustering
journal: "IDETC"
volume: 
issue: 
pages: 
authors: "Kevin Chiu, David Anderson, and Mark Fuge"
image: 
redirect_from: 
fulltext:
pdf: 
pdflink: 
github: 
doi: 
category: paper
published: false
tags: [curve]
---
{% include JB/setup %}

# Abstract

Computational design methods provide opportunities to discover novel and diverse designs that traditional optimization approaches cannot find or that use physical phenomena in ways that engineers have overlooked. However, existing methods require supervised objectives to search or optimize for explicit behaviors or functions — e.g., optimizing aerodynamic lift. In contrast, this paper unpacks what it means to discover interesting behaviors or functions we do not know about a priori using data from experiments or simulation in a fully unsupervised way. Doing so enables computers to invent or re-invent new or existing mechanical functions given only measurements of physical fields (e.g., pressure or electromagnetic fields) without directly specifying a set of objectives to optimize.

This paper explores this approach via two related parts. First, we study clustering algorithms that can detect novel device families from simulation data. Specifically, we contribute a modification to the Hierarchical Density-Based Spatial Clustering of Applications with Noise ("HDBSCAN") algorithm via the use of the silhouette score to reduce excessively granular clusters. Second, we study multiple ways by which we preprocess simulation data to increase its discriminatory power in the context of clustering device behavior. This leads to an insight regarding the important role that a design's representation has in compactly encoding its behavior.

We test our contributions via the task of discovering designs that function as fluidic logic gates. We generate synthetic data that mimics fluidic devices and show that our proposed contributions better discover logic gates, as measured by adjusted Rand score. Specifically, combining the Resolution Selection process and principal component analysis resulted in the highest and tightest spread of adjusted Rand scores on our tested datasets. This opens up new avenues of research wherein computers can automatically explore different types of physics and then derive new device functions, behaviors, and structures without the need for human labels or guidance.

# BibTeX Citation

```
@article{chiu2021BehaviorClustering,
  title={Automatically Discovering Mechanical Functions from Physical Behaviors Via Clustering},
  author={Chiu, Kevin and Anderson, David and Fuge, Mark},
  journal={ASME IDETC},
  year={2021}
}
```
