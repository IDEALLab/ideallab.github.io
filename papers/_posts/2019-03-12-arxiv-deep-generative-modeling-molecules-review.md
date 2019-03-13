---
layout: paper
title: "Deep learning for molecular generation and optimization - a review of the state of the art"
year: "2019"
shortref: "Elton et al. 2019"
nickname: DL-molecules-review
journal:
volume:
issue:
pages:  
authors: "Daniel C. Elton, Zois Boukouvalas, Mark D. Fuge, Peter W. Chung"
image: /assets/images/papers/2019_GAN_for_molecules.png
redirect_from:
fulltext: "https://arxiv.org/abs/1903.04388"
pdf:
pdflink: "https://arxiv.org/pdf/1903.00415.pdf"
github:
doi:
category: paper
published: true
tags: [deep learning, machine learning, AI, molecules, materials]
---
{% include JB/setup %}

# Abstract

In the space of only a few years, deep generative modeling has revolutionized how we think of artificial creativity, yielding autonomous systems which produce original images, music, and text. Inspired by these successes, researchers are now applying deep generative modeling techniques to the generation and optimization of molecules - in our review we found 45 papers on the subject published in the past two years. These works point to a future where such systems will be used to generate lead molecules, greatly reducing resources spent downstream synthesizing and characterizing bad leads in the lab. In this review we survey the increasingly complex landscape of models and representation schemes that have been proposed. The four classes of techniques we describe are recursive neural networks, autoencoders, generative adversarial networks, and reinforcement learning. After first discussing some of the mathematical fundamentals of each technique, we draw high level connections and comparisons with other techniques and expose the pros and cons of each. Several important high level themes emerge as a result of this work, including the shift away from the SMILES string representation of molecules towards more sophisticated representations such as graph grammars and 3D representations, the importance of reward function design, the need for better standards for benchmarking and testing, and the benefits of adversarial training and reinforcement learning over maximum likelihood based training.

# BibTeX Citation

```
@article{Elton2019Deep,
         author = {Elton, Daniel C. and  Boukouvalas, Zois and Fuge, Mark D. and Chung, Peter W.},  
          title = "{Deep learning for molecular generation and optimization - a review of the state of the art}",
          journal = {arXiv e-prints: 1903.04388},  
           year = "2019",  
          month = "Mar",  
         eprint = {1903.00415},  
   primaryClass = {cs.CL},  
   keywords = {Computer Science - Machine Learning, Physics - Chemical Physics, Statistics - Machine Learning},
}
```
