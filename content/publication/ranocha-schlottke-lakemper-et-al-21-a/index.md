---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient implementation of modern entropy stable and kinetic energy preserving
  discontinuous Galerkin methods for conservation laws
subtitle: ''
summary: ''
authors:
- Hendrik Ranocha
- Michael Schlottke-Lakemper
- Jesse Chan
- Andrés M. Rueda-Ramírez
- Andrew R. Winters
- Florian Hindenlang
- Gregor J. Gassner
tags:
- cs.MS
- cs.NA
- math.NA
- physics.comp-ph
categories: []
date: 2021, submitted-01-01
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
publishDate: '2022-10-23T09:14:44.345728Z'
publication_types:
- '2'
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
publication: '*ACM Trans. Math. Softw.*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2112.10517
---
