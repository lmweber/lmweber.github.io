---
title: Research Interests
layout: page
---


### Unsupervised statistical methods and differential analyses

I am interested in developing scalable statistical methods for unsupervised analyses of data from high-throughput genomic platforms, including spatially-resolved transcriptomics and single-cell RNA sequencing. Previously, I have performed a systematic benchmark comparison of clustering methods for high-dimensional cytometry data ([Weber and Robinson 2016](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030)), and developed an unsupervised analysis workflow for spatially-resolved transcriptomics data from the dorsolateral prefrontal cortex (DLPFC) in postmortem human brain samples ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)). Recently, I have led the development of an improved method to identify spatially variable genes ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)), as well as a collaborative analysis of spatial and single-nucleus data from the locus coeruleus region in postmortem human brain samples ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)).

Differential analyses aim to identify features such as differential abundance of cell types or differential expression states within cell types between groups of samples in different biologicaly conditions, e.g. diseased vs. healthy. I have been involved in several projects related to differential analyses in high-dimensional cytometry data, including leading the development of an improved computational framework ([diffcyt](https://bioconductor.org/packages/diffcyt) ([Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5)), and contributions to a comprehensive data analysis workflow ([Nowicka et al. 2019](https://f1000research.com/articles/6-748)).


---


### Applications of spatial statistics

Spatially-resolved transcriptomics data consists of gene expression measurements for large sets of genes at a large number of spatial locations within tissue sections. Recent advances in spatial statistical methodology, such as nearest-neighbor Gaussian processes (NNGPs), enable us to analyze these data in a more efficient and spatially-aware manner, for example to identify spatially variable genes or perform spatially-aware clustering. We have recently developed a scalable method to identify spatially variable genes in spatially-resolved transcriptomics data ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)), and applied this method to data from postmortem human brain samples from the locus coeruleus region ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)).


---


### Neuroscience and cancer biology

My statistical methodological work is motivated by collaborative projects in neuroscience and cancer biology. Spatially-resolved measurements are especially informative in these systems due to the presence of highly spatially defined biological features. Recent collaborations include an analysis of spatial and single-nucleus data from the locus coeruleus region in postmortem human brain samples ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)), contributions to an analysis of the spatial landscape of gene expression in the human dorsolateral prefrontal cortex (DLPFC) ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)), as well as an evaluation of methods for genetic variation-based demultiplexing of pooled single-cell RNA sequencing samples from tumor samples from high-grade serous ovarian cancer (HGSOC) and lung adenocarcinoma ([Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).


---


### Benchmarking and software workflows

Statistical and computational methodological development require rigorous benchmarking of new methods against existing methods and baselines. Together with several research groups, I led a project to provide guidance on how best to perform different types of benchmarking studies ([Weber et al. 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1738-8)), and I have also performed several systematic benchmarks during my computational projects ([Weber and Robinson 2016](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030), [Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5), and [Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).

I am also motivated to develop user-friendly software and analysis workflows that will enable other researchers to analyze high-throughput genomic data in a reliable and reproducible manner. I have been involved in a joint project to develop a data structure for storing and manipulating spatially-resolved transcriptomics data within the R/Bioconductor framework ([SpatialExperiment](https://bioconductor.org/packages/SpatialExperiment) ([Righelli, Weber, Crowell et al. 2022](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btac299/6575443)), and I am leading a collaborative effort to develop an interactive online textbook demonstrating key steps in a computational analysis workflow for spatially-resolved transcriptomics data, including examples of R code and datasets ([Orchestrating Spatially-Resolved Transcriptomics Analysis with Bioconductor (OSTA)](https://lmweber.org/OSTA-book/)).


---


### Open science

I support open science principles, including the release of open-source software, reproducible analyses, free availability of code and data resources, and publication of preprints. Open science practices improve the reliability and reproducibility of research outputs, and lead to faster scientific advances by enabling researchers to build on each others' work. In January 2021, my efforts to create open code and data resources were recognized with a [Research Symbiont award](https://researchsymbionts.org/).

