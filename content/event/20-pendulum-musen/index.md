---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Control of a Triple Pendulum in Theory and Practice"
event: MUSEN Online Seminar Series
event_url: https://www.tu-braunschweig.de/en/musen
location: virtual
address:
  street: 
  city:
  region:
  postcode:
  country:
summary: "Design of linear controllers and practical realization for the triple
pendulum."
abstract: 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-10-08T16:45:00+02:00
date_end: 2020-10-04T18:00:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-04T15:37:39+02:00

authors: [Jan Heiland]
tags: ['pendulum']

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
url_slides:

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

The stabilization of a simple pendulum in the upright equilibrium is a common control task and can be realized with basic algorithms and basic hardware like Lego Mindstorm. The double pendulum is a popular example for a chaotic system which means that the influence of small perturbations leads to unpredictable behavior. Still, linear feedback controllers that counteract perturbations in real time are capable to stabilize equilibria of a double pendulum as well as trajectories. For the control of a triple pendulum, the same linear theory applies. The third segment, however, adds additional technical difficulties that need to be tackled with powerful hardware.

In this talk, I will explain the principles of a linearization based 2-degrees of freedom controller design which is the combination of a feedforward control that prescribes a target trajectory and a feedback loop for stabilization of the system. For the nonlinear mathematical model of a triple pendulum, already the computation of the target trajectory and the feedforward control is a challenge. Further, I will discuss details of the implementation and practical problems that come with a physical setup.
