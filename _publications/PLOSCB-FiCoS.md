---
title: "FiCoS: a fine- and coarse-grained GPU-powered deterministic simulator for biochemical networks"
collection: publications
category: manuscripts
permalink: /publication/PLOSCB-FiCoS
excerpt: 'FiCoS is a GPU-powered deterministic simulator combining fine- and coarse-grained parallelization to simulate large-scale biochemical models with dramatic speed-ups.'
date: 2021-09-01
venue: 'PLoS Computational Biology'
paperurl: 'https://doi.org/10.1371/journal.pcbi.1009410'
citation: 'Tangherloni A., Nobile M.S., Cazzaniga P., Capitoli G., Spolaor S., Rundo L., Mauri G., Besozzi D. (2021). FiCoS: a fine- and coarse-grained GPU-powered deterministic simulator for biochemical networks. PLoS Computational Biology, 17(9): e1009410.'
---

Mathematical models of biochemical networks can largely facilitate the comprehension of the mechanisms at the basis of cellular processes, as well as the formulation of hypotheses that can be tested by means of targeted laboratory experiments. However, two issues might hamper the achievement of fruitful outcomes. On the one hand, detailed mechanistic models can involve hundreds or thousands of molecular species and their intermediate complexes, as well as hundreds or thousands of chemical reactions, a situation generally occurring in rule-based modeling. On the other hand, the computational analysis of a model typically requires the execution of a large number of simulations for its calibration or to test the effect of perturbations. As a consequence, the computational capabilities of modern Central Processing Units can be easily overtaken, possibly making the modeling of biochemical networks a worthless or ineffective effort. To the aim of overcoming the limitations of the current state-of-the-art simulation approaches, we present in this paper FiCoS, a novel "black-box" deterministic simulator that effectively realizes both a fine-grained and a coarse-grained parallelization on Graphics Processing Units. In particular, FiCoS exploits two different integration methods, namely, the Dormand–Prince and the Radau IIA, to efficiently solve both non-stiff and stiff systems of coupled Ordinary Differential Equations. We tested the performance of FiCoS against different deterministic simulators, by considering models of increasing size and by running analyses with increasing computational demands. FiCoS was able to dramatically speedup the computations up to 855×, showing to be a promising solution for the simulation and analysis of large-scale models of complex biological processes.
