---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On error-based step size control for discontinuous Galerkin methods for compressible
  fluid dynamics
subtitle: ''
summary: ''
authors:
- Hendrik Ranocha
- Andrew R. Winters
- Hugo Guillermo Castro
- Lisandro Dalcin
- Michael Schlottke-Lakemper
- Gregor J. Gassner
- Matteo Parsani
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
categories: []
date: 2022, submitted-01-01
lastmod: 2022-10-23T11:14:44+02:00
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
publishDate: '2022-10-23T09:14:44.462238Z'
publication_types:
- '2'
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
publication: '*Commun. Appl. Math. Comput.*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2209.07037
---
