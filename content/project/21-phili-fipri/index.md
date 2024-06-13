---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MRI Fingerprinting with Philips"
summary: "on *Improving Fingerprinting in MRI scans*"
authors: []
tags: ["BA-MA", "Industry"]
categories: []
date: 2021-04-15T14:23:01+02:00
math: true

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
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
links:
- name: Job Ad
  url: mrf_msc_ovgu.pdf
---

# Supervisors
[Dr. Manuel Baumann (Philips Research)](http://manuelbaumann.de/), Jun-Prof. Jan Heiland FMA

# Wanted

A highly motivated Masters' student of mathematics or statistics that feels comfortable with the problem below and that, at best, has good command of a programming language.

# Problem Statement

MR Fingerprinting is a new, quantitative imaging technique in Magnetic Resonance Imaging (MRI)[^1]. In short, 
[^1]: See here for a scientific paper on MR Fingerprinting: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3602925/

1. MR Fingerprinting relies on the simulation of the Bloch equation, a parameter-dependent ODE for the magnetization $M$ of the form 
$$\dot{M}(t) = f(M(t), B(t), T_1, T_2),$$
where the magnetic field $B$ is determined by the parameters of the acquisition. 

2. Variation of the relaxation times $T_1$ and $T_2$ yield a series of trajectories forming a so-called dictionary.

3. Fingerprinting means the matching of the acquired under-sampled data with the dictionary entries for querying the relevant tissue-specific parameters.

The development and implementation opens a number of options for a Master's project:

 * **System Theory:** Re-formulation of the MRF dictionary computation as an input-state-output system and model order reduction of the underlying Bloch equation. While the reformulation enables the matching by established system identification routines, a reduced order model can be used for a-posteriori checks of the selected parameters or for enriching the dictionary in the relevant parameter range.

 * **Statistics:** The estimation of parameters based on data is a common task in statistics. Apart from implementing and testing relevant routines for Fingerprinting, the inclusion of tailored statistical approaches for the particular problem of Fingerprinting can be useful for improving the dictionary in general and for providing confidence estimates for the selection obtained from classical matching.

 * **Optimization:** Fingerprinting seeks for the best match of collected data with the precomputed dictionary entries. Tools from mathematical optimization will be used to improve the reliability of the selected optimum and to enhance both the data aquisition and the dictionary through optimal design.

# How to apply

Please see the [job advertisement](mrf_msc_ovgu.pdf) and apply by June 30.
