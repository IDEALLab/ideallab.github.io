---
layout: paper
title: "Effect of Optimal Geometries and Performance Parameters on Airfoil Latent Space Dimension"
year: "2022"
shortref: "Alec Van Slooten and Mark Fuge <i>ASME IDETC</i> 2022"
nickname: optimized-geometry-airfoil
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Alec Van Slooten and Mark Fuge"
image: /assets/images/papers/2022_vansloot_optimal_geometry_airfoil.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2022_vansloot_optimized_geometry_airfoil.pdf
pdflink: 
github: "https://github.com/IDEALLab/Optimal_Airfoil_Geometry_IDETC2022"
doi: 
category: paper
published: true
tags: [artificial intelligence, data-driven design, design optimization, machine learning]
---
{% include JB/setup %}

# Abstract 
Although learning low-dimensional airfoil manifolds can facilitate aerodynamic optimizations, the properties of these latent spaces are not well understood. This paper investigates airfoil manifolds to provide greater insight into the effects of optimized geometry and data set features on latent spaces. Specifically, we investigate if optimized geometries occupy lower dimensional manifolds than non-optimized geometries. We also examine the effect of including target optimization conditions as data set features for a range of latent space sizes. We explore these areas using the UIUC airfoil database and a subset of these airfoils optimized with CBGAN and CEBGAN models. Lower dimensional airfoil manifolds are learned using both autoencoders and principal component analysis (PCA) models. The performance of these models are also compared to each other in ranges of training sample sizes and latent dimension size using mean squared error (MSE) between the original testing samples and the reprojected data constructed from the models as a metric. The results of this study suggest that optimized geometry does not always lie in a lower dimensional latent space as the two data sets were observed to have similar intrinsic dimensionalities. This study further demonstrates that including input parameters used in airfoil coordinate generation as data set features does not necessarily decrease the latent space dimensionality.



# BibTeX Citation

```
@inproceedings{van_slooten2022opt,
  title={Effect of Optimal Geometries and Performance Parameters on Airfoil Latent Space Dimension},
  author={Van Slooten, Alec and Fuge, Mark},
  booktitle={ASME 2022 International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
  year={2022},
  organization={American Society of Mechanical Engineers Digital Collection}
}
```
