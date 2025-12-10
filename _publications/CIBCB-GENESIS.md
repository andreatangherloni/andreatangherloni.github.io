---
title: "GENESIS: Generating scRNA-Seq data from Multiome Gene Expression"
collection: publications
category: conferences
permalink: /publication/CIBCB-GENESIS
excerpt: 'We introduce GENESIS, a generative modelling framework that bridges the gap between Multiome GEX and scRNA-Seq data by producing enhanced whole-cell–like expression profiles.'
date: 2025-08-20
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://ieeexplore.ieee.org/document/11177099'
citation: 'Riva S.G., Myers B., Buffa F.M., Tangherloni A. (2025). GENESIS: Generating scRNA-Seq data from Multiome Gene Expression. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

Single-cell technologies have significantly advanced our understanding of cellular heterogeneity by allowing the examination of individual cells at high resolution. Traditional single-cell RNA sequencing (scRNA-Seq) methods, which utilise whole cells, capture comprehensive RNA content. In contrast, emerging Multiome technologies, which simultaneously profile multiple omics such as gene expression (GEX) and chromatin accessibility, rely on nuclear RNA, potentially missing key cytoplasmic information. This discrepancy results in substantial technical and biological differences between GEX and scRNA-Seq datasets, making it challenging to integrate the data and perform downstream tasks, such as cell-type classification. To address this challenge, we introduce GENESIS (Gene Expression Normalisation and Enhancement for Single-cell Integrated Sequencing), a novel computational framework designed to transform GEX data from Multiome experiments into enhanced, scRNA-Seq like profiles. Utilising advanced generative models—including Variational Autoencoders, Generative Adversarial Networks, and a tailored VAE_UNet architecture—GENESIS can generate high-quality data by modelling and compensating for the inherent differences between nuclear and cytoplasmic RNA. Our comprehensive evaluations show that GENESIS, particularly through the VAE_UNet model, generates synthetic scRNA-Seq data that closely resembles the resolution and biological accuracy of whole-cell sequencing, thereby improving downstream tasks, especially cell-type classification.