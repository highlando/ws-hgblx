+++
title = "Open Master Thesis"
date = 2019-09-01
draft = false
profile = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["BA-MA"]

# Project summary to display on homepage.
summary = "on *Modelling of the impact of multiple scattering on measurements using luminescent particles*"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

# Supervisors
Jun-Prof. Benoit Fond FVST, Jun-Prof. Jan Heiland FMA

# Problem statement:

Thermographic Particle Image Velocimetry is an optical technique to
measure the temperature and velocity of fluid flows (gas or liquid), by
introducing small (micron-size) luminescent particles into the flow[^1]. It has been applied in various types of flows including internal
combustion engines, film cooling flows, and in natural convection. When
using micron-size particles, the particles follow the flow, and their
temperature is at equilibrium with the gas. If we illuminate the
particles with a UV laser, the particles absorb the UV light, and then,
they re-emit visible light called luminescence. The colour of the
emitted light depends on the temperature of the particles, so by
recording the light on a camera, we can determine the temperature of the
particle, and therefore that of the gas.

Typically, we collect light from the particles with a lens as shown in
Fig. 1 a). Only particles that are within the thin laser sheet (shown in
purple) are excited, and emit frequency shifted light (here shown by the
red rays). A filter is placed in front of the camera to only collect the
frequency-shifted luminescence. However, when there are many particles,
light emitted by particle can bounce off other particles, and the
spatial information may be lost. Pathways for wanted and unwanted
luminescence being collected on the detectors are shown on Figures 1.
The wanted scenario mentioned above is a). In unwanted scenarios b-d),
either excitation light or luminescence emission is scattered by
particles outside the probe volume. The objective of this project is to
theoretically quantify the contribution of unwanted light by
implementing Mie scattering theory[^2] with random particle positions. More
detail on Mie scattering theory can be found the following link:

# Task description:

a)  Improve the current model by developing numerical schemes to
    increase the spatial resolution to computational cost ratio.

b)  Quantify the contribution of multiple scattering relative (b and c)
    for a reference experimental configuration.

c)  Validate the model against the result of measurements performed in
    the reference experimental configuration in Fond´s group.

d)  Determine the scaling factor (size of coflow, seeding density ratio,
    imaginary over real part of index of refraction), and compare with
    experimental observations.

e)  Estimate the relative probability of three particle events compared
    to the two particle event of scenarios b and c).



[^2]: *The scattering of light may be thought of as the redirection of light that takes place when an electromagnetic (EM) wave (i.e. an incident light ray) encounters an obstacle or nonhomogeneity, in our case the scattering particle...* [pdf](http://plaza.ufl.edu/dwhahn/Rayleigh%20and%20Mie%20Light%20Scattering.pdf)

[^1]: C. Abram, B. Fond, and F. Beyrau, “Temperature measurement
techniques for gas and liquid flows using thermographic phosphor tracer
particles,” Prog. Energy Combust. Sci. 64, 93 – 156 (2018). [pdf](http://ltces.dem.ist.utl.pt/lxlaser/lxlaser2016/finalworks2016/papers/01.5_3_154paper.pdf)
