---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Pandoc vs. Pandemic"
subtitle: "what have tools ever done for you"
summary: ""
authors: []
tags: ["Productivity", "Markdown", "Off-topic"]
categories: []
date: 2021-04-18T14:36:55+02:00
lastmod: 2021-04-18T14:36:55+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

While things were shifting away from *away from keyboard*, I found little pleasures in seeing software tools in production. Most of all I enjoy small scripts[^1] that take a few lines of readable text and turn it into a [website for an online course](https://www.janheiland.de/courses/mathe2info-21/), into [lecture notes](https://www.janheiland.de/script-daes/basic-definitions-and-notions.html), or a [slide deck for presentation](http://www.janheiland.de/talk-gpuq/#/title-slide).

This all bases on `Markdown` text files and some interpreter and compiler. For the websites the interpreter is `hugo`, for the lecture nodes it is `bookdown`, and for the presentation it is `pandoc` and `reveal.js`.

The sources are conveniently edited in my favorite editor. With *syntax highlighting* and *code concealing*, the basic parts of the markup is partially hidden and already preinterpreted. 

{{< figure caption="Screenshot of an editor with markdown support." src="vim-scsh.png" >}}

The final compilation and interpretation is well kept out of sight and can be automated or not on many stages.

Together with other little *unix* tools[^2], it took me just one hour to [turn my notes](https://github.com/highlando/pandoc-markdown-book-template/blob/master/RUNME.md) on my *natural yeast recipes* into an *e-book* and arrange the pdf export such that it could be printed as an [8-page booklet on a single A4 page](https://www.instructables.com/A-one-sheet-of-paper-booklet/).

Please checkout the outcomes:

 * :orange_book: [Booklet of my recipes for baking](lm.pdf) 
 * :blue_book: [Ready to be printed and folded into a real booklet](ready-for-print.pdf) 

{{< figure src="the-booklet.jpg" caption="The printed booklet." >}}


[^1]: Similarly exciting and helpful but on a different level are high-end open source tools like `OBS` for screencasting and streaming or `audacity` for podcasting.
[^2]: Namely `Okular` for exporting epub to pdf, `pdftk` for rotating, cutting, and arranging, and `boomaga` 
