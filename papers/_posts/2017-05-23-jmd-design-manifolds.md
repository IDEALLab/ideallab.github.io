---
layout: paper
title: "Design Manifolds Capture the Intrinsic Complexity and Dimension of Design Spaces"
year: "2017"
shortref: "Wei Chen, Mark Fuge, and Jonah Chazan <i>JMD</i> 2017"
nickname: design-manifolds
journal: "Journal of Mechanical Design"
volume: 
issue: 
pages: 
authors: "Wei Chen, Mark Fuge, and Jonah Chazan"
image: /assets/images/papers/design_manifolds.png
redirect_from: 
fulltext: "http://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=2610207"
pdf: /assets/pdfs/chen_design_manifolds_jmd_2017.pdf
pdflink: 
github: "https://github.com/IDEALLab/design_embeddings_jmd_2016"
doi: "10.1115/1.4036134"
category: paper
published: true
tags: [manifolds]
---
{% include JB/setup %}

# Abstract 

This paper shows how to measure the intrinsic complexity and dimensionality of a design space. It assumes that high-dimensional design parameters actually lie in a much lower-dimensional space that represents semantic attributes—a design manifold. Past work has shown how to embed designs using techniques like autoencoders; in contrast, the method proposed in this paper first captures the inherent properties of a design space and then chooses appropriate embeddings based on the captured properties. We demonstrate this with both synthetic shapes of controllable complexity (using a generalization of the ellipse called the superformula) and real-world designs (glassware and airfoils). We evaluate multiple embeddings by measuring shape reconstruction error, pairwise distance preservation, and captured semantic attributes. By generating fundamental knowledge about the inherent complexity of a design space and how designs differ from one another, our approach allows us to improve design optimization, consumer preference learning, geometric modeling, and other design applications that rely on navigating complex design spaces. Ultimately, this deepens our understanding of design complexity in general.


# BibTeX Citation

```
@article{chen2017design,
  title={Design Manifolds Capture the Intrinsic Complexity and Dimension of Design Spaces},
  author={Chen, Wei and Fuge, Mark and Chazan, Jonah},
  journal={Journal of Mechanical Design},
  volume={139},
  number={5},
  pages={051102},
  year={2017},
  publisher={American Society of Mechanical Engineers},
  doi={10.1115/1.4036134}
}
```
