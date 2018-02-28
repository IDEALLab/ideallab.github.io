---
layout: paper
title: "Beyond the Known: Detecting Novel Feasible Domains over an Unbounded Design Space"
year: "2017"
shortref: "Wei Chen and Mark Fuge <i>JMD</i> 2017"
nickname: feasible-designs
journal: "Journal of Mechanical Design"
volume: "139"
issue: "11"
pages: "111405-111405-10"
authors: "Wei Chen and Mark Fuge"
image: /assets/images/papers/feasible_designs.png
redirect_from: 
fulltext: "http://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=2645709"
pdf: /assets/pdfs/chen_feasible_designs_jmd_2017.pdf
pdflink: 
github: [GitHub](https://github.com/IDEALLab/domain_expansion_jmd_2017)
doi: "10.1115/1.4037306"
category: paper
published: true
tags: [sampling]
---
{% include JB/setup %}

# Abstract 

To solve a design problem, sometimes it is necessary to identify the feasible design space. For design spaces with implicit constraints, sampling methods are usually used. These methods typically bound the design space; that is, limit the range of design variables. But bounds that are too small would fail to cover all possible designs; while bounds that are too large would waste sampling budget. This paper tries to solve the problem of efficiently discovering (possibly disconnected) feasible domains in an unbounded input data space. We propose a data-driven adaptive sampling technique -- epsilon-margin sampling, which both learns the domain boundary of feasible designs, while also expanding our knowledge of the design space as available budget increases. This technique is data-efficient, in that it makes principled probabilistic trade-offs between refining existing domain boundaries versus expanding the design space. We demonstrate that this method can better identify feasible domains on standard test functions compared to both random and active sampling (via uncertainty sampling). However, a fundamental problem when applying adaptive sampling to real world designs is that designs often have high dimensionality and thus require (in the worst case) exponentially more samples per dimension. We show how coupling Design Manifolds with epsilon-margin sampling allows us to actively expand high-dimensional design spaces without incurring this exponential penalty. We demonstrate this on real-world examples of glassware and bottle design, where our method discovers designs that have different appearance and functionality from its initial design set.


# BibTeX Citation

```
@article{chen2017beyond,
  title={Beyond the known: Detecting novel feasible domains over an unbounded design space},
  author={Chen, Wei and Fuge, Mark},
  journal={Journal of Mechanical Design},
  volume={139},
  number={11},
  pages={111405-111405-10},
  year={2017},
  publisher={American Society of Mechanical Engineers}
}
```
