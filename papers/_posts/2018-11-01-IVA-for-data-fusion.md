---
layout: paper
title: "Independent Vector Analysis for Data Fusion Prior to Molecular Property Prediction with Machine Learning"
year: "2018"
shortref: "Boukouvalas et al. 2018"
nickname: IVA-for-data-fusion
journal: "Neural Information Processing Systems (NeurIPS) workshop on Machine Learning for Molecules and Materials"
volume:
issue:
pages:  
authors: "Zois Boukouvalas, Daniel C. Elton, Peter W. Chung, Mark D. Fuge"
image: /assets/images/papers/2018_IVA_for_data_fusion_MAE_boxplot.png
redirect_from:
fulltext: "https://arxiv.org/abs/1811.00628"
pdf: /assets/pdfs/2018_IVA_for_data_fusion.pdf
pdflink:
github:
doi:
category: paper
published: true
tags: [materials]
---
{% include JB/setup %}

# Abstract

Due to its high computational speed and accuracy compared to ab initio quantum chemistry and forcefield modeling, the prediction of molecular properties using machine learning has received great attention in the fields of materials design and drug discovery. A main ingredient required for machine learning is a training dataset consisting of molecular features; for example fingerprint bits, chemical descriptors, etc. that adequately characterize the corresponding molecules. However, choosing features for any application is highly non-trivial. No "universal" method for feature selection exists. In this work, we propose a data fusion framework that uses Independent Vector Analysis to exploit underlying complementary information contained in different molecular featurization methods, bringing us a step closer to automated feature generation. Our approach takes an arbitrary number of individual feature vectors and automatically generates a single, compact (low dimensional) set of molecular features that can be used to enhance the prediction performance of regression models. At the same time our methodology retains the possibility of interpreting the generated features to discover relationships between molecular structures and properties. We demonstrate this on the QM7b dataset for the prediction of several properties such as atomization energy, polarizability, frontier orbital eigenvalues, ionization potential, electron affinity, and excitation energies. In addition, we show how our method helps improve the prediction of experimental binding affinities for a set of human BACE-1 inhibitors. To encourage more widespread use of IVA we have developed the PyIVA Python package, an open source code which is available for download on Github.

# BibTeX Citation

```
@inproceedings{Boukouvalas2018Independent,
   author = {Boukouvalas, Z. and Elton, D.~C. and Chung, P.~W. and Fuge, M.~D.},
    title = "{Independent Vector Analysis for Data Fusion Prior to Molecular Property Prediction with Machine Learning}",
    booktitle={Machine Learning for Molecules and Materials NeurIPS 2018 Workshop},
    year = 2018,
    month = dec,
    url = {http://www.quantum-machine.org/workshops/nips2018/}
    publisher={},
    address={Montreal, Canada}
}

```
