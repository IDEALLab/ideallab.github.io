---
layout: paper
title: "Diverse Weighted Bipartite b-Matching"
year: "2017"
shortref: "Faez Ahmed, John P. Dickerson and Mark Fuge <i>IJCAI</i> 2017"
nickname: diverse-matching
journal: "Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence"
volume: 
issue: 
pages: 
authors: "Faez Ahmed, John P. Dickerson and Mark Fuge"
image: /assets/images/papers/2017_ahmed_diverse.jpg
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2017_ahmed_diverse.pdf
pdflink: 
github: 
doi: "10.24963/ijcai.2017/6"
category: paper
published: true
tags: [diverse]
---
{% include JB/setup %}

# Abstract 

Bipartite matching, where agents on one side of a market are matched to agents or items on the other, is a classical problem in computer science and economics, with widespread application in healthcare, education, advertising, and general resource allocation. A practitioner’s goal is typically to maximize a matching market’s economic efficiency, possibly
subject to some fairness requirements that promote equal access to resources. A natural balancing act exists between fairness and efficiency in matching markets, and has been the subject of much research. In this paper, we study a complementary goal—balancing diversity and efficiency—in a generalization of bipartite matching where agents on one side of the market can be matched to sets of agents on the other. Adapting a classical definition of the diversity of a set, we propose a quadratic
programming-based approach to solving a super-modular minimization problem that balances diversity and total weight of the solution. We also provide a scalable greedy algorithm with theoretical performance bounds. We then define the price of diversity, a measure of the efficiency loss due to enforcing diversity, and give a worst-case theoretical bound. Finally, we demonstrate the efficacy of our methods on three real-world datasets, and show that the price of diversity is not bad in practice. Our
code is publicly accessible for further research.

# BibTeX Citation

```
@inproceedings{ahmed:ijcai_2017_diverse,
    address = {Melbourne, Australia},
    author = {Faez Ahmed, John Dickerson, and Mark Fuge},
    booktitle = {Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence},
    title = {Diverse Weighted Bipartite b-Matching},
    month = {August},
    year = {2017},
    publisher = {AAAI Press}
}
```


