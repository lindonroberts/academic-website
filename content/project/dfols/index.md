---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DFO-LS"
summary: "Derivative-free solver for nonlinear least-squares problems"
authors: []
tags: []
categories: []
date: 2018-02-06

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

url_code: "https://github.com/numericalalgorithmsgroup/dfols"
url_pdf: "https://doi.org/10.1145/3338517"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

[DFO-LS](https://github.com/numericalalgorithmsgroup/dfols) is a Python library for solving nonlinear least-squares problems, with optional box constraints. It is a derivative-free solver, meaning it only requires function values, and no first (or higher) derivatives. As a result, it is particularly useful for situations when function evaluations are expensive, or when they are noisy.

Examples of using DFO-LS for parameter fitting and solving nonlinear systems of equations are given in the [documentation](https://numericalalgorithmsgroup.github.io/dfols). There is also a demonstration of how standard (derivative-based) solvers fail when function evaluations are noisy.

DFO-LS is based on [DFO-GN](https://github.com/numericalalgorithmsgroup/dfogn), but includes more features, including: improved robustness to noise, reduced initialization cost, and greater flexibility in parameter choices.

A version of DFO-LS is also available in the commercial [NAG Library](https://www.nag.co.uk/content/nag-library).

