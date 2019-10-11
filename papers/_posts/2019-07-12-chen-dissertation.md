---
layout: paper
title: "Data-Driven Geometric Design Space Exploration and Design Synthesis"
year: "2019"
shortref: "Wei Chen 2019"
nickname: chen_dissertation
journal: 
volume: 
issue: 
pages: 
authors: "Wei Chen"
image: /assets/themes/lab/images/logo/ideal_logo_dark.png
redirect_from: 
fulltext: "https://drum.lib.umd.edu/handle/1903/25175"
pdf: /assets/pdfs/chen_dissertation.pdf
pdflink: 
github:
doi: doi.org/10.13016/qwkq-qmtw
category: phdthesis
published: true
tags: [chen_dissertation]
---
{% include JB/setup %}

# Abstract 

A design space is the space of all potential design candidates. While the design space can be of any kind, this work focuses on exploring geometric design spaces, where geometric parameters are used to represent designs and will largely affect a given design's functionality or performance (e.g., airfoil, hull, and car body designs). By exploring the design space, we evaluate different design choices and look for desired solutions. However, a design space may have unnecessarily high dimensionality and implicit boundaries, which makes it difficult to explore. Also, if we synthesize new designs by randomly sampling design variables in the high-dimensional design space, there is high chance that the designs are not feasible, as there is correlation between feasible design variables. This dissertation introduces ways of capturing a compact representation (which we call a latent space) that describes the variability of designs, so that we can synthesize designs and explore design options using this compact representation instead of the original high-dimensional design variables. The main research question answered by this dissertation is: how does one effectively learn this compact representation from data and efficiently explore this latent space so that we can quickly find desired design solutions? The word "quickly" here means to eliminate or reduce the iterative ideation, prototyping, and evaluation steps in a conventional design process. This also reduces human intervention, and hence facilitates design automation. This work bridges the gap between machine learning and geometric design in engineering. It contributes new pieces of knowledge within two topics: design space exploration and design synthesis. Specifically, the main contributions are: 1. A method for measuring the intrinsic complexity of a design space based on design data manifolds. 2. Machine learning models that incorporate prior knowledge from the domain of design to improve latent space exploration and design synthesis quality. 3. New design space exploration tools that expand the design space and search for desired designs in an unbounded space. 4. Geometrical design space benchmarks with controllable complexity for testing data-driven design space exploration and design synthesis.




# BibTeX Citation

```
@phdthesis{chen2019data,
  title={Data-Driven Geometric Design Space Exploration and Design Synthesis},
  author={Chen, Wei},
  year={2019}
}
```
