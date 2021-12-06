---
layout: paper
title: "Inverse Design of 2D Airfoils using Conditional Generative Models and Surrogate Log-Likelihoods"
year: "2022"
shortref: "Qiuyi Chen, Jun Wang, Phillip Pope, Wei (Wayne) Chen and Mark Fuge <i>JMD</i> 2021"
nickname: inverse-airfoil
journal: "Journal of Mechanical Design"
volume: 144
issue: 2
pages: 021712
authors: "Qiuyi Chen, Jun Wang, Phillip Pope, Wei (Wayne) Chen, Mark Fuge"
image: /assets/images/papers/2021_qiuyi_invert_airfoil.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2021_qiuyi_inverse_airfoil_design_JMD.pdf
pdflink: 
github:  "https://github.com/IDEALLab/CEBGAN_JMD_2021"
doi: 10.1115/1.4052846
category: paper
published: true
tags: [artificial intelligence, data-driven design, design optimization, generative design, machine learning, uncertainty modeling]
---
{% include JB/setup %}

# Abstract 

This paper shows how to use conditional generative models in two-dimensional (2D) airfoil optimization to probabilistically predict good initialization points within the vicinity of the optima given the input boundary conditions, thus warm starting and accelerating further optimization. We accommodate the possibility of multiple optimal designs corresponding to the same input boundary condition and take this inversion ambiguity into account when designing our prediction framework. To this end, we first employ the conditional formulation of our previous work BézierGAN–Conditional BézierGAN (CBGAN)—as a baseline, then introduce its sibling conditional entropic BézierGAN (CEBGAN), which is based on optimal transport regularized with entropy. Compared with CBGAN, CEBGAN overcomes mode collapse plaguing conventional GANs, improves the average lift-drag (Cl/Cd) efficiency of airfoil predictions from 80.8% of the optimal value to 95.8%, and meanwhile accelerates the training process by 30.7%. Furthermore, we investigate the unique ability of CEBGAN to produce a log-likelihood lower bound that may help select generated samples of higher performance (e.g., aerodynamic performance). In addition, we provide insights into the performance differences between these two models with low-dimensional toy problems and visualizations. These results and the probabilistic formulation of this inverse problem justify the extension of our GAN-based inverse design paradigm to other inverse design problems or broader inverse problems.


# BibTeX Citation

```
@article{chen2021inverse,
    author = {Chen, Qiuyi and Wang, Jun and Pope, Phillip and (Wayne) Chen, Wei and Fuge, Mark},
    title = "{Inverse Design of Two-Dimensional Airfoils Using Conditional Generative Models and Surrogate Log-Likelihoods}",
    journal = {Journal of Mechanical Design},
    volume = {144},
    number = {2},
    year = {2021},
    month = {12},
    abstract = "{This paper shows how to use conditional generative models in two-dimensional (2D) airfoil optimization to probabilistically predict good initialization points within the vicinity of the optima given the input boundary conditions, thus warm starting and accelerating further optimization. We accommodate the possibility of multiple optimal designs corresponding to the same input boundary condition and take this inversion ambiguity into account when designing our prediction framework. To this end, we first employ the conditional formulation of our previous work BézierGAN–Conditional BézierGAN (CBGAN)—as a baseline, then introduce its sibling conditional entropic BézierGAN (CEBGAN), which is based on optimal transport regularized with entropy. Compared with CBGAN, CEBGAN overcomes mode collapse plaguing conventional GANs, improves the average lift-drag (Cl/Cd) efficiency of airfoil predictions from 80.8\\% of the optimal value to 95.8\\%, and meanwhile accelerates the training process by 30.7\\%. Furthermore, we investigate the unique ability of CEBGAN to produce a log-likelihood lower bound that may help select generated samples of higher performance (e.g., aerodynamic performance). In addition, we provide insights into the performance differences between these two models with low-dimensional toy problems and visualizations. These results and the probabilistic formulation of this inverse problem justify the extension of our GAN-based inverse design paradigm to other inverse design problems or broader inverse problems.}",
    issn = {1050-0472},
    doi = {10.1115/1.4052846},
    url = {https://doi.org/10.1115/1.4052846},
    note = {021712},
    eprint = {https://asmedigitalcollection.asme.org/mechanicaldesign/article-pdf/144/2/021712/6806632/md\_144\_2\_021712.pdf},
}
```