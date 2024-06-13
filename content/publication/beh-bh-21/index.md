---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Invariant Galerkin Ansatz Spaces and Davison-Maki Methods for the Numerical
  Solution of Differential Riccati Equations
subtitle: ''
summary: ''
authors:
- Maximilian Behr
- Peter Benner
- Jan Heiland
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-09-10T21:47:52+02:00
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
publication_types:
- '2'
abstract: The differential Riccati equation appears in different fields of applied
  mathematics like control and system theory. Recently Galerkin methods based on Krylov
  subspaces were developed for the autonomous differential Riccati equation. These
  methods overcome the prohibitively large storage requirements and computational
  costs of the numerical solution. In view of memory efficient approximation, we review
  and extend known solution formulas and identify invariant subspaces for a possibly
  low-dimensional solution representation. Based on these theoretical findings, we
  propose a Galerkin projection onto a space related to a low-rank approximation of
  the algebraic Riccati equation. For the numerical implementation, we provide an
  alternative interpretation of the modified emphDavison-Maki method via the transformed
  flow of the differential Riccati equation, which enables us to rule out known stability
  issues of the method in combination with the proposed projection scheme. We present
  numerical experiments for large-scale autonomous differential Riccati equations
  and compare our approach with high-order splitting schemes.
publication: '*Applied Mathematics and Computation*'
---
