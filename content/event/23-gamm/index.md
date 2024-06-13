---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Computational Approaches to H-Infinity-robust Controller Design and System Norms for Large-scale Systems"
event: GAMM 2023 annual meeting
event_url:
location: TU Dresden
address:
  street:
  city: Dresden
  region:
  postcode:
  country: Germany
summary:
abstract: 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-06-01T18:31:10+02:00
date_end: 2023-06-01T18:31:10+02:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-06-01T18:31:10+02:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

math: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides: 23-gamm-hinf-cntrl-heiland.pdf

url_code:
url_pdf: https://arxiv.org/abs/2111.06516
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
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
---

The computation of controller gains for the (linearization based) $H_\infty$ robust control of linear (and nonlinear) dynamical systems amounts to the solution of indefinite Riccati equations. For large-scale systems, a direct approach is infeasible because of both computational efforts and memory requirements.

In this talk we review existing iterative approaches and then discuss our recent algorithm[^1] that merges the ideas of the *Riccati iteration*[^2] (that approaches solutions of the indefinite equations through a sequence of definite Riccati equations) and *low-rank ADI iterations*[^3] (as it has become a standard tool for solving large-scale Riccati equations numerically). For that we provide necessary and sufficient conditions for convergence and thorough numerical studies concerning run times and memory consumption.

In order to estimate the performance and robustness of controllers, one may resort to system norms which themselves pose a significant computational challenge. In the second part of this talk, we will illustrate suitable reformulations of the relevant system norms so that their estimation can be achieved by high-performant routines from numerical linear algebra[^4]. In view of robust control, we will in particular focus on estimates that also include system uncertainties and model reduction errors.

Finally, we will bring together the computation of the controller gains and the norm estimates to robustly stabilize incompressible flows in two different setups of the well-known cylinder wake.

[^1]: Benner, P.; Heiland, J. & Werner, S. W. R. *A low-rank solution method for Riccati equations with indefinite quadratic terms*, Numer. Algorithms, 2022
[^2]: Benner, P.; Heiland, J. & Werner, S. W. R.: *Robust output-feedback stabilization for incompressible flows using low-dimensional $H_\infty$-controllers*. Comput. Optim. Appl., 2022, 82, 225-249
[^3]: Lanzon, A.; Feng, Y. & Anderson, B.: *An iterative algorithm to solve Algebraic Riccati Equations with an indefinite quadratic term*, 2007 European Control Conference (ECC), 2007.
[^4]: Benner, P.; Bujanović, Z.; Kürschner, P. & Saak, J.: *RADI: A low-rank ADI-type algorithm for large scale algebraic Riccati equations*. Numer. Math., 2018.
