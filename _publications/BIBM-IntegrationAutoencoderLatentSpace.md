---
title: "Integration of Multiple scRNA-Seq Datasets on the Autoencoder Latent Space"
collection: publications
category: conferences
permalink: /publication/BIBM-IntegrationAutoencoderLatentSpace
excerpt: 'A novel Autoencoder-based strategy for integrating multiple scRNA-Seq datasets that outperforms Scanorama, Ingest, and Seurat in most cases.'
date: 2021-12-09
venue: 'IEEE International Conference on Bioinformatics and Biomedicine (BIBM)'
paperurl: 'https://doi.org/10.1109/BIBM52615.2021.9669807'
citation: 'Riva S.G., Cazzaniga P., Tangherloni A. (2021). Integration of Multiple scRNA-Seq Datasets on the Autoencoder Latent Space. In IEEE International Conference on Bioinformatics and Biomedicine (BIBM), pp. 2155-2162, IEEE.'
---

The application of single-cell transcriptomic sequencing technologies, such as single-cell RNA sequencing (scRNA-Seq), have witnessed in recent years a dramatic increase, allowing for the elucidation of the molecular processes driving both normal cell development and the onset of pathologies. In particular, scRNA-Seq can be exploited to investigate cell heterogeneity at single-cell resolution, and to identify the variety of known and putatively novel cell populations, which can potentially have different functional roles in different contexts. However, the heterogeneity among cells of the same cell-type can make the integration of multiple scRNA-Seq datasets a challenging task. In this context, technical non-negligible batch effects in the datasets—which may arise from the sequencing technology employed and from the size of the experiment—must be considered to realize a correct data integration. In this work, we present a novel strategy based on Autoencoders (AEs) for the integration of multiple scRNA-Seq datasets, whose performance is compared with different integration strategies that do not exploit a batch effect removal step, which might introduce artifacts in the datasets. Our results, obtained by considering 3 different datasets, suggest that AEs represent a suitable strategy for the integration of scRNA-Seq datasets, achieving better performance than other approaches, i.e., Scanorama, Ingest, and Seurat, in most of the cases.
