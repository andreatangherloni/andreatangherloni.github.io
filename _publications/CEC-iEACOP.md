---
title: "A Modified EACOP Implementation for Real-Parameter Single Objective Optimization Problems"
collection: publications
category: conferences
permalink: /publication/CEC-iEACOP
excerpt: 'We introduce iEACOP, an enhanced evolutionary algorithm with minimal hyper-parameter tuning requirements, which outperforms the original EACOP on most CEC 2017 benchmark functions and achieves performance comparable to top competition algorithms.'
date: 2024-06-30
venue: 'IEEE Congress on Evolutionary Computation (CEC)'
paperurl: 'https://ieeexplore.ieee.org/document/10611920'
citation: 'Tangherloni A., Coelho V., Buffa F.M., Cazzaniga P. (2024). A Modified EACOP Implementation for Real-Parameter Single Objective Optimization Problems. In IEEE Congress on Evolutionary Computation (CEC), IEEE.'
---

Evolutionary algorithms are effective techniques for optimizing non-linear and complex high-dimensional problems. However, most of them require a precise fine-tuning of their functioning settings to achieve satisfactory results. In this work, we propose a modified version of an evolutionary approach called the Evolutionary Algorithm for COmplex-process oPtimization (EACOP), designed to have a limited number of hyper-parameters. The base version of EACOP (bEACOP) combines different strategies, including the scatter search methodology, local searches, and a novel combination method based on path relinking to balance the exploration and exploitation phases. Our improved version (iEACOP) intensifies the exploration phase to escape from suboptimal search space areas where, on the contrary, bEACOP gets stuck. Our results show that iEACOP outperforms bEACOP on 27 out of 29 CEC 2017 test suite benchmark functions, exhibiting comparable performance against the three best algorithms of the CEC 2017 competition on single-objective bound-constrained real-parameter numerical optimization. The source code of bEACOP and iEACOP will be made publicly available on GitHub upon acceptance.