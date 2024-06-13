---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Turnpike and Linear Systems Theory"
event: "csc seminar"
event_url: "https://www.mpi-magdeburg.mpg.de/csc/seminars/csc/2020"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "How turnpike for LQR problems follow from classical system theoretic
results and how it looks like for DAE constraints."
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-04-07T14:00:00+02:00
date_end: 2020-04-07T15:00:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-04-11T16:01:00+02:00

authors: [Jan Heiland]
tags: []

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
url_slides: "http://janheiland.de/20-talk-turnpike-dae/"

url_code:
url_pdf:
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
---

# Turnpike and Linear Systems Theory
## Old Formulas and New Results

It is often observed, that the solution to an optimal control problem on a
finite but large time horizon stays close to an associated steady state optimal
solution most of the time. This phenomenon is called *turnpike* property. It has
been addressed in the research of economics since the 60s and has become a
popular topic in systems and control in the last 20 years. 

The turnpike property is intimately related to the exponential decay of the
solution to a differential Riccati equation towards the stabilizing solution of
the associated algebraic Riccati equation (ARE). 

In this talk, I will show how the basic result on turnpike (namely that the linear quadratic regulator (LQR) problem enjoys the
turnpike property) follows from classical system theory results by Callier,
Willems, and Winkin[^1]. With these results, we can also directly address borderline
cases like that of undetectable systems. By means of an explicit formula for the
state transition matrix of the forward and backward closed loop system, we extend
the classical results to the affine case, i.e., the case with nonzero control
targets.

In the second part of the talk, we discuss the turnpike property of LQR
problems with DAE constraints. Under standard assumptions, we establish existence
of solutions to the generalized (nonsymmetric) differential Riccati equation
and conditions for their convergence to a solution of the generalized ARE. With
these results, we can characterize the turnpike property for DAE control
problems.


[^1]: Callier, F. M.; Winkin, J. & Willems, J. L. *Convergence of the
  time-invariant Riccati differential equation and LQ-problem: mechanisms of
  attraction*. International Journal of Control, Taylor & Francis, 1994, 59,
  983-1000.
