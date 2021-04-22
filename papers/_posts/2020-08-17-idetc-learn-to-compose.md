---
layout: paper
title: "Learning to Abstract and Compose Mechanical Device Function and Behavior"
year: "2020"
shortref: "Jun Wang, Kevin Chiu, and Mark Fuge <i>ASME IDETC</i> 2020"
nickname: learn-to-compose
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Jun Wang, Kevin Chiu, and Mark Fuge"
image: /assets/images/papers/2020-08-17-idetc-gnn.jpg
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2020_jun_Learn_to_compose_IDETC.pdf
pdflink: 
github: "https://github.com/IDEALLab/DeepCFD"
doi: 
category: paper
published: true
tags: [learn-to-compose]
---
{% include JB/setup %}

# Abstract 

While current neural networks (NNs) are becoming good at deriving single types of abstractions for a small set of phenomena, for example, using a single NN to predict a flow velocity field, NNs are not good at composing large systems as compositions of small phenomena and reasoning about their interactions. We want to study how NNs build both the abstraction and composition of phenomena when a single NN model cannot suffice. Rather than a single NN that learns one physical or social phenomenon, we want a group of NNs that learn to abstract, compose, reason, and correct the behaviors of different parts in a system. In this paper, we investigate the joint use of Physics-Informed (Navier-Stokes equations) Deep Neural Networks (i.e., Deconvolutional Neural Networks) as well as Geometric Deep Learning (i.e., Graph Neural Networks) to learn and compose fluid component behavior. Our models successfully predict the fluid flows and their composition behaviors (i.e., velocity fields) with an accuracy of about 99%.


# BibTeX Citation

```
@inproceedings{wang2020learning,
  title={Learning to Abstract and Compose Mechanical Device Function and Behavior},
  author={Wang, Jun and Chiu, Kevin and Fuge, Mark},
  booktitle={ASME 2020 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
  year={2020},
  organization={American Society of Mechanical Engineers Digital Collection}
}
```
