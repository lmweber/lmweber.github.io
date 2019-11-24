---
layout: page
title: Research
---


I am interested in a variety of problems related to data analysis, statistical methodology, software development, and benchmarking for the interpretation of high-throughput biological data, especially single-cell data.



### What is a cell type?

From a biological perspective, I am interested in the fundamental question of "what is a cell type?". By learning from datasets generated using new single-cell technologies (e.g. single-cell RNA sequencing, high-dimensional cytometry, single-cell epigenomics, as well as multi-modal technologies), it is possible to refine definitions of known cell types and states according to their molecular profiles, potentially discover new cell types and transient states in health and disease, and address fundamental biological questions regarding the nature of cells and cell types. This question motivates several aspects of my methodological work.



### Subtypes of high-grade serous ovarian cancer (HGSOC)

I am currently involved in a collaborative project aimed at identifying the biological basis of subtypes of high-grade serous ovarian cancer (HGSOC) using bulk and single-cell RNA sequencing data. My responsibilities include data analysis, development of computational analysis pipelines, and evaluation of statistical methodologies, especially relating to the deconvolution of cell types in bulk RNA sequencing samples based on cell type signatures from single-cell data. This project is a collaboration between the labs of [Prof. Stephanie Hicks, Johns Hopkins University](https://www.stephaniehicks.com/); [Prof. Casey Greene, University of Pennsylvania](http://www.greenelab.com/); and [Prof. Jennifer Doherty, University of Utah](https://uofuhealth.utah.edu/huntsman/labs/doherty/).



### Differential analysis in high-dimensional cytometry data

During my PhD in the lab of [Prof. Mark Robinson, University of Zurich](https://robinsonlabuzh.github.io/), I worked on several projects relating to differential analysis in high-dimensional cytometry data. High-dimensional cytometry refers to a set of technologies that enable measurement of expression levels of around 20--100 proteins in thousands to millions of cells, using targeted antibody-based probes (including multicolor flow cytometry, mass cytometry or CyTOF, and sequence-based or genomic cytometry). Differential analysis experiments aim to detect groups of cells with differing characteristics between samples in different conditions, e.g. diseased vs. healthy. This can include differential abundance of cell types, as well as differential states (e.g. signaling or other functional states) for specific cell types of interest.

Key publications related to this theme (which I either led or contributed to) include the following:

- **Weber L.M.**, Nowicka N., Soneson C., and Robinson M.D. (2019), [*diffcyt: Differential discovery in high-dimensional cytometry via high-resolution clustering*](https://www.nature.com/articles/s42003-019-0415-5), Communications Biology, 2, 183.

    In this paper, we developed a new computational framework (*diffcyt*) for differential discovery analyses in high-dimensional cytometry data, with extensive benchmarking against existing approaches. The *diffcyt* framework is freely available as an R package from [Bioconductor](http://bioconductor.org/packages/diffcyt).

- Nowicka N., Krieg C., Crowell H.L., **Weber L.M.**, Hartmann F.J., Guglietta S., Becher B., Levesque M.P., and Robinson M.D. (2017; updated 2019), [*CyTOF workflow: differential discovery in high-throughput high-dimensional cytometry datasets*](https://f1000research.com/articles/6-748), F1000Research, 6:748, v3.

    This paper describes a complete computational workflow for differential discovery analyses in high-dimensional cytometry data, based largely on R/Bioconductor packages. Comprehensive R code is provided within the publication, for steps including preprocessing, exploratory analyses, differential testing, and visualizations. The code is also provided in the form of a [Bioconductor workflow](https://bioconductor.org/packages/cytofWorkflow) package.



### Comparison of clustering algorithms

During my PhD, I performed an extensive benchmark of clustering algorithms for high-dimensional cytometry data. Clustering represents a key preprocessing step in computational workflows: measurements from individual cells are summarized by grouping them into clusters representing cell types, which can then be further investigated, e.g. by differential testing.

Due to the rapidly increasing dimensionality of datasets from new technologies (in particular mass cytometry or CyTOF), a number of research groups had developed new clustering algorithms designed for these data types. However, these algorithms had not yet been comprehensively compared in an independent evaluation. In our benchmark, we compared freely available clustering algorithms, using several publicly available datasets containing a known ground truth. A key result was that the [FlowSOM](https://bioconductor.org/packages/FlowSOM) algorithm (Van Gassen et al. 2015) gave both excellent performance and fast runtimes; we subsequently used this algorithm in our work on differential analysis.

These results are described in the following publication:

- **Weber L.M.** and Robinson M.D. (2016), [*Comparison of clustering methods for high‐dimensional single‐cell flow and mass cytometry data*](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030), Cytometry Part A, 89A, 12, 1084--1096.



### Benchmarking guidelines

Benchmarking has represented a key component of the work during several of my previous projects. Thorough benchmarking of methods is crucial during computational work --- for example, when developing new methods, or independent comparisons to provide recommendations for other users. However, in practice, many benchmarks do not fulfill their aims. For example, they may be too narrow in scope, or fail to consider important design details such as comparable levels of parameter optimization.

In order to assist other computational researchers interested in benchmarking, we coordinated a review paper summarizing key practical guidelines and recommendations for performing high-quality benchmarks, based on our experiences in computational biology. The paper was drafted in collaboration with members of three external research groups, who have also been extensively involved in benchmarking:

- **Weber L.M.**, Saelens W., Cannoodt R., Soneson C., Hapfelmeier A., Gardner P.P., Boulesteix A.-L., Saeys Y., and Robinson M.D. (2019), [*Essential guidelines for computational method benchmarking*](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1738-8), Genome Biology, 20, 125.



### Future projects

I am interested in projects that aim to rigorously evaluate and establish statistical practices in the analysis of high-throughput biological data, as well as assisting experimental researchers to access and use suitable computational methods. Specific issues that I plan to work more on in the future include:

- benchmarking of new classes of methods from machine learning (e.g. generative adversarial networks, GANs)
- data analysis for single-cell multi-modal data (e.g. transcriptomic and proteomic data from the same cells)
- data analysis for spatial data (e.g. spatial transcriptomics)
- computational workflows (user-friendly and modular)
- experimental design
- data preprocessing procedures (e.g. normalization of single-cell data)


