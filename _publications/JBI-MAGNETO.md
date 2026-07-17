---
title: "MAGNETO: Marker pAnels GeNEraTor with multi-Objective optimization"
collection: publications
category: manuscripts
permalink: /publication/JBI-MAGNETO
excerpt: 'MAGNETO is a fully-automatic framework that builds compact, optimal marker panels from single-cell gene expression data by solving a tailored bi-objective optimization problem.'
date: 2023-11-01
venue: 'Journal of Biomedical Informatics'
paperurl: 'https://doi.org/10.1016/j.jbi.2023.104510'
citation: 'Tangherloni A., Riva S.G., Myers B., Buffa F.M., Cazzaniga P. (2023). MAGNETO: Marker pAnels GeNEraTor with multi-Objective optimization. Journal of Biomedical Informatics, 147: 104510.'
---

Single-cell RNA sequencing experiments produce data useful to identify different cell types, including uncharacterized and rare ones. This enables us to study the specific functional roles of these cells in different microenvironments and contexts. After identifying a (novel) cell type of interest, it is essential to build succinct marker panels, composed of a few genes referring to cell surface proteins and clusters of differentiation molecules, able to discriminate the desired cells from the other cell populations. In this work, we propose a fully-automatic framework called MAGNETO, which can help construct optimal marker panels starting from a single-cell gene expression matrix and a cell type identity for each cell. MAGNETO builds effective marker panels solving a tailored bi-objective optimization problem, where the first objective regards the identification of the genes able to isolate a specific cell type, while the second conflicting objective concerns the minimization of the total number of genes included in the panel. Our results on three public datasets show that MAGNETO can identify marker panels that identify the cell populations of interest better than state-of-the-art approaches. Finally, by fine-tuning MAGNETO, our results demonstrate that it is possible to obtain marker panels with different specificity levels.
