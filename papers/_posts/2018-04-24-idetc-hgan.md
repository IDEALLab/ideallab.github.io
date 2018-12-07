---
layout: paper
title: "Synthesizing Designs with Inter-part Dependencies Using Hierarchical Generative Adversarial Networks"
year: "2018"
shortref: "Wei Chen, Ashwin Jeyaseelan, and Mark Fuge <i>ASME IDETC</i> 2018"
nickname: hgan
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Wei Chen, Ashwin Jeyaseelan, and Mark Fuge"
image: /assets/images/papers/hgan.svg
redirect_from: 
fulltext: 
pdf: /assets/pdfs/chen_hgan_idetc_2018.pdf
pdflink: 
github: "https://github.com/IDEALLab/hgan_idetc2018"
doi:
category: paper
published: true
tags: [hgan]
---
{% include JB/setup %}

# Abstract 

Real-world designs usually consist of parts with hierarchical dependencies, i.e., the geometry of one component (a child shape) is dependent on another (a parent shape). We propose a method for synthesizing this type of design. It decomposes the problem of synthesizing the whole design into synthesizing each component separately but keeping the inter-component dependencies satisfied. This method constructs a two-level generative adversarial network to train two generative models for parent and child shapes, respectively. We then use the trained generative models to synthesize or explore parent and child shapes separately via a parent latent representation and infinite child latent representations, each conditioned on a parent shape. We evaluate and discuss the disentanglement and consistency of latent representations obtained by this method. We show that shapes change consistently along any direction in the latent space. This property is desirable for design exploration over the latent space.




# BibTeX Citation

```
@inproceedings{chen2018hgan,
    author={Chen, Wei and Jeyaseelan, Ashwin and Fuge, Mark},
    title={Synthesizing Designs with Inter-part Dependencies Using Hierarchical Generative Adversarial Networks},
    booktitle={ASME 2018 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
    year={2018},
    month={Aug},
    publisher={ASME},
    address={Quebec City, Canada}
}
```
