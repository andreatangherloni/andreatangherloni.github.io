---
title: "Consensus Clustering Strategy for Cell Type Assignments of scRNA-seq Data"
collection: publications
category: conferences
permalink: /publication/CIBCB-ConsensusClusteringStrategy
excerpt: 'We introduce a pseudo-voting consensus approach within scALPO that combines multiple clustering outputs to achieve more robust and accurate cell-type annotation.'
date: 2023-08-20
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://ieeexplore.ieee.org/document/10264908'
citation: 'Riva S.G., Myers B., Cazzaniga P., Buffa F.M., Tangherloni A. (2023). Consensus Clustering Strategy for Cell Type Assignments of scRNA-seq Data. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

Cell type annotation is a crucial step for analyzing single-cell RNA sequencing data. Among others, single-cell Automatic Labeling of cell POpulations (scALPO) is a computational pipeline developed to automatically assign the cell types to the identified clusters in scRNA-seq data. Different from most of the approaches, scALPO relies only on the information on marker genes from published literature. Specifically, after the definition of the dataset obtained from gene information retrieved from online databases, the Leiden clustering algorithm is executed to partition cells that are finally annotated. Since the Leiden algorithm might struggle to obtain a reliable outcome under certain circumstances, in this work, we include several clustering algorithms in scALPO, and we propose a pseudo-voting consensus approach that combines the outcome of a set of clustering algorithms. The results obtained on three different datasets show that the consensus approach can improve the cell type annotation without selecting a specific clustering algorithm that best suits the data under investigation.