---
layout: paper
title: "Applying machine learning techniques to predict the properties of energetic materials"
year: "2018"
shortref: "Elton et al. 2018"
nickname: ml-for-energetics-arxiv
journal: "Scientific Reports"
volume: 8
issue:
pages:  
authors: "Dan Elton, Zois Boukouvalas, Mark Butrico, Mark Fuge, Peter Chung"
image: /assets/images/papers/2018_elton_ml_for_energetics_arxiv.jpg
redirect_from:
fulltext: "https://www.nature.com/articles/s41598-018-27344-x"
pdf: /assets/pdfs/2018_elton_ml_for_energetics.pdf
pdflink:
github: "https://github.com/delton137/Machine-Learning-Energetic-Molecules-Notebooks"
doi: "10.1038/s41598-018-27344-x"
category: paper
published: true
tags: [materials]
---
{% include JB/setup %}

# Abstract

We present a proof of concept that machine learning techniques can be used to predict the properties of CNOHF energetic molecules from their molecular structures. We focus on a small but diverse dataset consisting of 109 molecular structures spread across ten compound classes. Up until now, candidate molecules for energetic materials have been screened using predictions from expensive quantum simulations and thermochemical codes. We present a comprehensive comparison of machine learning models and several molecular featurization methods - sum over bonds, custom descriptors, Coulomb matrices, Bag of Bonds, and fingerprints. The best featurization was sum over bonds (bond counting), and the best model was kernel ridge regression. Despite having a small data set, we obtain acceptable errors and Pearson correlations for the prediction of detonation pressure, detonation velocity, explosive energy, heat of formation, density, and other properties out of sample. By including another dataset with ~300 additional molecules in our training we show how the error can be pushed lower, although the convergence with number of molecules is slow. Our work paves the way for future applications of machine learning in this domain, including automated lead generation and interpreting machine learning models to obtain novel chemical insights.


# BibTeX Citation

```
@article{Elton2018applying,
  doi = {10.1038/s41598-018-27344-x},
  url = {https://doi.org/10.1038/s41598-018-27344-x},
  year  = {2018},
  month = {jun},
  publisher = {Springer Nature},
  volume = {8},
  number = {1},
  author = {Daniel C. Elton and Zois Boukouvalas and Mark S. Butrico and Mark D. Fuge and Peter W. Chung},
  title = {Applying machine learning techniques to predict the properties of energetic materials},
  journal = {Scientific Reports}
}
```
