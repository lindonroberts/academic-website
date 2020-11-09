---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DFBGN"
summary: "Derivative-free block Gauss-Newton method (for large-scale nonlinear least-squares problems)"
authors: []
tags: []
categories: []
date: 2020-10-23

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

url_code: "https://github.com/numericalalgorithmsgroup/dfbgn"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

[DFBGN](https://github.com/numericalalgorithmsgroup/dfbgn) is a Python library for solving nonlinear least-squares problems. It is a derivative-free solver, meaning it only requires function values, and no first (or higher) derivatives. As a result, it is particularly useful for situations when function evaluations are expensive, or when they are noisy. Compared to [DFO-LS](https://github.com/numericalalgorithmsgroup/dfols), it is better-suited to large-scale problems (i.e. with many variables to be optimized).

This package is described in Chapter 7 of [my doctoral thesis](https://ora.ox.ac.uk/objects/uuid:ec76e895-6eee-491a-88ed-b4ed10fa6003). A standalone paper is currently in preparation.