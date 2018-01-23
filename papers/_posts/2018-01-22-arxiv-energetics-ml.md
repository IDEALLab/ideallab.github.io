---
layout: paper
title: "Applying machine learning techniques to predict the properties of energetic materials"
year: "2018"
shortref: "Elton et al. ArXiV 2018"
nickname: ml-for-energetics-arxiv
journal: "ArXiV"
volume: 
issue: 
pages: 
authors: "Dan Elton, Zois Boukouvalas, Mark Butrico, Mark Fuge, Peter Chung"
image: /assets/images/papers/aes.png
redirect_from: 
fulltext: "https://arxiv.org/abs/1801.04900"
pdf: /assets/pdfs/2018_elton_ml_for_energetics_arxiv.pdf
pdflink: 
github: 
doi: 
category: paper
published: true
tags: [materials]
---
{% include JB/setup %}

# Abstract 

We present a proof of concept that machine learning techniques can be used to predict the properties of CNOHF energetic molecules from their molecular structures. We focus on a small but diverse dataset consisting of 109 molecular structures spread across ten compound classes. Up until now, candidate molecules for energetic materials have been screened using predictions from expensive quantum simulations and thermochemical codes. We present a comprehensive comparison of machine learning models and several molecular featurization methods - sum over bonds, custom descriptors, Coulomb matrices, Bag of Bonds, and fingerprints. The best featurization was sum over bonds (bond counting), and the best model was kernel ridge regression. Despite having a small data set, we obtain acceptable errors and Pearson correlations for the prediction of detonation pressure, detonation velocity, explosive energy, heat of formation, density, and other properties out of sample. By including another dataset with ~300 additional molecules in our training we show how the error can be pushed lower, although the convergence with number of molecules is slow. Our work paves the way for future applications of machine learning in this domain, including automated lead generation and interpreting machine learning models to obtain novel chemical insights.


# BibTeX Citation

```
@article{elton2018applying,
  title={Applying machine learning techniques to predict the properties of energetic materials},
  author={Elton, Daniel C and Boukouvalas, Zois and Butrico, Mark S and Fuge, Mark D and Chung, Peter W},
  journal={arXiv preprint arXiv:1801.04900},
  year={2018}
}
```
