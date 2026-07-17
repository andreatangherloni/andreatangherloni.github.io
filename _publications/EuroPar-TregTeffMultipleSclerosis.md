---
title: "GPU accelerated analysis of Treg-Teff cross regulation in relapsing-remitting multiple sclerosis"
collection: publications
category: conferences
permalink: /publication/EuroPar-TregTeffMultipleSclerosis
excerpt: 'GPU-accelerated analysis of the cross regulation between regulatory and effector T cells in relapsing-remitting multiple sclerosis.'
date: 2019-01-01
venue: 'Euro-Par 2018: Parallel Processing Workshops (Springer)'
paperurl: 'https://doi.org/10.1007/978-3-030-10549-5_49'
citation: 'Beccuti M., Cazzaniga P., Pennisi M., Besozzi D., Nobile M.S., Pernice S., Russo G., Tangherloni A., Pappalardo F. (2019). GPU accelerated analysis of Treg-Teff cross regulation in relapsing-remitting multiple sclerosis. In Euro-Par 2018: Parallel Processing Workshops, Lecture Notes in Computer Science, 11339: 626-637, Springer.'
---

The computational analysis of complex biological systems can be hindered by two main factors. First, modeling the system so that it can be easily understood and analyzed by non-expert users is not always possible, especially when dealing with systems of Ordinary Differential Equations. Second, when the system is composed of hundreds or thousands of reactions and chemical species, the classic CPU-based simulators could not be appropriate to efficiently derive the behavior of the system. To overcome these limitations, in this paper we propose a novel approach that combines the descriptive power of Stochastic Symmetric Nets–a Petri Net formalism that allows modeler to describe the system in a parametric and compact manner–with LASSIE, a GPU-powered deterministic simulator that offloads onto the GPU the calculations required to execute many simulations by following both fine-grained and coarse-grained parallelization strategies. This pipeline has been applied to carry out a parameter sweep analysis of a relapsing-remitting multiple sclerosis model, aimed at understanding the role of possible malfunctions in the cross-balancing mechanisms that regulate peripheral tolerance of self-reactive T lymphocytes. From our experiments, LASSIE achieves around 97× speed-up with respect to the sequential execution of the same number of simulations.
