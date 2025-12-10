---
title: "A Deep Learning Pipeline for the Automatic cell type Assignment of scRNA-seq Data"
collection: publications
category: conferences
permalink: /publication/CIBCB-DeepLearningPipelineAutomaticCellType
excerpt: 'scALPO is a novel automated pipeline that employs an LSTM neural network to assign cell types based solely on marker genes, surpassing current state-of-the-art tools in annotation accuracy.'
date: 2022-08-20
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://ieeexplore.ieee.org/document/9863034'
citation: 'Riva S.G., Myers B., Cazzaniga P., Tangherloni A.(2022).A Deep Learning Pipeline for the Automatic cell type Assignment of scRNA-seq Data. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

The increasing number of single-cell transcriptomics and single-cell RNA sequencing studies are allowing for a deeper understanding of the molecular processes underlying the normal development of an organism, as well as the onset of pathologies. In this context, cell type annotation represents a crucial step for the analysis of single-cell RNA sequencing data, which is usually performed by means of time-consuming and possibly biased manual processes, carried out by expert biologists. Recently, alternative computational tools have been proposed to realize an automatic cell identification either based on supervised or unsupervised Machine Learning approaches. These methods typically exploit gene expression data of curated marker gene databases to associate gene expression profiles of single cells with a cell type. In this paper, we propose a novel fully-automatic computational pipeline, named single-cell Automatic Labeling of cell POpulations (scALPO), which leverages a Long Short-Term Memory Neural Network to assign the cell types. Specifically, scALPO can label the provided clusters by simply relying on marker genes rather than gene expressions. Our results, obtained by considering two different datasets, show that scALPO outperforms the most promising state-of-the-art approaches (i.e., SCSA and scType), achieving a cell type annotation more similar to the manually-created ground truth.