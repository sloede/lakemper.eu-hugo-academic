---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Direct-Hybrid Method for Aeroacoustic Analysis
subtitle: ''
summary: ''
authors:
- Michael Schlottke-Lakemper
tags: []
categories: []
date: '2017-01-01'
lastmod: 2022-10-23T11:14:43+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-23T09:14:43.174279Z'
publication_types:
- '7'
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
publication: ''
---
