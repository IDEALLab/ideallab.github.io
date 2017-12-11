---
layout: paper
title: "Ranking ideas for diversity and quality"
year: "2017"
shortref: "Faez Ahmed and Mark Fuge <i>JMD</i> 2017"
nickname: ranking-diversity
journal: "Journal of Mechanical Design"
volume: "140"
issue: "1"
pages: 
authors: "Faez Ahmed and Mark Fuge"
image: /assets/images/papers/diverse_rank.jpg
redirect_from: 
fulltext: "http://mechanicaldesign.asmedigitalcollection.asme.org/article.aspx?articleid=2656866"
pdf: /assets/pdfs/2017_ahmed_ranking.pdf
pdflink: 
github: "https://github.com/IDEALLab/ranking_diversity_jmd_2017"
doi: "10.1115/1.4038070"
category: paper
published: true
tags: [diversity]
---
{% include JB/setup %}

# Abstract 

When selecting ideas or trying to find inspiration, designers often must sift through hundreds or thousands of ideas. This paper provides an algorithm to rank design ideas such that the ranked list simultaneously maximizes the quality and diversity of recommended designs. To do so, we first define and compare two diversity measures using Determinantal Point Processes (DPP) and additive sub-modular functions. We show that DPPs are more suitable for items expressed as text and that a greedy algorithm diversifies rankings with both theoretical guarantees and empirical performance on what is otherwise an NP-Hard problem. To produce such rankings, this paper contributes a novel way to extend quality and diversity metrics from sets to permutations of ranked lists.

These rank metrics open up the use of multi-objective optimization to describe trade-offs between diversity and quality in ranked lists. We use such trade-off fronts to help designers select rankings using indifference curves. However, we also show that rankings on trade-off front share a number of top-ranked items; this means reviewing items (for a given depth like the top 10) from across the entire diversity-to-quality front incurs only a marginal increase in the number of designs considered. While the proposed techniques are general purpose enough to be used across domains, we demonstrate concrete performance on selecting items in an online design community (OpenIDEO), where our approach reduces the time required to review diverse, high-quality ideas from around 25 hours to 90 minutes. This makes evaluation of crowd-generated ideas tractable for a single designer. Our code is publicly accessible for further research.


# BibTeX Citation

```
@article{ahmed2017ranking,
  title={Ranking ideas for diversity and quality},
  author={Ahmed, Faez and Fuge, Mark},
  journal={Journal of Mechanical Design},
  volume={140},
  issue={1},
  pages={011101},
  year={2017},
  publisher={American Society of Mechanical Engineers}
}
```
