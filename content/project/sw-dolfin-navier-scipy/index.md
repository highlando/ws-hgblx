---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "dolfin-navier-scipy"
summary: "A Python package that provides an interface between *scipy* and *FEniCS* in view of solving Navier-Stokes Equations."
authors: [Jan Heiland]
tags: ["software"]
categories: []
date: 2019-07-03T18:53:50+02:00

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
- icon_pack: fab
  icon: github
  name: Github
  url: 'https://github.com/highlando/dolfin_navier_scipy'
- name: Documentation
  url: 'http://dolfin-navier-scipy.readthedocs.org/en/latest/index.html'
- name: DOI
  url: https://doi.org/10.5281/zenodo.3238622
- name: PyPI
  url: https://pypi.org/project/dolfin-navier-scipy/1.0.0/

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

A Python package that provides an interface between *scipy* and *FEniCS* in view of solving Navier-Stokes Equations. *FEniCS* is used to perform a Finite Element discretization of the equations. The assembled coefficients are exported as sparse matrices for use in *scipy*. Nonlinear and time-dependent parts are evaluated and assembled on demand. Visualization is done via the *FEniCS* interface to *paraview*. 

## Features

 * modelling of control and observation
 * second order time integration with explicit treatment of the nonlinearities

## Video

{{< youtube a1iDcEIRmvU >}}

Simulation of the *Karman Vortex Street*. See the [relevant commit here](https://github.com/highlando/dolfin_navier_scipy/commit/ae907dc2266076a635c89d62726696e63b3fdc85).
