---
title: "ACDC: Automated cell detection and counting for time-lapse fluorescence microscopy"
collection: publications
category: manuscripts
permalink: /publication/AppliedSciences-ACDC
excerpt: 'ACDC is an automated method for detecting and counting fluorescently labeled cell nuclei in time-lapse microscopy, without relying on large annotated datasets.'
date: 2020-09-04
venue: 'Applied Sciences'
paperurl: 'https://doi.org/10.3390/app10186187'
citation: 'Rundo L., Tangherloni A., Tyson D.R., Betta R., Militello C., Spolaor S., Nobile M.S., Besozzi D., Lubbock A.L.R., Quaranta V., Mauri G., Lopez C.F., Cazzaniga P. (2020). ACDC: Automated cell detection and counting for time-lapse fluorescence microscopy. Applied Sciences, 10(18): 6187.'
---

Advances in microscopy imaging technologies have enabled the visualization of live-cell dynamic processes using time-lapse microscopy imaging. However, modern methods exhibit several limitations related to the training phases and to time constraints, hindering their application in the laboratory practice. In this work, we present a novel method, named Automated Cell Detection and Counting (ACDC), designed for activity detection of fluorescent labeled cell nuclei in time-lapse microscopy. ACDC overcomes the limitations of the literature methods, by first applying bilateral filtering on the original image to smooth the input cell images while preserving edge sharpness, and then by exploiting the watershed transform and morphological filtering. Moreover, ACDC represents a feasible solution for the laboratory practice, as it can leverage multi-core architectures in computer clusters to efficiently handle large-scale imaging datasets. Indeed, our Parent-Workers implementation of ACDC allows to obtain up to a 3.7× speed-up compared to the sequential counterpart. ACDC was tested on two distinct cell imaging datasets to assess its accuracy and effectiveness on images with different characteristics. We achieved an accurate cell-count and nuclei segmentation without relying on large-scale annotated datasets, a result confirmed by the average Dice Similarity Coefficients of 76.84% and 88.64% and the Pearson coefficients of 0.99 and 0.96, calculated against the manual cell counting, on the two tested datasets.
