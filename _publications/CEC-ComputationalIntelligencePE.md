---
title: "Computational Intelligence for Parameter Estimation of Biochemical Systems"
collection: publications
category: conferences
permalink: /publication/CEC-ComputationalIntelligencePE
excerpt: 'To address the challenge of estimating kinetic parameters in biochemical models, we benchmark seven state-of-the-art optimization techniques and find that a settings-free FST-PSO variant yields the most robust and accurate performance across diverse systems.'
date: 2018-07-08
venue: 'IEEE Congress on Evolutionary Computation (CEC)'
paperurl: 'https://ieeexplore.ieee.org/document/8477873'
citation: 'Nobile M.S., Tangherloni A., Rundo L., Spolaor S., Besozzi D., Mauri G., Cazzaniga P. (2018). Computational Intelligence for Parameter Estimation of Biochemical Systems. In IEEE Congress on Evolutionary Computation (CEC), IEEE.'
---

In the field of Systems Biology, simulating the dynamics of biochemical models represents one of the most effective methodologies to understand the functioning of cellular processes in normal or altered conditions. However, the lack of kinetic rates, necessary to perform accurate simulations, strongly limits the scope of these analyses. Parameter Estimation (PE), which consists in identifying a proper model parameterization, is a non-linear, non-convex and multi-modal optimization problem, typically tackled by means of Computational Intelligence techniques, such as Evolutionary Computation and Swarm Intelligence. In this work, we perform a thorough investigation of the most widespread methods for PE-namely, Artificial Bee Colony (ABC), Covariance Matrix Adaptation Evolution Strategy (CMA-ES), Differential Evolution (DE), Estimation of Distribution Algorithm (EDA), Genetic Algorithms (GAs), Particle Swarm Optimization (PSO), and Fuzzy Self-Tuning PSO (FST-PSO)-comparing their performances on a set of synthetic (yet realistic) biochemical models of increasing size and complexity. Our results show that a variant of the settings-free FST-PSO algorithm can consistently outperform all other methods; ABC and GAs represent the most performing alternatives, while methods based on multivariate normal distributions (e.g., CMA-ES, EDA) struggle to keep pace with the other approaches.