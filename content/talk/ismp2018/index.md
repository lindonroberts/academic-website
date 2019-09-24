---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A flexible, robust and efficient derivative-free solver for least-squares"
event: ISMP 2018
event_url:
location: University of Bordeaux
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "We present DFO-LS, a software package for derivative-free optimization (DFO) for nonlinear least-squares problems, that has simplified models, flexible initialization and improved robustness to noise. Inspired by the Gauss-Newton method, DFO-LS constructs simplified linear regression models for the residuals. DFO-LS also has improved flexibility for expensive problems, whereby it can begin making progress from as few as two objective evaluations. Numerical results show DFO-LS can gain reasonable progress on some medium-scale problems with fewer objective evaluations than is needed for one gradient evaluation. For noisy problems, DFO-LS allows a wide variety of sample averaging methodologies, the construction of highly overdetermined regression models, and restart strategies. Our extensive numerical experimentation shows that restarting the solver when stagnation is detected is a cheap and effective mechanism for achieving robustness, with superior performance. We also discuss our package Py-BOBYQA, a Python implementation of BOBYQA (Powell, 2009) which implements some of these features for general objective problems."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-07-04
#date_end: 2018-07-04
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-09-24T11:42:57+10:00

authors: []
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
