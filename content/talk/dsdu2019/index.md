---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving the scalability of model-based derivative-free optimization [slides available]"
event: Data Science Down Under
event_url: https://carma.newcastle.edu.au/meetings/dsdu
location: University of Newcastle
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Derivative-free optimization (DFO) methods are an important class of optimization routines for many problems in data science, such as hyperparameter optimization and adversarial attacks for neural networks. However, in model-based DFO methods, the computational cost of constructing local models and Lagrange polynomials can be high. As a result, these algorithms are not as suitable for large-scale problems as derivative-based methods. In this talk, I will introduce a derivative-free method based on exploration of random subspaces, suitable for nonlinear least-squares problems. This method has a substantially reduced computational cost (in terms of linear algebra), while still making progress using few objective evaluations. I will also discuss how this approach may be extended to DFO for general nonlinear optimization problems."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-12-11
#date_end: 2019-12-11
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-11-05T21:37:52+11:00

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
url_slides: roberts_dsdu.pdf

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
