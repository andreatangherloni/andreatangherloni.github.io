---
title: "Reboot Strategies in Particle Swarm Optimization and their Impact on Parameter Estimation of Biochemical Systems"
collection: publications
category: conferences
permalink: /publication/CIBCB-RebootStrategiesPSO
excerpt: 'Three reboot strategies for PSO that reinitialize particle positions to avoid local optima in the parameter estimation of biochemical systems, accelerated with GPU simulation.'
date: 2017-08-23
venue: 'IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)'
paperurl: 'https://doi.org/10.1109/CIBCB.2017.8058550'
citation: 'Spolaor S., Tangherloni A., Rundo L., Nobile M.S., Cazzaniga P. (2017). Reboot Strategies in Particle Swarm Optimization and their Impact on Parameter Estimation of Biochemical Systems. In IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), IEEE.'
---

Computational methods adopted in the field of Systems Biology require the complete knowledge of reaction kinetic constants to perform simulations of the dynamics and understand the emergent behavior of biochemical systems. However, kinetic parameters of biochemical reactions are often difficult or impossible to measure, thus they are generally inferred from experimental data, in a process known as Parameter Estimation (PE). We consider here a PE methodology that exploits Particle Swarm Optimization (PSO) to estimate an appropriate kinetic parameterization, by comparing experimental time-series target data with in silico dynamics, simulated by using the parameterization encoded by each particle. In this work we present three different reboot strategies for PSO, whose aim is to reinitialize particle positions to avoid particles to get trapped in local optima, and we compare the performance of PSO coupled with the reboot strategies with respect to standard PSO in the case of the PE of two biochemical systems. Since the PE requires a huge number of simulations at each iteration, in this work we exploit a GPU-powered deterministic simulator, cupSODA, which performs in a parallel fashion all simulations and fitness evaluations. Finally, we show that the performances of our implementation scale sublinearly with respect to the swarm size, even on outdated GPUs.
