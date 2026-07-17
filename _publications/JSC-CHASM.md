---
title: "A CUDA-powered method for the feature extraction and unsupervised analysis of medical images"
collection: publications
category: manuscripts
permalink: /publication/JSC-CHASM
excerpt: 'CHASM is a GPU-accelerated method for Haralick feature extraction and self-organizing-map analysis of medical images.'
date: 2021-01-01
venue: 'The Journal of Supercomputing'
paperurl: 'https://doi.org/10.1007/s11227-020-03565-8'
citation: 'Rundo L., Tangherloni A., Cazzaniga P., Mistri M., Galimberti S., Woitek R., Sala E., Mauri G., Nobile M.S. (2021). A CUDA-powered method for the feature extraction and unsupervised analysis of medical images. The Journal of Supercomputing, 77(8): 8514-8531.'
---

Image texture extraction and analysis are fundamental steps in computer vision. In particular, considering the biomedical field, quantitative imaging methods are increasingly gaining importance because they convey scientifically and clinically relevant information for prediction, prognosis, and treatment response assessment. In this context, radiomic approaches are fostering large-scale studies that can have a significant impact in the clinical practice. In this work, we present a novel method, called CHASM (Cuda, HAralick & SoM), which is accelerated on the graphics processing unit (GPU) for quantitative imaging analyses based on Haralick features and on the self-organizing map (SOM). The Haralick features extraction step relies upon the gray-level co-occurrence matrix, which is computationally burdensome on medical images characterized by a high bit depth. The downstream analyses exploit the SOM with the goal of identifying the underlying clusters of pixels in an unsupervised manner. CHASM is conceived to leverage the parallel computation capabilities of modern GPUs. Analyzing ovarian cancer computed tomography images, CHASM achieved up to ∼19.5× and ∼37× speed-up factors for the Haralick feature extraction and for the SOM execution, respectively, compared to the corresponding C++ coded sequential versions. Such computational results point out the potential of GPUs in the clinical research.
