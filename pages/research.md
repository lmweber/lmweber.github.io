---
title: Research Interests
layout: page
---


### Unsupervised statistical methods

I am interested in developing improved and scalable methods for unsupervised analyses in high-throughput genomic data, including spatially-resolved transcriptomics, single-cell and single-nucleus RNA sequencing, and high-dimensional cytometry. In previous work, I have performed a systematic benchmark comparison of clustering methods for high-dimensional cytometry data ([Weber and Robinson 2016](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030)), and developed an unsupervised analysis workflow for spatially-resolved transcriptomics data as part of a collaboration on analyzing the spatial landscape of gene expression in the human brain dorsolateral prefrontal cortex (DLPFC) region ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)). Recently, I have led the development of a new, computationally scalable method to identify spatially variable genes in spatially-resolved transcriptomics data ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)), as well as a collaborative, data-driven analysis of spatial and single-nucleus data from the locus coeruleus region in the human brain ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)).


---


### Applications of spatial statistics

Spatially-resolved transcriptomics data (e.g. from the [10x Genomics Visium platform](https://www.10xgenomics.com/products/spatial-gene-expression)) consists of gene expression measurements for thousands of genes at a thousands or more spatial locations on a tissue section. To efficiently analyze these large datasets, we are adapting recent advances in spatial statistical methodology to the genomic context. For example, this will allow us to more efficiently identify spatially variable genes with expression that varies with tissue structures of interest, or perform spatially aware clustering to identify spatial domains representing cell types or other biological structures. We have recently developed a new, computationally scalable method to identify spatially variable genes in spatially-resolved transcriptomics data ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)), and applied this method in the context of data from the human brain ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)).


---


### Biological applications in neuroscience and cancer biology

My methodological work is motivated by collaborative projects in fields including neuroscience and cancer biology. Recent papers from these collaborations include a data-driven analysis of spatial and single-nucleus data from the locus coeruleus region in the human brain ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)), contributions to an analysis of the spatial landscape of gene expression in the dorsolateral prefrontal cortex (DLPFC) region in the human brain ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)), as well as an evaluation of methods for genetic variation-based demultiplexing of pooled single-cell RNA sequencing samples from tumor samples from high-grade serous ovarian cancer (HGSOC) and lung adenocarcinoma ([Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).


---


### Differential analyses

Differential analyses aim to identify features such as differential abundance of cell types or differential expression states within cell types between groups of replicate samples from different conditions, such as diseased and healthy. I have been involved in several computational and methodological projects related to differential analyses in HDCyto data, including leading the development of an improved computational framework for these analyses (*diffcyt*) ([Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5)), and contributions to a comprehensive data analysis workflow ([Nowicka et al. 2019](https://f1000research.com/articles/6-748)).


---


### Benchmarking

Methodological work requires rigorous and systematic benchmarking of new methods against existing methods and baselines. This is a crucial aspect of method development, since it provides information to users about which methods will be most appropriate for their analyses. Together with several research groups interested in benchmarking, I led a project to summarize our views and guidance on how best to perform different types of benchmarking studies, which we summarized in the form of a review ([Weber et al. 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1738-8)). I have also performed several systematic benchmarks during my computational projects ([Weber and Robinson 2016](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030), [Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5), and [Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).


---


### Software workflows

I am motivated to develop user-friendly software and analysis workflows that will enable other researchers to analyze high-throughput genomic data in a reliable and reproducible manner. To facilitate these efforts, I have been involved in a joint project to develop a core data class for storing and manipulating spatially-resolved transcriptomics data within the R/Bioconductor framework (*SpatialExperiment*) ([Righelli, Weber, Crowell et al. 2022](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btac299/6575443)). I am also leading a collaborative effort to develop an interactive online textbook demonstrating key steps in a computational analysis workflow for spatially-resolved transcriptomics data, including examples of R code and datasets ([Orchestrating Spatially-Resolved Transcriptomics Analysis with Bioconductor (OSTA)](https://lmweber.org/OSTA-book/)).


---


### Open science


I support open science principles, including the release of open-source software, reproducible analyses, free availability of code and data resources, and publication of preprints. In my view, open science is better science and leads to faster scientific advances, since open-source software and reproducible code and data repositories allow researchers to easily build on each others' ideas. In January 2021, my efforts to create open code and data resources as part of my computational projects were recognized with a [Research Symbiont award](https://researchsymbionts.org/).

