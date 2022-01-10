---
layout: paper
title: "Learning Airfoil Manifolds with Optimal Transport"
year: "2022"
shortref: "Qiuyi Chen, Phillip Pope, Mark Fuge <i>AIAA SciTech</i> 2022"
nickname: OT-airfoil
journal: "AIAA SCITECH 2022 Forum"
volume: 
issue: 
pages: 
authors: "Qiuyi Chen, Phillip Pope, Mark Fuge"
image: /assets/images/papers/2022_qiuyi_airfoil_manifold.png
redirect_from: 
fulltext: "https://arc.aiaa.org/doi/abs/10.2514/6.2022-2352"
pdf: /assets/pdfs/2022_qiuyi_airfoil_manifold_aiaa.pdf
pdflink: 
github:  "https://github.com/IDEALLab/EGAN_Airfoil"
doi: 10.2514/6.2022-2352
category: paper
published: true
tags: [artificial intelligence, data-driven design, design optimization, machine learning, manifold learning]
---
{% include JB/setup %}

# Abstract 

The manifold hypothesis forms a pillar of many modern machine learning techniques. Within the context of design, it proposes that valid designs reside on low dimensional manifolds in the high dimensional design spaces. Our previous research—BézierGAN—suggests learning
the low dimensional parameterization of valid airfoil designs can indeed accelerate aerodynamic optimizations. However, it incurs problems such as misalignment, long training time, and the trouble of fi nding the latent dimensionality. In this work we present the optimal-transport-based sibling of BézierGAN that surpass its predecessor in terms of both manifold approximating precision and learning speed, and provide methodology that helps determine the intrinsic dimension of the design manifold beforehand.


# BibTeX Citation

```
@inbook{chen2022manifold,
author = {Qiuyi Chen and Phillip Pope and Mark Fuge},
title = {Learning Airfoil Manifolds with Optimal Transport},
booktitle = {AIAA SCITECH 2022 Forum},
chapter = {},
pages = {},
doi = {10.2514/6.2022-2352},
URL = {https://arc.aiaa.org/doi/abs/10.2514/6.2022-2352},
eprint = {https://arc.aiaa.org/doi/pdf/10.2514/6.2022-2352},
    abstract = {The manifold hypothesis forms a pillar of many modern machine learning techniques. Within the context of design, it proposes that valid designs reside on low dimensional manifolds in the high dimensional design spaces. Our previous research—BezierGAN—suggests learning the low dimensional parameterization of valid airfoil designs can indeed accelerate aerodynamic optimizations. However, it incurs problems such as misalignment, long training time, and the trouble of fi nding the latent dimensionality. In this work we present the optimal-transport-based sibling of BézierGAN that surpass its predecessor in terms of both manifold approximating precision and learning speed, and provide methodology that helps determine the intrinsic dimension of the design manifold beforehand. }
}
```
