+++
title = "Talk: Stability Analysis of Time Stepping Schemes for Incompressible Flows from a DAE Perspective"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2019-10-02T16:10:00+02:00
date_end = 2019-10-02T16:35:00+02:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2019-05-26T14:19:01+02:00

authors = ["Robert Altmann", "Jan Heiland"]

location = "Eegmond an Zee, The Netherlands"

event = "Enumath @ TU Delft"
event_url = "https://www.enumath2019.eu/program/show_slot/103"

# Abstract. What's your talk about?
abstract = "By analysing the Kronecker index of the difference-algebraic equations, that represent commonly and successfully used time stepping schemes for the Navier-Stokes equations, we show that those time-integration schemes factually remove strangeness. The theoretical considerations are backed and illustrated by numerical examples."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

math = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

We consider the time discretization of the semi-discrete incompressible Navier-Stokes equations (NSE)

$
\begin{aligned}
	\quad \quad \quad M \dot v(t) &= N(v(t)) + J^Tp(t) + f(t), 
    \\\\\\\\
	0 &= Jv(t),
\end{aligned}
$

formulated in the velocity $v(t) \in \mathbb R^{n_v}$ and pressure $p(t) \in \mathbb R^{n_p}$, with $M\in \mathbb R^{n_v, n_v}$ being the mass matrix from the spatial discretization, $N\colon \mathbb R^{n_v} \to \mathbb R^{n_v}$ modelling the discretized convection and diffusion, and with $J\in \mathbb R^{n_p, n_v}$ and $J^T$ representing the discrete divergence and gradient operators.

It is commonly known that the semi-discrete incompressible Navier-Stokes equations can be classified as a differential-algebraic equation (DAE) of *differentiation index* $\nu=2$ so that a straight-forward time discretization, e.g. by the *implicit-Euler* method, will likely suffer from instabilities. To overcome these numerical difficulties, a large number of time stepping schemes, with *Chorin*'s projection or the *SIMPLE* scheme as notable examples, have been developed. 

In this talk, we trace down and illustrate the instability that origins from the index-2 structure and show that commonly and succesfully applied time-stepping schemes correspond to a reformulation of the semi-discrete NSE as an equivalent system of index-1. Also we show how a finite-element discretization by *Taylor-Hood* or *Crouzeix-Raviart* schemes can be modified such that the resulting semi-discrete NSE already is of index-1 so that standard time-integration schemes lead to stable pressure approximations.

**References**

 Altmann, R. &amp; Heiland, J.: *Finite Element Decomposition and Minimal Extension for Flow Equations*, ESAIM: M2AN, **2015**, 49, 1489--1509 

 Altmann, R. &amp; Heiland, J.: *Continuous, Semi-discrete, and Fully Discretized Navier-Stokes Equations*, DAE-Forum, Issue: *Applications of Differential-Algebraic Equations: Examples and Benchmarks*, Springer, **2018**

