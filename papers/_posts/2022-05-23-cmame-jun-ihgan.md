---
layout: paper
title: "IH-GAN: A Conditional Generative Model for Implicit Surface-Based Inverse Design of Cellular Structures"
year: "2022"
shortref: "Jun Wang, Wei (Wayne) Chen, Daicong Da, Mark Fuge and Rahul Rai <i>CMAME</i> 2022"
nickname: ihgan-cmame
journal: "Computer Methods in Applied Mechanics and Engineering"
volume: 396
issue: 
pages: 115060
authors: "Jun Wang, Wei (Wayne) Chen, Daicong Da, Mark Fuge and Rahul Rai"
image: /assets/images/papers/2022_jun_ihgan_cmame.svg
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2022_jun_ihgan_cmame.pdf
pdflink: 
github:  "https://github.com/IDEALLab/IH-GAN_CMAME_2022"
doi: 10.1016/j.cma.2022.115060
category: paper
published: true
tags: [artificial intelligence, data-driven design, design optimization, generative design, machine learning, inverse design]
---
{% include JB/setup %}

# Abstract 

Variable-density cellular structures can overcome connectivity and manufacturability issues of topologically optimized structures, particularly those represented as discrete density maps. However, the optimization of such cellular structures is challenging due to the multiscale design problem. Past work addressing this problem generally either only optimizes the volume fraction of single-type unit cells but ignoring the effects of unit cell geometry on properties, or considers the geometry–property relation but builds this relation via heuristics. In contrast, we propose a simple yet more principled way to accurately model the property to geometry mapping using a conditional deep generative model, named Inverse Homogenization Generative Adversarial Network (IH-GAN). It learns the conditional distribution of unit cell geometries given properties and can realize the one-to-many mapping from properties to geometries. We further reduce the complexity of IH-GAN by using the implicit function parameterization to represent unit cell geometries. Results show that our method can 1) generate various unit cells that satisfy given material properties with high accuracy (R2-scores between target properties and properties of generated unit cells > 98%) and 2) improve the optimized structural performance over the conventional variable-density single-type structure. In the minimum compliance example, our IH-GAN generated structure achieves a 79.7% reduction in concentrated stress and an extra 3.03% reduction in displacement. In the target deformation examples, our IH-GAN generated structure reduces the target matching error by 86.4% and 79.6% for two test cases, respectively. We also demonstrated that the connectivity issue for multi-type unit cells can be solved by transition layer blending.


# BibTeX Citation

```
@article{wang2022ih,
  title={IH-GAN: A conditional generative model for implicit surface-based inverse design of cellular structures},
  author={Wang, Jun and Chen, Wei Wayne and Da, Daicong and Fuge, Mark and Rai, Rahul},
  journal={Computer Methods in Applied Mechanics and Engineering},
  volume={396},
  pages={115060},
  year={2022},
  publisher={Elsevier}
}
```
