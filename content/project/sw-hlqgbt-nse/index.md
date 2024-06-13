---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "hinf-lqgbt-nse"
summary: "Python module for application of (Hinf-)LQG-balanced truncation for low-order controllers for the stabilization of Navier-Stokes equations"
authors: [Jan Heiland]
tags: ["software", "Navier-Stokes", "control"]
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
  url: 'https://github.com/highlando/lqgbt-oseen'
- name: Documentation
  url: 'http://lqgbt-for-flow-stabilization.readthedocs.org/en/latest/'

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

Python module for application of (Hinf-)LQG-balanced truncation for low-order controllers for the stabilization of Navier-Stokes equations.

As an example we consider the stabilization of the cylinder wake at moderate Reynoldsnumbers via boundary control and distributed observation.

# Features

 * implementation of various Riccati-based feedback controllers
   * static state feedback
   * observer based LQGBT feedback
   * robustified LQGBT feedback
 * integration with M.E.S.S or my [homebrew Riccati solver](www.github.com/highlando/sadptprj_riclyap_adi) for flow related equations
