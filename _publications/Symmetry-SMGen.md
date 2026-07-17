---
title: "SMGen: A generator of synthetic models of biochemical reaction networks"
collection: publications
category: manuscripts
permalink: /publication/Symmetry-SMGen
excerpt: 'SMGen automatically generates synthetic yet realistic models of biochemical reaction networks to benchmark simulation and analysis tools in computational systems biology.'
date: 2022-01-10
venue: 'Symmetry'
paperurl: 'https://doi.org/10.3390/sym14010119'
citation: 'Riva S.G., Cazzaniga P., Nobile M.S., Spolaor S., Rundo L., Besozzi D., Tangherloni A. (2022). SMGen: A generator of synthetic models of biochemical reaction networks. Symmetry, 14(1): 119.'
---

Several software tools for the simulation and analysis of biochemical reaction networks have been developed in the last decades; however, assessing and comparing their computational performance in executing the typical tasks of computational systems biology can be limited by the lack of a standardized benchmarking approach. To overcome these limitations, we propose here a novel tool, named SMGen, designed to automatically generate synthetic models of reaction networks that, by construction, are characterized by relevant features (e.g., system connectivity and reaction discreteness) and non-trivial emergent dynamics of real biochemical networks. The generation of synthetic models in SMGen is based on the definition of an undirected graph consisting of a single connected component that, generally, results in a computationally demanding task; to speed up the overall process, SMGen exploits a main–worker paradigm. SMGen is also provided with a user-friendly graphical user interface, which allows the user to easily set up all the parameters required to generate a set of synthetic models with any number of reactions and species. We analysed the computational performance of SMGen by generating batches of symmetric and asymmetric reaction-based models (RBMs) of increasing size, showing how a different number of reactions and/or species affects the generation time. Our results show that when the number of reactions is higher than the number of species, SMGen has to identify and correct a large number of errors during the creation process of the RBMs, a circumstance that increases the running time. Still, SMGen can generate synthetic models with hundreds of species and reactions in less than 7 seconds.
