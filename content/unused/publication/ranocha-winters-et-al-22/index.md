---
title: On error-based step size control for discontinuous Galerkin methods for compressible
  fluid dynamics
authors:
- Hendrik Ranocha
- Andrew R. Winters
- Hugo Guillermo Castro
- Lisandro Dalcin
- Michael Schlottke-Lakemper
- Gregor J. Gassner
- Matteo Parsani
date: '2023-01-01'
publishDate: '2023-11-23T12:20:16.650308Z'
publication_types:
- article-journal
publication: '*Commun. Appl. Math. Comput.*'
doi: 10.1007/s42967-023-00264-y
abstract: We study temporal step size control of explicit Runge-Kutta methods for
  compressible computational fluid dynamics (CFD), including the Navier-Stokes equations
  and hyperbolic systems of conservation laws such as the Euler equations. We demonstrate
  that error-based approaches are convenient in a wide range of applications and compare
  them to more classical step size control based on a Courant-Friedrichs-Lewy (CFL)
  number. Our numerical examples show that error-based step size control is easy to
  use, robust, and efficient, e.g., for (initial) transient periods, complex geometries,
  nonlinear shock capturing approaches, and schemes that use nonlinear entropy projections.
  We demonstrate these properties for problems ranging from well-understood academic
  test cases to industrially relevant large-scale computations with two disjoint code
  bases, the open source Julia packages Trixi.jl with OrdinaryDiffEq.jl and the C/Fortran
  code SSDC based on PETSc.
tags:
- math.NA
- cs.NA
- physics.comp-ph
- 65L06
- 65M20
- 65M70
- 76M10
- 76M22
- 76N99
- 35L50
---
