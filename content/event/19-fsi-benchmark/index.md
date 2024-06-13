---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A benchmark for fluid rigid body interaction with standard CFD packages
event: GAMM CSE Workshop
event_url: https://www.uni-ulm.de/mawi/institut-fuer-numerische-mathematik/forschung/gamm-cse-workshop-2019/
location: G&uuml;nzburg
summary: A fluid rigid body benchmark case in a fixed domain
abstract: This talk presents a setup that we have designed to particularly investigate the effects regarding the free rotation of a spherical object in a flow channel in 2D and 3D.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-11-21T16:00:00+01:00
date_end: 2019-11-21T16:30:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-11-21T18:22:27+01:00

authors: [Henry von Wahl, Thomas Richter, Jan Heiland, Christoph Lehrenfeld, Piotr Minakowski]
tags: [dns.py]

# Is this a featured talk? (true/false)
featured: false

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

# Optional filename of your slides within your talk's folder or a URL.
url_slides: https://janheiland.de/19-talk-fsi-benchmark/

url_code:
url_pdf: https://arxiv.org/abs/1908.04637
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
links:
- icon_pack: fab
  icon: github
  name: Source
  url: https://github.com/highlando/19-talk-fsi-benchmark
---

The interaction between a fluid flow and rigid bodies appears in many
physical applications. The flow around a free rigid body causes both
displacement and rotation of that body, via the forces and torque
exerted from the fluid onto the body. Conversely, the motion of the body
causes changes in the flow. The complexity that comes with coupling
models for fluid and elastic or rigid bodies and the numerical
challenges due to evolving geometrical domains make reliable and
benchmark computations very necessary though difficult to perform. This
talk presents a setup that we have designed to particularly investigate
the effects regarding the free rotation of a spherical object in a flow
channel in 2D and 3D. This setup connects to the well known benchmark
of *flow past a cylinder* \[1\] and is accessible to standard CFD
software.

![](media/image1.png)

> Figure 1: Spatial configuration of the 3D setup.

In this setup the flow applies a torque force on the object. The induced
rotation then couples back to the flow via the boundary conditions. We
discuss the governing equations of this fluid structure interaction
problem; namely the incompressible Navier-Stokes equations and the
relevant realizations of Newton’s second law that relates the rotation
of the rigid body to the forces acting on it. The proposed benchmark
configurations comprise two and three spatial dimensions and
quasi-stationary (low Reynolds-number) and periodic (high
Reynolds-number) regimes. For a discretization independent comparison of
the results, we also propose significant, nondimensionalized
characteristic values.

The benchmark cases were solved numerically with various approaches and software tools so that the computed characteristic values could be reported within in a reasonable confidence interval.

In this talk, we introduce the mathematical model, discuss the characteristic and challenges of the benchmark cases, and present the various implementation and their particular advantages. The codes that were reported on in our work \[2\] as well as the raw data and postprocessing routines are available \[3\] for further exploration and reproduction.

References
==========

1.  M Schäfer and S Turek: *Benchmark computations of laminar flow around a cylinder. (With support by F. Durst, E. Krause and R. Rannacher)* Flow Simulation with High-Performance Computers II. DFG priority research program results 1993-1995, 1996.

2.  H von Wahl et al.: *Numerical benchmarking of fluid-rigid body interactions*. Computers & Fluids, 2019.

3.  DOI:[10.5281/zenodo.3253455](https://doi.org/10.5281/zenodo.3253455)
