---
layout: paper
title: "Using natural language processing techniques to extract information on the properties and functionalities of energetic materials from large text corpora"
year: "2019"
shortref: "Elton et al. 2019"
nickname: nlp-chemicals-NTREM
journal: "Proceedings of the 22nd International Seminar in New Trends in Research of Energetic Materials"
volume:
issue:
pages:  
authors: "Daniel C. Elton, Dhruv Turakhia, Nischal Reddy, Zois Boukouvalas, Mark D. Fuge, Ruth M. Doherty, Peter W. Chung"
image: /assets/images/papers/2019_NLP_NTREM_word2vec_embedding_chemical_names.png
redirect_from:
fulltext: "https://arxiv.org/abs/1903.00415"
pdf: /assets/pdfs/2019_nlp_for_extracting_info_on_chemicals_NTREM.pdf
pdflink:
github:
doi:
category: paper
published: true
tags: [nlp, materials]
---
{% include JB/setup %}

# Abstract

The number of scientific journal articles and reports being published about energetic materials every year is growing exponentially, and therefore extracting relevant information and actionable insights from the latest research is becoming a considerable challenge. In this work we explore how techniques from natural language processing and machine learning can be used to automatically extract chemical insights from large collections of documents. We first describe how to download and process documents from a variety of sources - journal articles, conference proceedings (including NTREM), the US Patent & Trademark Office, and the Defense Technical Information Center archive on archive.org. We present a custom NLP pipeline which uses open source NLP tools to identify the names of chemical compounds and relates them to function words ("underwater", "rocket", "pyrotechnic") and property words ("elastomer", "non-toxic"). After explaining how word embeddings work we compare the utility of two popular word embeddings - word2vec and GloVe. Chemical-chemical and chemical-application relationships are obtained by doing computations with word vectors. We show that word embeddings capture latent information about energetic materials, so that related materials appear close together in the word embedding space.

# BibTeX Citation

```
@article{Elton2019Using,
         author = {Elton, Daniel C. and Turakhia, Dhruv and Reddy, Nischal and Boukouvalas, Zois and Fuge, Mark D. and Doherty, Ruth M. and Chung, Peter W.},  
          title = "{Using natural language processing techniques to extract information on the properties and functionalities of energetic materials from large text corpora}",  
        journal = {arXiv e-prints : {1903.00415},  
           year = "2019",  
          month = "Mar",  
         eprint = {1903.00415},  
   primaryClass = {cs.CL},  
   keywords = {Computer Science - Computation and Language, Condensed Matter - Materials Science},  
}
```
