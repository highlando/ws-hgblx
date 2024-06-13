---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Polytopic Autoencoders with Smooth Clustering for Reduced-order Modelling of
  Flows
subtitle: ''
summary: ''
authors:
- Jan Heiland
- Yongho Kim
tags: []
categories: []
date: '2024-01-01'
lastmod: 2024-01-23T10:15:35+01:00
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
- '0'
abstract: With the advancement of neural networks, there has been a notable increase,
  both in terms of quantity and variety, in research publications concerning the application
  of autoencoders to reduced-order models. We propose a polytopic autoencoder architecture
  that includes a lightweight nonlinear encoder, a convex combination decoder, and
  a smooth clustering network. Supported by several proofs, the model architecture
  ensures that all reconstructed states lie within a polytope, accompanied by a metric
  indicating the quality of the constructed polytopes, referred to as polytope error.
  Additionally, it offers a minimal number of convex coordinates for polytopic linear-parameter
  varying systems while achieving acceptable reconstruction errors compared to proper
  orthogonal decomposition (POD). To validate our proposed model, we conduct simulations
  involving two flow scenarios with the incompressible Navier-Stokes equation. Numerical
  results demonstrate the guaranteed properties of the model, low reconstruction errors
  compared to POD, and the improvement in error using a clustering network.
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2401.10620
- name: Code
  url: https://doi.org/10.5281/zenodo.10491870
---
