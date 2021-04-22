---
layout: paper
title: "IH-GAN: A Conditional Generative Model for Implicit Surface-Based Inverse Design of Cellular Structures"
year: "2021"
shortref: "Jun Wang, Wei Chen, Mark Fuge, and Rahul Rai <i>arXiv</i> 2021"
nickname: ihgan-arxiv
journal: "arXiv"
volume: 
issue: 
pages: 
authors: "Jun Wang, Wei Chen, Mark Fuge, and Rahul Rai"
image: /assets/images/papers/2021_jun_ihgan_arxiv.svg
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2021_jun_ihgan_arxiv.pdf
pdflink: 
github: "https://github.com/IDEALLab/IH-GAN" 
doi: 
category: paper
published: true
tags: [ihgan_arxiv]
---
{% include JB/setup %}

# Abstract 

Variable-density cellular structures can overcome connectivity and manufacturability issues of topologically-optimized, functionally graded structures, particularly when those structures are represented as discrete density maps. One naïve approach to creating variable-density cellular structures is simply replacing the discrete density map with an unselective type of unit cells having corresponding densities. However, doing so breaks the desired mechanical behavior, as equivalent density alone does not guarantee equivalent mechanical properties. Another approach uses homogenization methods to estimate each pre-defined unit cell's effective properties and remaps the unit cells following a scaling law. However, a scaling law merely mitigates the problem by performing an indirect and inaccurate mapping from the material property space to single-type unit cells. In contrast, we propose a deep generative model that resolves this problem by automatically learning an accurate mapping and generating diverse cellular unit cells conditioned on desired properties (i.e., Young's modulus and Poisson's ratio). We demonstrate our method via the use of implicit function-based unit cells and conditional generative adversarial networks. Results show that our method can 1) generate various unit cells that satisfy given material properties with high accuracy (relative error <5%), 2) create functionally graded cellular structures with high-quality interface connectivity (98.7% average overlap area at interfaces), and 3) improve the structural performance over the conventional topology-optimized variable-density structure (84.4% reduction in concentrated stress and extra 7% reduction in displacement).


# BibTeX Citation

```
@article{wang2021ih,
  title={IH-GAN: A Conditional Generative Model for Implicit Surface-Based Inverse Design of Cellular Structures},
  author={Wang, Jun and Chen, Wei and Fuge, Mark and Rai, Rahul},
  journal={arXiv preprint arXiv:2103.02588},
  year={2021}
}
```
