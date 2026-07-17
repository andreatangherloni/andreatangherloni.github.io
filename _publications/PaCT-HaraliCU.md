---
title: "HaraliCU: GPU-powered Haralick Feature Extraction on Medical Images Exploiting the Full Dynamics of Gray-Scale Levels"
collection: publications
category: conferences
permalink: /publication/PaCT-HaraliCU
excerpt: 'HaraliCU is a GPU-powered method for Haralick feature extraction on medical images that exploits the full dynamics of gray-scale levels without requantization.'
date: 2019-08-01
venue: 'International Conference on Parallel Computing Technologies (PaCT)'
paperurl: 'https://doi.org/10.1007/978-3-030-25636-4_24'
citation: 'Rundo L., Tangherloni A., Galimberti S., Cazzaniga P., Woitek R., Sala E., Nobile M.S., Mauri G. (2019). HaraliCU: GPU-powered Haralick Feature Extraction on Medical Images Exploiting the Full Dynamics of Gray-Scale Levels. In International Conference on Parallel Computing Technologies (PaCT), Lecture Notes in Computer Science, 11657: 304-318, Springer.'
---

Image texture extraction and analysis are fundamental steps in Computer Vision. In particular, considering the biomedical field, quantitative imaging methods are increasingly gaining importance since they convey scientifically and clinically relevant information for prediction, prognosis, and treatment response assessment. In this context, radiomic approaches are fostering large-scale studies that can have a significant impact in the clinical practice. In this work, we focus on Haralick features, the most common and clinically relevant descriptors. These features are based on the Gray-Level Co-occurrence Matrix (GLCM), whose computation is considerably intensive on images characterized by a high bit-depth (e.g., 16 bits), as in the case of medical images that convey detailed visual information. We propose here HaraliCU, an efficient strategy for the computation of the GLCM and the extraction of an exhaustive set of the Haralick features. HaraliCU was conceived to exploit the parallel computation capabilities of modern Graphics Processing Units (GPUs), allowing us to achieve up to ∼20× speed-up with respect to the corresponding C++ coded sequential version. Our GPU-powered solution highlights the promising capabilities of GPUs in the clinical research.
