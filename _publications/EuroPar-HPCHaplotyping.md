---
title: "High Performance Computing for Haplotyping: Models and Platforms"
collection: publications
category: conferences
permalink: /publication/EuroPar-HPCHaplotyping
excerpt: 'A review of models and high-performance computing platforms for the haplotype assembly problem.'
date: 2019-01-01
venue: 'Euro-Par 2018: Parallel Processing Workshops (Springer)'
paperurl: 'https://doi.org/10.1007/978-3-030-10549-5_51'
citation: 'Tangherloni A., Rundo L., Spolaor S., Nobile M.S., Merelli I., Besozzi D., Mauri G., Cazzaniga P., Liò P. (2019). High Performance Computing for Haplotyping: Models and Platforms. In Euro-Par 2018: Parallel Processing Workshops, Lecture Notes in Computer Science, 11339: 650-661, Springer.'
---

The reconstruction of the haplotype pair for each chromosome is a hot topic in Bioinformatics and Genome Analysis. In Haplotype Assembly (HA), all heterozygous Single Nucleotide Polymorphisms (SNPs) have to be assigned to exactly one of the two chromosomes. In this work, we outline the state-of-the-art on HA approaches and present an in-depth analysis of the computational performance of GenHap, a recent method based on Genetic Algorithms. GenHap was designed to tackle the computational complexity of the HA problem by means of a divide-et-impera strategy that effectively leverages multi-core architectures. In order to evaluate GenHap's performance, we generated different instances of synthetic (yet realistic) data exploiting empirical error models of four different sequencing platforms (namely, Illumina NovaSeq, Roche/454, PacBio RS II and Oxford Nanopore Technologies MinION). Our results show that the processing time generally decreases along with the read length, involving a lower number of sub-problems to be distributed on multiple cores.
