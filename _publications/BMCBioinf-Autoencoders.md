---
title: "Analysis of single-cell RNA sequencing data based on autoencoders"
collection: publications
category: manuscripts
permalink: /publication/BMCBioinf-Autoencoders
excerpt: 'scAEspy is a unifying autoencoder-based tool for the low-dimensional representation and integration of single-cell RNA-Seq datasets.'
date: 2021-06-01
venue: 'BMC Bioinformatics'
paperurl: 'https://doi.org/10.1186/s12859-021-04150-3'
citation: 'Tangherloni A., Ricciuti F., Besozzi D., Liò P., Cvejic A. (2021). Analysis of single-cell RNA sequencing data based on autoencoders. BMC Bioinformatics, 22(1): 309.'
---

Single-cell RNA sequencing (scRNA-Seq) experiments are gaining ground to study the molecular processes that drive normal development as well as the onset of different pathologies. Finding an effective and efficient low-dimensional representation of the data is one of the most important steps in the downstream analysis of scRNA-Seq data, as it could provide a better identification of known or putatively novel cell-types. Another step that still poses a challenge is the integration of different scRNA-Seq datasets. Though standard computational pipelines to gain knowledge from scRNA-Seq data exist, a further improvement could be achieved by means of machine learning approaches. Autoencoders (AEs) have been effectively used to capture the non-linearities among gene interactions of scRNA-Seq data, so that the deployment of AE-based tools might represent the way forward in this context. We introduce here scAEspy, a unifying tool that embodies: (1) four of the most advanced AEs, (2) two novel AEs that we developed on purpose, (3) different loss functions. We show that scAEspy can be coupled with various batch-effect removal tools to integrate data by different scRNA-Seq platforms, in order to better identify the cell-types. We benchmarked scAEspy against the most used batch-effect removal tools, showing that our AE-based strategies outperform the existing solutions. scAEspy is a user-friendly tool that enables using the most recent and promising AEs to analyse scRNA-Seq data by only setting up two user-defined parameters. Thanks to its modularity, scAEspy can be easily extended to accommodate new AEs to further improve the downstream analysis of scRNA-Seq data. Considering the relevant results we achieved, scAEspy can be considered as a starting point to build a more comprehensive toolkit designed to integrate multi single-cell omics.
