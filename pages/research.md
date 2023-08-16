---
title: Research Interests
layout: page
---


### Unsupervised statistical methods and differential analyses

I am interested in developing scalable statistical methods for unsupervised analyses of data from high-throughput genomic platforms, including spatially-resolved transcriptomics and single-cell RNA sequencing. Recent projects include the development of a scalable method to identify spatially variable genes ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)) and a collaborative analysis of spatial and single-nucleus data from the locus coeruleus region in postmortem human brain samples ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)). Previously, I developed an unsupervised analysis workflow during a collaborative analysis of spatially-resolved transcriptomics data from the dorsolateral prefrontal cortex (DLPFC) in postmortem human brain samples ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)).

Methods for differential analyses are used to identify biological features such as differential abundance of cell types or differential expression states within cell types between groups of samples in different biological conditions, such as diseased vs. healthy. I have led the development of an improved computational framework for differential analyses ([diffcyt](https://bioconductor.org/packages/diffcyt) ([Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5)) and contributed to the development of a comprehensive data analysis workflow in high-dimensional cytometry data ([Nowicka et al. 2019](https://f1000research.com/articles/6-748)).


---


### Neuroscience and cancer biology

My statistical and computational methodological work is motivated by collaborative projects in neuroscience and cancer biology. Spatially-resolved measurements are especially informative in these systems, due to the presence of highly spatially defined biological structures.

Recent collaborations include an analysis of spatial and single-nucleus data from the locus coeruleus region in postmortem human brain samples ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)), contributions to an analysis of spatially-resolved transcriptomics data from the human dorsolateral prefrontal cortex (DLPFC) ([Maynard and Collado-Torres et al. 2021](https://www.nature.com/articles/s41593-020-00787-0)), and a benchmark evaluation of methods for genetic variation-based demultiplexing of pooled single-cell RNA sequencing samples from tumor samples from high-grade serous ovarian cancer (HGSOC) and lung adenocarcinoma ([Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).


---


### Applications of spatial statistics

Spatially-resolved transcriptomics data consist of gene expression measurements for up to thousands of genes at up to thousands of spatial locations within tissue sections. Recent advances in statistical methodology and computational implementations in spatial statistics, such as nearest-neighbor Gaussian processes (NNGPs), enable us to analyze these data in a more efficient and spatially-aware manner, for example to identify spatially variable genes or perform spatially-aware clustering. I recently led a project to adapt these methods to the context of spatially-resolved transcriptomics to identify spatially variable genes ([nnSVG](https://bioconductor.org/packages/nnSVG), [Weber et al. 2023](https://www.nature.com/articles/s41467-023-39748-z)), and applied this framework to data from postmortem human brain samples from the locus coeruleus region ([Weber and Divecha et al. 2023](https://elifesciences.org/reviewed-preprints/84628)).


---


### Benchmarking, software infrastructure, and analysis workflows

Statistical and computational methods development requires rigorous benchmarking of new methods against existing and baseline methods. Together with several international research groups, I led a project to develop guidance on how to perform different types of benchmarking studies ([Weber et al. 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1738-8)). Previously, I performed a systematic benchmark comparison of clustering methods for high-dimensional cytometry data ([Weber and Robinson 2016](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030)), as well as comprehensive benchmarks during several additional computational projects (including [Weber et al. 2019](https://www.nature.com/articles/s42003-019-0415-5) and [Weber et al. 2021](https://academic.oup.com/gigascience/article/10/9/giab062/6374209)).

I am motivated to develop accessible software infrastructure and well-documented analysis workflows to demonstrate the use of computational methods, show how different methods connect in analysis workflows, and empower other researchers to analyze high-throughput genomic data in a rigorous and reproducible manner. To this end, I have co-led the development of software and data infrastructure for spatially-resolved transcriptomics datasets within the R/Bioconductor framework ([SpatialExperiment](https://bioconductor.org/packages/SpatialExperiment) ([Righelli, Weber, Crowell et al. 2022](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btac299/6575443)), and I am coordinating a collaborative effort to develop an interactive online textbook demonstrating key steps in a computational analysis workflow for spatially-resolved transcriptomics data, including examples of R code and datasets ([Orchestrating Spatially-Resolved Transcriptomics Analysis with Bioconductor (OSTA)](https://lmweber.org/OSTA-book/)).


---


### Open science

I support principles of open science, including the release of freely accessible open-source software, reproducible analyses, code and data resources, and publication of preprints. Open science improves the reliability and reproducibility of research outputs, and leads to faster scientific advances by enabling researchers to build on each others' work. In January 2021, my efforts to create open code and data resources were recognized with a [Research Symbiont award](https://researchsymbionts.org/).

