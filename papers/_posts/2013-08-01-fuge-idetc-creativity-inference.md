---
layout: paper
title: "Automatically Inferring Metrics for Design Creativity"
year: "2013"
shortref: "Fuge <i>et al. ASME IDETC</i> 2013"
nickname: fuge-inferring-creativity-metrics
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Mark Fuge, Josh Stroud, and Alice Agogino"
image: /assets/images/papers/creativity_system.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/Fuge_DETC2013-12620.pdf
pdflink: 
github: "https://github.com/IDEALLab/creativitymetrics"
doi: 
category: paper
published: true
tags: [creativity, machine learning]
---
{% include JB/setup %}

# Abstract 

Measuring design creativity is crucial to evaluating the effectiveness of idea generation methods. Historically, there has been a divide between easily-computable metrics, which are often based on arbitrary scoring systems, and human judgement metrics, which accurately reflect human opinion but rely on the expensive collection of expert ratings. This research bridges this gap by introducing a probabilistic model that computes a family of repeatable creativity metrics trained on expert data. Focusing on metrics for variety, a combination of submodular functions and logistic regression generalizes existing metrics, accurately recovering several published metrics as special cases and illuminating a space of new metrics for design creativity. When tasked with predicting which of two sets of concepts has greater variety, our model matches two commonly used metrics to 96% accuracy on average. In addition, using submodular functions allows this model to efficiently select the highest variety set of concepts when used in a design synthesis system.


# BibTeX Citation

```
@inproceedings{fuge:creativity_inference,
    address = {Portland, U.S.A.},
    author = {Mark Fuge, Josh Stroud, and Alice Agogino},
    booktitle = {ASME International Design Engineering Technical Conferences},
    day = {4-7},
    month = aug,
    title = {{Automatically Inferring Metrics for Design Creativity}},
    year = {2013}
}
```