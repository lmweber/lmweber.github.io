---
layout: page
title: Research Interests
---


### Unsupervised statistical methods

I am interested in developing improved statistical methods for unsupervised analyses in high-throughput and high-dimensional biological data, including spatial transcriptomics, single-cell RNA sequencing, and mass cytometry (CyTOF). This includes techniques such as clustering and dimension reduction. I am also interested in making these methods accessible through the development of user-friendly computational data analysis pipelines.

Key papers:

- **Weber L.M.** and Robinson M.D. (2016), *Comparison of clustering methods for high‐dimensional single‐cell flow and mass cytometry data*, Cytometry Part A, 89A, 12, 1084--1096. Links to: [Paper](https://onlinelibrary.wiley.com/doi/full/10.1002/cyto.a.23030), [Code](https://github.com/lmweber/cytometry-clustering-comparison), [Data](http://flowrepository.org/id/FR-FCM-ZZPH).

    - benchmark paper comparing the performance of clustering algorithms for mass cytometry (CyTOF) data <br/> <br/>

- Maynard K.R.\*, Collado-Torres L.\*, **Weber L.M.**, Uytingco C., Barry B.K., Williams S.R., Catallini J.L. II, Tran M.N., Besich Z., Tippani M., Chew J., Yin Y., Kleinman J.E., Hyde T.M., Rao N., Hicks S.C., Martinowich K.<sup>+</sup>, Jaffe A.E.<sup>+</sup> (2020), *Transcriptome-scale spatial gene expression in the human dorsolateral prefrontal cortex*, bioRxiv, v1. Links to: [Paper](https://www.biorxiv.org/content/10.1101/2020.02.28.969931v1), [Web application](http://spatial.libd.org/spatialLIBD/), [R/Bioconductor package](http://bioconductor.org/packages/spatialLIBD), [Code for paper](https://github.com/LieberInstitute/HumanPilot), [Code for web application](https://github.com/LieberInstitute/spatialLIBD).

    - collaboration paper investigating the spatial landscape of gene expression in human brain (dorsolateral prefrontal cortex); my contribution consisted of the development of an unsupervised analysis pipeline


---


### Differential analyses

Methods for differential analyses are frequently used for exploratory analyses in high-throughput genomics data -- for example identifying differentially abundant (DA) subpopulations of cells, or differential states (DS) of expression within cell populations. I have been involved with several projects to develop improved methods for DA and DS analyses in mass cytometry (CyTOF) data.

Key papers:

- **Weber L.M.**, Nowicka N., Soneson C., and Robinson M.D. (2019), *diffcyt: Differential discovery in high-dimensional cytometry via high-resolution clustering*, Communications Biology, 2, 183. Links to: [Paper](https://www.nature.com/articles/s42003-019-0415-5), [R/Bioconductor package](http://bioconductor.org/packages/diffcyt), [Code](https://github.com/lmweber/diffcyt-evaluations), [Data](http://flowrepository.org/id/FR-FCM-ZYL8).

    - development of an improved computational framework for differential analyses in mass cytometry (CyTOF) data, implemented as an R/Bioconductor software package named *diffcyt* <br/> <br/>

- Nowicka N., Krieg C., Crowell H.L., **Weber L.M.**, Hartmann F.J., Guglietta S., Becher B., Levesque M.P., and Robinson M.D. (2017; updated 2019), *CyTOF workflow: differential discovery in high-throughput high-dimensional cytometry datasets*, F1000Research, 6:748, v3. Links to: [Paper](https://f1000research.com/articles/6-748), [R/Bioconductor package](https://bioconductor.org/packages/cytofWorkflow).

    - contributed to a comprehensive data analysis pipeline for differential analyses in mass cytometry (CyTOF) data


---


### Spatial transcriptomics

My methodological work is motivated by experimental collaborations in high-throughput molecular biology. Recently, I have been involved in several collaborations on data analysis for spatial transcriptomics (using the 10x Genomics Visium platform) in human brain. This is a fascinating new type of data, which allows measuring transcriptome-wide gene expression with spatial resolution, at near single-cell level. These projects allow us to contribute to fundamental biological insights, while opening up new avenues for statistical methodological research to develop data analysis methods that account for the unique characteristics of these data types.

Key papers:

- Maynard and Collado-Torres et al. (2020) (spatial transcriptomics collaboration on human brain; see link and details above)


---


### Single-cell RNA sequencing

Single-cell RNA sequencing experiments are expensive, and frequently subject to systematic issues such as batch effects. Application of improved methods for experimental design, such as sample pooling and genetic variation-based sample demultiplexing, can help alleviate these issues.

Key papers:

- **Weber L.M.**, Hippen A.A., Hickey P.F., Berrett K.C., Gertz J., Doherty J.A., Greene C.S., and Hicks S.C. (2020), *Genetic demultiplexing of pooled single-cell RNA-sequencing samples in cancer facilitates effective experimental design*, bioRxiv, v1, 371963. Links to: [Paper](https://www.biorxiv.org/content/10.1101/2020.11.06.371963v1), [Code](https://github.com/lmweber/snp-dmx-cancer), [Data](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE156793), [Code (controlled access)](https://www.ncbi.nlm.nih.gov/projects/gap/cgi-bin/study.cgi?study_id=phs002262.v1.p1).

    - evaluation of genetic variation-based sample demultiplexing in the context of an experimental collaboration on high-grade serous ovarian cancer (HGSOC), and development of a Snakemake computational pipeline


---


### Benchmarking

Benchmarking is a crucial aspect of computational methods development. New methods must be rigorously compared against existing methods, both in terms of statistical performance, as well as other aspects such as computational complexity and runtime. Useful contributions include both neutral benchmarks (i.e. major systematic comparisons of algorithms by researchers not involved with the development of any of the methods), as well as smaller (but still comprehensive) benchmarks performed by developers of a new method to demonstrate their performance.

Key papers:

- **Weber L.M.**, Saelens W., Cannoodt R., Soneson C., Hapfelmeier A., Gardner P.P., Boulesteix A.-L., Saeys Y., and Robinson M.D. (2019), *Essential guidelines for computational method benchmarking*, Genome Biology, 20, 125. Link to: [Paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1738-8).

    - review paper summarizing our views and guidance for how to best perform different types of benchmarking studies <br/> <br/>

- Weber and Robinson (2016) (comparison of clustering algorithms for mass cytometry data; see link and details above)

- Weber et al. (2019) (development of *diffcyt* framework for differential analyses in mass cytometry data; see link and details above)


---


### Open science

Science is a collaborative human effort spanning continents and generations. Openness is crucial, since it allows us all to build on each others' achievements and insights.

I strongly support modern practices in open science, including -- providing freely available code and data repositories along with all papers to ensure reproducibility of computational analyses; developing freely available and open-source software packages to implement all new statistical methods; collaborative development of software via platforms such as GitHub; and making papers accessible by posting preprints and publishing open access papers.

These practices have undergone enormous change within the last 10 years -- especially the widespread adoption of preprints in biology through [bioRxiv](https://www.biorxiv.org/). I am excited to continue following these developments over the coming years and decades, and will continue to adopt best practices in open science in all my own research work.


