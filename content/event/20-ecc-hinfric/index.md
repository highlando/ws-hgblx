---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Equivalence of Riccati-Based Robust Controller Design for Index-1 Descriptor Systems and Standard Plants with Feedthrough"
event: "ECC 2020"
event_url: "https://ecc20.eu/"
location: "virtual"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "The equivalence of Riccati approaches for index-1 descriptor systems
and standard LTI systems with feedthrough."
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-05-13T15:00:00+03:00
date_end: 2020-05-13T17:00:00+03:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-04-11T16:01:00+02:00

authors: [Jan Heiland, Peter Benner]
tags: ["BenH20"]

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

links:
- name: Youtube 
  url: "https://youtu.be/CLE6uDpq5pE?t=8328"
  icon_pack: fab
  icon: youtube

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "http://janheiland.de/20-talk-ecc-hinfriccati/"

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

## Abstract

The Riccati-based approach to robust control is completely understood in theory
since long but seldom used for large-scale systems in practice. Only recently,
we have transferred iterative algorithms that allow the computation of solutions
to LQR Riccati equations in the large-scale setting to the indefinite Riccati
equations that appear in robust control. For descriptor systems, the relevant
Riccati equations are nonsymmetric and, for large-scale systems, there is no
established algorithm that can handle these even in the LQR case. 

In this paper, we show how the general theory for descriptor systems with
index-1 pencil coincides with the theory for standard linear time invariant case
with feedthrough terms. This provides an algorithm to characterize and to
compute the solution to the generalized indefinite Riccati equations via
standard Riccati equations. In view of feasibility for large-scale descriptor
systems, we illustrate how to arrive at the equivalent standard Riccati-equation
without resorting to the canonical form used in the derivation of the
theoretical results.
