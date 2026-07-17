---
title: "Gillespie’s Stochastic Simulation Algorithm on MIC Coprocessor"
collection: publications
category: manuscripts
permalink: /publication/JSC-GillespieMIC
excerpt: 'A parallel implementation of Gillespie’s Stochastic Simulation Algorithm on the Intel Many Integrated Core (Xeon Phi) coprocessor to accelerate stochastic simulations of biochemical networks.'
date: 2017-02-01
venue: 'The Journal of Supercomputing'
paperurl: 'https://doi.org/10.1007/s11227-016-1778-8'
citation: 'Tangherloni A., Nobile M.S., Cazzaniga P., Besozzi D., Mauri G. (2017). Gillespie’s Stochastic Simulation Algorithm on MIC Coprocessor. The Journal of Supercomputing, 73(2): 676-686.'
---

To investigate the behavior of biochemical systems, many runs of Gillespie's Stochastic Simulation Algorithm (SSA) are generally needed, causing excessive computational costs on Central Processing Units (CPUs). Since all SSA runs are independent, the Intel Xeon Phi coprocessors based on the Many Integrated Core (MIC) architecture can be exploited to distribute the workload. We considered two execution modalities on MIC: one consisted in running exactly the same CPU code of SSA, while the other exploited MIC's vector instructions to reuse the CPU code with only few modifications. MIC performance was compared with Graphics Processing Units (GPUs), specifically implemented in CUDA to optimize the use of memory hierarchy. Our results show that GPU largely outperforms MIC and CPU, but required a complete redesign of SSA. MIC allows a relevant speedup, especially when vector instructions are used, with the additional advantage of requiring minimal modifications to CPU code.
