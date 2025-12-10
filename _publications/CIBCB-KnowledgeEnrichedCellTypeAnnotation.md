---
title: "Knowledge-Enriched Cell-Type Annotation in Single-Cell Transcriptomics via LLM Embeddings"
collection: publications
category: conferences
permalink: /publication/CIBCB-KnowledgeEnrichedCellTypeAnnotation
excerpt: 'We show that embedding biological knowledge through Modern-BERT gene vectors strengthens supervised models for scRNA-seq cell-type classification.'
date: 2025-08-20
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://ieeexplore.ieee.org/document/11177124'
citation: 'Fabbricatore A., Buffa F.M., Tangherloni A. (2025). Knowledge-Enriched Cell-Type Annotation in Single-Cell Transcriptomics via LLM Embeddings. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

Single-cell RNA sequencing (scRNA-seq) has profoundly reshaped our understanding of cellular diversity and functionality; however, accurate cell-type annotation is required for biological interpretation. Current annotation methods, which are predominantly reliant on gene expression alone or manual curation, suffer from subjectivity and a limited biological context. Here, we introduce a novel approach that integrates textual biological knowledge via gene embeddings, derived from fine-tuning Large Language Models (LLMs), with gene counts to enrich the input space for supervised models in automatic cell-type classification. In particular, we trained an XGBoost model and a multi-layer perceptron (MLP) to automatically classify the cell populations. We demonstrate that combining Modern-BERT embeddings and raw counts enhances the performance of MLPs, particularly in complex classification scenarios that involve subtle cell-subtype distinctions. Our results also show that ModernBERT generated better embeddings than smaller LLM architectures, underlining the value of enriched, biologically informed embeddings. By embedding prior knowledge from curated biological databases and literature, our approach enhances the MLP’s ability to distinguish sub-cell populations and biological signals. This work provides a scalable framework for integrating broader biological context into scRNA-seq analyses, offering new opportunities for downstream tasks such as gene regulatory network inference and cross-species annotation.
