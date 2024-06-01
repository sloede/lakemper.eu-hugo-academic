---
title: A Direct-Hybrid Method for Aeroacoustic Analysis
authors:
- Michael Schlottke-Lakemper
date: '2017-01-01'
publishDate: '2023-11-23T12:20:16.615375Z'
publication_types:
- thesis
abstract: 'Hybrid computational fluid dynamics (CFD) - computational aeroacoustics
  (CAA) schemes are the standard method for aeroacoustics simulations. In this approach,
  it is necessary to exchange information between the CFD and the CAA step, which
  is usually accomplished by storing acoustic source data. This data exchange procedure,
  however, poses two problems when such hybrid methods are used for large-scale problems
  with O(10^9) degrees of freedom: Firstly, the required disk space becomes large
  and reaches hundreds of terabytes for a single simulation. Added to that, the parallel
  scalability of the overall numerical scheme is limited by the available I/O bandwidth,
  which typically peaks between 5,000 and 10,000 cores. To avoid these problems, a
  highly scalable direct-hybrid scheme is presented, in which both the flow and the
  acoustics simulations run simultaneously. That is, all data between the two solvers
  is transferred in-memory, avoiding the restrictions of the I/O subsystem. Both solvers
  operate on a joint hierarchical Cartesian grid, which enables efficient parallelization
  and dynamic load balancing, and which inherently supports local mesh refinement.
  To demonstrate the capabilities of the new scheme, the aeroacoustic field of a co-rotating
  vortex pair is computed and the flow-induced noise emissions of a turbulent, isothermal
  jet are predicted. The results show that the direct-hybrid method is able to accurately
  capture the sound pressure field and that it is particularly suitable for efficient,
  highly parallel simulations. Furthermore, in comparison to the classic hybrid method
  with data exchange via disk I/O, the novel approach shows superior performance when
  scaling to thousands of cores.'
---
