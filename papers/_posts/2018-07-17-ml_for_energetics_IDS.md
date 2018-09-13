---
layout: paper
title: "Machine Learning of Energetic Material Properties"
year: "2018"
shortref: "Barnes et al. 2018"
nickname: ml-for-energetics-IDS
journal: "Proceedings of the 16th International Detonation Symposium"
volume:
issue:
pages:  
authors: "Brian C. Barnes, Daniel C. Elton, Zois Boukouvalas, DeCarlos E. Taylor, William D. Mattson, Mark D. Fuge, Peter W. Chung"
image: /assets/images/papers/2018_ml_for_energetics_IDS_molecule.png
redirect_from:
fulltext: "https://arxiv.org/abs/1807.06156"
pdf: /assets/pdfs/2018_ml_for_energetics_IDS.pdf
pdflink:
github:
doi:
category: paper
published: true
tags: [materials]
---
{% include JB/setup %}

# Abstract

In this work, we discuss use of machine learning techniques for rapid prediction of detonation properties including explosive energy, detonation velocity, and detonation pressure. Further, analysis is applied to individual molecules in order to explore the contribution of bonding motifs to these properties. Feature descriptors evaluated include Morgan fingerprints, E-state vectors, a custom "sum over bonds" descriptor, and coulomb matrices. Algorithms discussed include kernel ridge regression, least absolute shrinkage and selection operator ("LASSO") regression, Gaussian process regression, and the multi-layer perceptron (a neural network). Effects of regularization, kernel selection, network parameters, and dimensionality reduction are discussed. We determine that even when using a small training set, non-linear regression methods may create models within a useful error tolerance for screening of materials.

# BibTeX Citation

```
@article{Barnes2018machine,
   author = {Barnes, B. C. and Elton, D.~C. and Boukouvalas, Z. and {Taylor}, D.~E. and Mattson, W.~D. and {Fuge}, M.~D. and {Chung}, P.~W.},
    title = "{Machine Learning of Energetic Material Properties}",
  journal = {ArXiv e-prints},
archivePrefix = "arXiv",
   eprint = {1807.06156},
 primaryClass = "cond-mat.mtrl-sci",
 keywords = {Condensed Matter - Materials Science, Physics - Chemical Physics, Physics - Computational Physics},
     year = 2018,
    month = jul,
}
```
