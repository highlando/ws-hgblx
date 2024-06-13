---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inverse Triple Pendulum"
summary: "An inverted triple pendulum as a test bench and demonstrator for control routines."
authors: []
tags: ["BA-MA", "Industry", "software", "pendulum"]
categories: []
date: 2019-09-17T11:56:57+02:00

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
slides: ""

draft: false
---

Our institute has a triple pendulum connected to a cart that can be controlled by a computer. Stabilizing a pendulum in upright position is a common control benchmark. Controlling a double or triple pendulum requires powerful hardware and a sophisticated and well-tuned software. The hardware was set up by the Magdeburg-based company Hasomed, the software has been developed in our institute for over 20 years.

The triple pendulum is used to test control algorithms in experiments. As opposed to pure simulations, the application in hardware comes with additional challenges like delays in communication and changing environmental parameters. 

Also, the pendulum is used to showcase the need and potential of control algorithms in regular visits of students or the public at our annual long night of science.

News
---

 * September 11th: Visit of a project group from the Hubertus Gymnasium.

 * March 1st: In cooperation with [Hasomed](https://www.hasomed.de), we revise the controller software and the interface to the hardware. The result will be test blocks for basic control tasks like the controlled transversion of the pendulum both in open loop and closed loop regimes. *HASOMED* co-sponsors the development and will distribute the developed software under a license agreement with the MPI-MD.

Resources
---

 * This [poster](pendulum-de.pdf) explains the setup and the basic procedures of the control scheme as well as typical application areas (in German).

 * This video shows the swingup and swingdown of the triple pendulum in slow motion:

{{< video src="triple_swingup_slomo.MP4" controls="yes" >}}
