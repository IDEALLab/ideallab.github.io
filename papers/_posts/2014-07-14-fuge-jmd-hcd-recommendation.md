---
layout: paper
title: "Machine Learning Algorithms for Recommending Design Methods"
year: "2014"
shortref: "Fuge <i>et al. JMD</i> 2014"
nickname: fuge-jmd-hcd-recommendation
journal: "Journal of Mechanical Design"
volume: 136
issue: 10
pages: 
authors: "Mark Fuge, Bud Peters, and Alice Agogino"
image: /assets/images/papers/jmd_2014_method_pr_curve.png
redirect_from: 
fulltext: http://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=1892766
pdf: /assets/pdfs/2014_jmd_fuge_peters_hcd_methods.pdf
pdflink: 
github: "https://github.com/IDEALLab/design_method_recommendation_JMD_2014"
doi: 10.1115/1.4028102
category: paper
published: true
tags: [machine-learning, design-methods]
---
{% include JB/setup %}

# Abstract 

Every year design practitioners and researchers develop new methods for understanding users and solving problems. This increasingly large collection of methods causes a problem for novice designers: How does one choose which design methods to use for a given problem? Experienced designers can provide case studies that document which methods they used, but studying these cases to infer appropriate methods for a novel problem is inefficient. This research addresses that issue by applying techniques from content-based and collaborative filtering to automatically recommend design methods, given a particular problem. Specifically, we demonstrate the quality with which different algorithms recommend 39 design methods out of an 800+ case study dataset. We find that knowing which methods occur frequently together allows one to recommend design methods more effectively than just using the text of the problem description itself. Furthermore, we demonstrate that automatically grouping frequently co-occurring methods using spectral clustering replicates human-provided groupings to 92% accuracy. By leveraging existing case studies, recommendation algorithms can help novice designers efficiently navigate the increasing array of design methods, leading to more effective product design.


# BibTeX Citation

```
@article{fuge:jmd_2014_hcd_recommendation,
    author = {Mark Fuge, Bud Peters, and Alice Agogino},
    journal = {Journal of Mechanical Design},
    title = {Machine Learning Algorithms for Recommending Design Methods},
    year = {2014},
    volume = {136},
    number={10},
    month = aug
}
```