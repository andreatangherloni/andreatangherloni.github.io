---
title: "GPU-Powered Multi-Swarm Parameter Estimation of Biological Systems: A Master-Slave Approach"
collection: publications
category: conferences
permalink: /publication/PDP-MultiSwarmPE
excerpt: 'MS2PSO is a parallel and distributed multi-swarm PSO, powered by GPU simulation, for estimating reaction constants in biological models across multiple experimental conditions.'
date: 2018-03-21
venue: 'Euromicro International Conference on Parallel, Distributed, and Network-based Processing (PDP)'
paperurl: 'https://doi.org/10.1109/PDP2018.2018.00115'
citation: 'Tangherloni A., Rundo L., Spolaor S., Cazzaniga P., Nobile M.S. (2018). GPU-Powered Multi-Swarm Parameter Estimation of Biological Systems: A Master-Slave Approach. In IEEE 26th Euromicro International Conference on Parallel, Distributed and Network-based Processing (PDP), pp. 698-705, IEEE.'
---

In silico investigation of biological systems requires the knowledge of numerical parameters that cannot be easily measured in laboratory experiments, leading to the Parameter Estimation (PE) problem, in which the unknown parameters are automatically inferred by means of optimization algorithms exploiting the available experimental data. Here we present MS2PSO, an efficient parallel and distributed implementation of a method based on Particle Swarm Optimization (PSO) for the estimation of reaction constants in mathematical models of biological systems, considering as target for the estimation a set of discrete-time measurements of molecular species amounts. In particular, such method accounts for the availability of experimental data typically measured under different experimental conditions, by considering a multi-swarm in which the best particles of the swarms can migrate. This strategy allows to infer a common set of reaction constants that simultaneously fits all target data used in the estimation. With the aim of efficiently tackling the problem, MS2PSO embeds the execution of cupSODA, a deterministic simulator that relies on Graphics Processing Units to achieve a massive parallelization of the simulations required in the fitness evaluation. In addition, a further level of parallelism is realized by exploiting the Master-Slave distributed programming paradigm. We apply MS2PSO for the estimation of synthetic biochemical models with 10, 20 and 30 parameters to be estimated, and compare the performances obtained with different GPUs and different configurations (i.e., numbers of processes).
