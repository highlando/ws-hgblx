---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Tensor-Galerkin POD for Efficient Uncertainty Quantification in PDEs with Multivariate Random Parameters"
event: "GAMM Annual Meeting"
event_url: https://gamm202021.de
location: virtual
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-03-17T14:00:00+01:00
# date_end: 2021-01-29T12:26:32+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-01-29T12:26:32+01:00

authors: [Jan Heiland, Peter Benner]
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
url_slides: http://www.janheiland.de/talk-gpuq/#/title-slide

url_code: https://doi.org/10.5281/zenodo.4005724
url_pdf: https://arxiv.org/abs/2009.01055
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

## Abstract

The statistically sound treatment of modelled uncertainties in simulations comes with significant additional computational costs. Since a deterministic model can already be arbitrarily complex, running statistics for general problems may soon become infeasible unless some kind of model reduction is involved.

In this talk we present a multidimensional Galerkin Proper Orthogonal Decomposition (Galerkin POD)
that simultaneously reduces the physical dimensions of the model and the dimensions related to
the uncertainties.

Using basic tensor calculus we extend our recent work of space-time Galerkin POD [1] to arbitrary dimensions and apply it to PDEs with multivariate uncertain. By means of a numerical example we illustrate the procedure and how it outperforms POD based on random snapshots.

## References:
[1] Baumann, M.; Benner, P. & Heiland, J. Space-Time Galerkin POD with Application in Optimal Control of Semi-linear Parabolic Partial Differential Equations SIAM J. Sci. Comput., 2018, 40, A1611-A1641
