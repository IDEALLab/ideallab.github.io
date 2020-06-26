---
layout: paper
title: "Airfoil Design Parameterization and Optimization using Bézier Generative Adversarial Networks"
year: "2020"
shortref: "Wei Chen, Kevin Chiu, and Mark Fuge <i>AIAAJ</i> 2020"
nickname: beziergan_aiaaj
journal: "AIAA Journal"
volume: 
issue: 
pages: 
authors: "Wei Chen, Kevin Chiu, and Mark Fuge"
image: /assets/images/papers/chen_beziergan_aiaaj_2020.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2020_chen_beziergan_aiaaj.pdf
pdflink: 
github: "https://github.com/IDEALLab/bezier-gan"
doi: 
category: paper
published: true
tags: [beziergan_aiaaj]
---
{% include JB/setup %}

# Abstract 

Global optimization of aerodynamic shapes usually requires a large number of expensive computational fluid dynamics simulations because of the high dimensionality of the design space. One approach to combat this problem is to reduce the design space dimension by obtaining a new representation. This requires a parametric function that compactly and sufficiently describes useful variation in shapes. We propose a deep generative model, Bézier-GAN, to parameterize aerodynamic designs by learning from shape variations in an existing database. The resulted new parameterization can accelerate design optimization convergence by improving the representation compactness while maintaining sufficient representation capacity. We use the airfoil design as an example to demonstrate the idea and analyze Bézier-GAN's representation capacity and compactness. Results show that Bézier-GAN both (1) learns smooth and realistic shape representations for a wide range of airfoils and (2) empirically accelerates optimization convergence by at least two times compared to state-of-the-art parameterization methods.




# BibTeX Citation

```
@article{chen2020airfoil,
  title={Airfoil Design Parameterization and Optimization using Bézier Generative Adversarial Networks},
  author={Chen, Wei and Chiu, Kevin and Fuge, Mark},
  journal={AIAA Journal},
  volume={},
  number={},
  pages={},
  year={2020},
  publisher={American Institute of Aeronautics and Astronautics}
}
```
