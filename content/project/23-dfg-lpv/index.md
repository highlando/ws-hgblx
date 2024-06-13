---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "LPV Approximations for Nonlinear Controller Design"
summary: ""
authors: []
tags: ["grants", "phd", "postdoc"]
categories: []
date: 2023-07-20T11:00:00+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: DFG-funded
  url: https://gepris.dfg.de/gepris/projekt/527443892?language=en
  icon_pack: fas
  icon: globe
- name: Apply
  url: https://ovgu.b-ite.careers/e1dns
  icon_pack: fas
  icon: envelope

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Project Description

The computer-aided control system design for nonlinear large-dimensional systems is a tremendous task as it has to cope both with model complexities due to nonlinear dynamics and with computational challenges that are caused by the system’s size. While linear algebra packages and algorithms for solving, say, Riccati equations can handle the large system sizes, the theory for Linear Parameter Varying (LPV) systems has been successfully employed for nonlinear controller design. Within this project, we want to make the LPV theory accessible for numerical controller design for nonlinear large-scale systems.

The core idea is to use approximations to provide low-dimensional LPV surrogate models for nonlinear input-affine systems which then will be the base for designing the controller by established LPV theory. 

Representations of nonlinear systems as LPV systems have been used before for nonlinear controller design. A new direction that we will explore here will be the inclusion of model order reduction techniques to primarily reduce the parameter dimension in order to make the controller design numerically feasible also for systems of large state space dimension. 

If model reduction is involved, the surrogate model for the controller design is no more exact which may lead to failures of the controller. Within this project, we want to establish to what extend such model errors can be compensated by robustness margins of the controllers. For plain linear time-invariant systems, the standard H-infinity theory provides general relevant results. A generalization of these results to cover parameter reductions in LPV systems is another objective of this project. 

For the realization in numerical simulations, nonlinear model reduction approaches are the method of choice as they have proven to outperform linear approaches like Proper Orthogonal Decomposition (POD) at very low dimensions. This project aims at gaining practical insights in using these comparatively recent approaches for reducing the parameter dimension in LPV models to be employed for controller design for nonlinear large-scale systems like spatially discretized Navier-Stokes equations.

# Related Publications


# Related Talks


# Funding Information

| Funding Agency | DFG
|----------------|--------------|
| Duration       | 3 Years      |
| Overall Budget | 180'000 Euro |


