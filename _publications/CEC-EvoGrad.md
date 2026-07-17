---
title: "EvoGrad: Accelerated Metaheuristics in a Differentiable Wonderland"
collection: publications
category: conferences
permalink: /publication/CEC-EvoGrad
excerpt: 'EvoGrad is a unified differentiable framework that turns evolutionary and swarm operators into differentiable operators, integrating Evolutionary Computation and Swarm Intelligence with gradient-based optimization via backpropagation.'
date: 2026-06-01
venue: 'IEEE Congress on Evolutionary Computation (CEC)'
paperurl: 'https://arxiv.org/abs/2506.06320'
citation: 'Citterio B.F.R., Papetti D.M., Dimitri G.M., Tangherloni A. (2026). EvoGrad: Accelerated Metaheuristics in a Differentiable Wonderland. In IEEE Congress on Evolutionary Computation (CEC), IEEE.'
---

Differentiable programming has revolutionised optimisation by enabling efficient gradient-based training of complex models, such as Deep Neural Networks (NNs) with billions and trillions of parameters. However, traditional Evolutionary Computation (EC) and Swarm Intelligence (SI) algorithms, widely successful in discrete or complex search spaces, typically do not leverage local gradient information, limiting their optimisation efficiency. In this paper, we introduce EvoGrad, a unified differentiable framework that integrates EC and SI with gradient-based optimisation through backpropagation. EvoGrad converts conventional evolutionary and swarm operators (e.g., selection, mutation, crossover, and particle updates) into differentiable operators, facilitating end-to-end gradient optimisation. Extensive experiments on benchmark optimisation functions and training of small NN regressors reveal that our differentiable versions of EC and SI metaheuristics consistently outperform traditional, gradient-agnostic algorithms in most scenarios. Our results show the substantial benefits of fully differentiable evolutionary and swarm optimisation, setting a new standard for hybrid optimisation frameworks.
