---
layout: paper
title: "Mean Squared Error may lead you astray when Optimizing your Inverse Design methods"
year: "2022"
shortref: "Shai Bernard, Jun Wang, and Mark Fuge <i>ASME IDETC</i> 2022"
nickname: inverse-heat-conduction
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Shai Bernard, Jun Wang, and Mark Fuge"
image: /assets/images/papers/2022_idetc_shai_inverse_heat_conduction.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2022_shai_inverse_heat_conduction_IDTEC.pdf
pdflink: 
github: "https://github.com/IDEALLab/ID_Conduction_IDETC2022"
doi: 
category: paper
published: true
tags: [artificial intelligence, data-driven design, design optimization, generative design, machine learning, inverse design]
---
{% include JB/setup %}

# Abstract 

When performing time-intensive optimization tasks, such as those in Topology Optimization or Shape Optimization, researchers have turned to Machine Learned (ML) Inverse Design methods\textemdash \ie, algorithms that predict the optimized geometry from input conditions\textemdash to either replace or \textit{warm start} traditional optimizers. Almost exclusively, such methods are trained and optimized to reduce the Mean Squared Error between a method's output and a ground truth training dataset of optimized designs, this being the obvious choice for traditional supervised learning. While convenient, we show that this choice may be myopic. Specifically, we compare two methods of optimizing the hyper-parameters of both a random forest (RF) and k-nearest neighbors (KNN) model for predicting the optimal topology in a 2D heat sink example. 

We show that under both direct Inverse Design as well as when warm starting further Topology Optimization (TO), using typical Mean Squared Error metrics produces less performant models than a proposed metric that directly evaluates the objective function, though both methods produce designs that are almost one order of magnitude better than a control condition that uses a uniform initialization common in TO. We also illustrate how warm starting TO with predicted solutions impacts both the convergence time, the type of solutions obtained during optimization, and the final designs. Sensitivity analyses on various model parameters demonstrate that the results are not dependent on other model hyperparameters. Overall, our initial results portend that researchers may need to revisit common choices for evaluating ID methods that subtly trade-off factors in how an ID method will actually be used. We hope our open-source dataset and evaluation environment will spur additional research in those directions


# BibTeX Citation

```
@inproceedings{shai2022mean,
  title={Mean Squared Error may lead you astray when Optimizing your Inverse Design methods},
  author={Bernard, Shai and Wang, Jun and Fuge, Mark},
  booktitle={ASME 2022 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
  year={2022},
  organization={American Society of Mechanical Engineers Digital Collection}
}
```
