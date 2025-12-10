---
title: "GPU-powered bat algorithm for the parameter estimation of biochemical kinetic values"
collection: publications
category: conferences
permalink: /publication/CIBCB-GPU_poweredBatAlgorithmPE
excerpt: 'A Lévy-flight Bat Algorithm combined with GPU simulation outperforms PSO in accuracy and speed for biochemical parameter estimation.'
date: 2016-10-05
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://ieeexplore.ieee.org/document/7758103'
citation: 'Tangherloni A., Nobile M.S., Cazzaniga P. (2016). GPU-powered bat algorithm for the parameter estimation of biochemical kinetic values. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

The emergent behavior of biochemical systems can be investigated by means of mathematical modeling and computational analyses, which usually require the automatic inference of the unknown values of the model's parameters. This problem, known as Parameter Estimation (PE), is usually tackled with bio-inspired meta-heuristics for global optimization, most notably Particle Swarm Optimization (PSO). In this work we assess the performances of PSO and Bat Algorithm with differential operator and Lévy flights trajectories (DLBA). In particular, we compared these meta-heuristics for the PE using two biochemical models: the expression of genes in prokaryotes and the heat shock response in eukaryotes. In our tests, we also evaluated the impact on PE of different strategies for the initial positioning of individuals within the search space. Our results show that DLBA achieves comparable results with respect to PSO, but it converges to better results when a uniform initialization is employed. Since every iteration of DLBA requires three fitness evaluations for each bat, the whole methodology is built around a GPU-powered biochemical simulator (cupSODA) which is able to parallelize the process. We show that the acceleration achieved with cupSODA strongly reduces the running time, with an empirical 61× speedup that has been obtained comparing a Nvidia GeForce Titan GTX with respect to a CPU Intel Core i7-4790K. Moreover, we show that DLBA always outperforms PSO with respect to the computational time required to execute the optimization process.