---
layout: paper
title: "Aerodynamic Design Optimization and Shape Exploration using Generative Adversarial Networks"
year: "2018"
shortref: "Wei Chen, Kevin Chiu, and Mark Fuge <i>AIAA SciTech</i> 2018"
nickname: hgan
journal: "Proceedings of the AIAA SciTech Conference"
volume: 
issue: 
pages: 
authors: "Wei Chen, Kevin Chiu, and Mark Fuge"
image: /assets/images/papers/airfoil_opt.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/chen_airfoil_opt_scitech_2019.pdf
pdflink: 
github: "https://github.com/IDEALLab/airfoil-opt-gan"
doi:
category: paper
published: true
tags: [airfoil_opt]
---
{% include JB/setup %}

# Abstract 

Global optimization of aerodynamic shapes requires a large number of expensive CFD simulations because of the high dimensionality of the design space. One means to combat that problem is to reduce the dimension of the design space—for example, by constructing low dimensional parametric functions (such as PARSEC and others)—and then optimizing over those parameters instead. Such approaches require first a parametric function that compactly describes useful variation in airfoil shape—a non-trivial and error-prone task. In contrast, we propose to use a deep generative model of aerodynamic designs (specifically airfoils) that reduces the dimensionality of the optimization problem by learning from shape variations in the UIUC airfoil database. We show that our data-driven model both (1) learns realistic and compact airfoil shape representations and (2) empirically accelerates optimization convergence by over an order of magnitude.




# BibTeX Citation

```
@inproceedings{chen2019aerodynamic,
    author={Chen, Wei and Chiu, Kevin and Fuge, Mark},
    title={Aerodynamic Design Optimization and Shape Exploration using Generative Adversarial Networks},
    booktitle={AIAA SciTech Forum},
    year={2019},
    month={Jan},
    publisher={AIAA},
    address={San Diego, USA}
}
```
