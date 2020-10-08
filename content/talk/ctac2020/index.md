---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inexact Derivative-Free Optimisation for Bilevel Learning [slides available]"
event: CTAC 2020
event_url: https://www.ctac2020.unsw.edu.au/
location: University of New South Wales
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "When variational regularisation methods are used to solve inverse problems, they suffer from the drawback of having potentially many parameters which the user must specify. A common approach to handle this is to learn these parameters from data. While mathematically appealing, this strategy leads to a bilevel optimisation problem which is difficult to solve computationally. Theoretically, algorithms for bilevel learning rely on access to exact solutions to the lower-level regularisation problem, but this condition is not guaranteed in practice. In this talk, we describe a novel approach using dynamic accuracy derivative-free optimisation for solving bilevel learning problems. This approach still retains convergence guarantees but allows the regularisation problem to be solved inexactly and hence is able to be implemented in practice. Using problems from image analysis, we demonstrate that our approach dramatically reduces the computational requirements of bilevel learning. This is joint work with Matthias Ehrhardt (Bath)."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-08-31
#date_end: 2020-08-31
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-10-08T16:26:27+11:00

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
url_slides: roberts_ctac.pdf

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
