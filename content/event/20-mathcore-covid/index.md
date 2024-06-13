---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mathematical modeling of infectious disease"
event: "MathCoRe Seminar"
event_url: "https://www.mathcore.ovgu.de/TEACHING/SEMINARS/index.php"
location: "virtual"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: ""
abstract: 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-07-02T11:00:00+01:00
date_end: 2020-07-02T12:00:00+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-04-11T16:01:00+02:00

authors: [Sara Grundel, Jan Heiland]
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

links:

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 
url_code:
url_pdf: "event/20-mathcore-covid/Grundel-Heiland-mathcore-cv19.pdf"
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

Within the last couple of months, the COVID-19 epidemic has determined our
public and private life with travel restrictions, lockdown, social distancing,
working from home, hygiene rules etc. The daily news informed about reproduction
rates and the numbers of current confirmed COVID-19 cases. The media prominently
advertised the strategy *stay at home* in order to *flatten the curve*.

In this joint talk, we present two mathematical modeling strategies for
infectious disease. In the first part, we consider a classical compartment
approach which splits the population into different groups, for example
*Susceptible*, *Infected*, *Recovered* (SIR model). The evolution of the numbers
in each compartment can be described mathematically in form of a system of
coupled ordinary differential equations. The transition rates between the
different compartments (e.g. infection rate, recovery rate) can be adjusted
through available data. For the modeling of the COVID-19 epidemic in Italy and
Germany, the SIDHARTE version of a compartment model has been developed[^1] in
order to simulate and predict the spread of the epidemic and to model possible
countermeasures.

In the second part of the talk, the spreading of the disease on a graph
representing a smaller population sample is presented. In this model the graph
represents a hospital or other institution in which a COVID-19 outbreak could be
harmful. In this model we are particularly interested in finding a suitable test
strategy, which is one way to apply control to the system. In general is the
question of the right control mechanisms to *flatten the curve* or slow the
spread of virus still an open one.

[^1]: G. Giordano, F. Blanchini, R. Bruno, P. Colaneri, A. Di Filippo, A. Di Matteo, M. Colaneri: Modelling the COVID-19 epidemic and implementation of population-wide interventions in Italy. Nat. Med. (2020)"
