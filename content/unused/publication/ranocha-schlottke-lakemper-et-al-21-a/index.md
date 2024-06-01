---
title: Efficient implementation of modern entropy stable and kinetic energy preserving
  discontinuous Galerkin methods for conservation laws
authors:
- Hendrik Ranocha
- Michael Schlottke-Lakemper
- Jesse Chan
- Andrés M. Rueda-Ramírez
- Andrew R. Winters
- Florian Hindenlang
- Gregor J. Gassner
date: '2023-01-01'
publishDate: '2023-11-23T12:20:16.646348Z'
publication_types:
- article-journal
publication: '*ACM Trans. Math. Softw.*'
doi: 10.1145/3625559
abstract: Many modern discontinuous Galerkin (DG) methods for conservation laws make
  use of summation by parts operators and flux differencing to achieve kinetic energy
  preservation or entropy stability. While these techniques increase the robustness
  of DG methods significantly, they are also computationally more demanding than standard
  weak form nodal DG methods. We present several implementation techniques to improve
  the efficiency of flux differencing DG methods that use tensor product quadrilateral
  or hexahedral elements, in 2D or 3D respectively. Focus is mostly given to CPUs
  and DG methods for the compressible Euler equations, although these techniques are
  generally also useful for GPU computing and other physical systems including the
  compressible Navier-Stokes and magnetohydrodynamics equations. We present results
  using two open source codes, Trixi.jl written in Julia and FLUXO written in Fortran,
  to demonstrate that our proposed implementation techniques are applicable to different
  code bases and programming languages.
tags:
- cs.MS
- cs.NA
- math.NA
- physics.comp-ph
---
