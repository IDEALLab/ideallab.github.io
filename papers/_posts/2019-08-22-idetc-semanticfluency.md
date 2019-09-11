---
layout: paper
title: "Using Semantic Fluency Models Improves Network Reconstruction Accuracy of Tacit Engineering Knowledge"
year: "2019"
shortref: "Sexton and Fuge 2019"
nickname: structuring-knowledge-i
journal: "Proceedings of the ASME 2019 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference (IDETC/CIE2019)"
volume:
issue:
pages:  
authors: "Thurston Sexton, Mark D. Fuge"
image: /assets/images/papers/2019_sexton_semanticfluency.png
redirect_from:
fulltext: "https://www.nist.gov/publications/using-semantic-fluency-models-improves-network-reconstruction-accuracy-tacit"
pdf: /assets/pdfs/sexton_semanticfluency_idetc_2019.pdf
pdflink:
github:
doi:
category: paper
published: true
tags: [materials]
---
{% include JB/setup %}

# Abstract

Human- or expert-generated records that describe the behavior of
engineered systems over a period of time can be useful for statistical
learning techniques like pattern detection or output prediction.
However, such data often assumes familiarity of a reader with the
relationships between entities within the system --- that is, knowledge of
the system's structure. This required, but unrecorded "tacit" knowledge
makes it difficult to reliably learn patterns of system behavior using
statistical modeling techniques on these written records. Part of this
difficulty stems from a lack of good models for how engineers generate
written records of a system, given their expertise, since they often
create such records under time pressure using shorthand notation or
internal jargon. In this paper, we model the process of maintenance work
order creation as a modified semantic fluency task, to build a
probabilistic generative model that can uncover underlying relationships
between entities referenced within a complex system. Compared to more
traditional similarity-metric-based methods for structure recovery, we
directly model a possible cognitive process by which technicians may
record work-orders. Mathematically, we represent this as a censored
local random walk over a latent network structure representing tacit
engineering knowledge. This allows us to recover implied engineering
knowledge about system structure by processing written records.
Additionally, we show that our model leads to improved generative
capabilities for synthesizing plausible data.

# BibTeX Citation

```
@inproceedings{Sexton2019Semantic,
    author       =   {Sexton, Thurston and Fuge, Mark},
    title        =   "{Using Semantic Fluency Models Improves Network Reconstruction Accuracy of Tacit Engineering Knowledge}",
    booktitle    =   "{ASME 2019 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference}",
    year         =   2019,
    month        =   August,
    url          =   {https://www.nist.gov/publications/using-semantic-fluency-models-improves-network-reconstruction-accuracy-tacit},
    organization =   {American Society of Mechanical Engineers}
}
```
