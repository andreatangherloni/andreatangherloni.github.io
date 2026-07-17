---
title: "Simplifying Fitness Landscapes using Dilation Functions evolved with Genetic Programming"
collection: publications
category: manuscripts
permalink: /publication/MCI-DilationFunctions
excerpt: 'We propose GP4DFs, a Genetic Programming method that automatically evolves effective Dilation Functions to manipulate the fitness landscape and improve the optimization process.'
date: 2023-02-01
venue: 'IEEE Computational Intelligence Magazine'
paperurl: 'https://doi.org/10.1109/MCI.2022.3222096'
citation: 'Papetti D.M., Tangherloni A., Farinati D., Cazzaniga P., Vanneschi L. (2023). Simplifying Fitness Landscapes using Dilation Functions evolved with Genetic Programming. IEEE Computational Intelligence Magazine, 18(1): 22-31.'
---

Several optimization problems have features that hinder the capabilities of searching heuristics. To cope with this issue, different methods have been proposed to manipulate search spaces and improve the optimization process. This paper focuses on Dilation Functions (DFs), which are one of the most promising techniques to manipulate the fitness landscape, by "expanding" or "compressing" specific regions. The definition of appropriate DFs is problem dependent and requires a-priori knowledge of the optimization problem. Therefore, it is essential to introduce an automatic and efficient strategy to identify optimal DFs. With this aim, we propose a novel method based on Genetic Programming, named GP4DFs, which is capable of evolving effective DFs. GP4DFs identifies optimal dilations, where a specific DF is applied to each dimension of the search space. Moreover, thanks to a knowledge-driven initialization strategy, GP4DFs converges to better solutions with a reduced number of fitness evaluations, compared to the state-of-the-art approaches. The performance of GP4DFs is assessed on a set of 43 benchmark functions mimicking several features of real-world optimization problems. The obtained results indicate the suitability of the generated DFs.
