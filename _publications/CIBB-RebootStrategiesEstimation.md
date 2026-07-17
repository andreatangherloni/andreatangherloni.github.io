---
title: "Estimation of Kinetic Reaction Constants: Exploiting Reboot Strategies to Improve PSO’s Performance"
collection: publications
category: conferences
permalink: /publication/CIBB-RebootStrategiesEstimation
excerpt: 'Reboot strategies for Particle Swarm Optimization that help avoid local optima when estimating kinetic reaction constants of biochemical models.'
date: 2019-01-01
venue: 'International Conference on Computational Intelligence Methods for Bioinformatics and Biostatistics (CIBB)'
paperurl: 'https://doi.org/10.1007/978-3-030-14160-8_10'
citation: 'Spolaor S., Tangherloni A., Rundo L., Cazzaniga P., Nobile M.S. (2019). Estimation of Kinetic Reaction Constants: Exploiting Reboot Strategies to Improve PSO’s Performance. In Computational Intelligence Methods for Bioinformatics and Biostatistics (CIBB), Lecture Notes in Computer Science, 10834: 92-102, Springer.'
---

The simulation and analysis of mathematical models of biological systems require a complete knowledge of the reaction kinetic constants. Unfortunately, these values are often difficult to measure, but they can be inferred from experimental data in a process known as Parameter Estimation (PE). In this work, we tackle the PE problem using Particle Swarm Optimization (PSO) coupled with three different reboot strategies, which aim to reinitialize particle positions to avoid local optima. In particular, we highlight the better performance of PSO coupled with the reboot strategies with respect to standard PSO. Finally, since the PE requires a huge number of simulations at each iteration of PSO, we exploit cupSODA, a GPU-powered deterministic simulator, which performs all simulations and fitness evaluations in parallel.
