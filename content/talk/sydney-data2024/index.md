---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An adaptively inexact first-order method for bilevel optimization with application to hyperparameter learning [slides available]"
event: Sydney Workshop on Mathematics of Data Science
event_url: https://www.maths.usyd.edu.au/u/USYD-MDSworkshop/
location: University of Sydney
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "A common problem in data science is the determination of model hyperparameters. One approach for learning hyperparameters is to use bilevel optimisation, where the lower-level problem is the standard learning optimisation problem, and the upper-level problem is to learn the hyperparameters (e.g. by minimising validation error). In this setting, particularly for large-scale problems, neither exact function values nor exact gradients are attainable, necessitating methods that only rely on inexact evaluation of such quantities. I will present a new bilevel optimisation algorithm with adaptive inexactness suitable for hyperparameter learning. Numerical results on problems from imaging demonstrate its robustness and strong performance. This is joint work with Mohammad Sadegh Salehi, Matthias Ehrhardt (University of Bath) and Subhadip Mukherjee (IIT Kharagpur)."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-12-05
#date_end: 2024-11-28T10:19:55+11:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2024-11-28T10:19:55+11:00

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
url_slides: roberts_data_science_workshop.pdf

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