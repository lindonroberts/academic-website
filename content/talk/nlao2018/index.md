---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving the efficiency of derivative-free methods for nonlinear least squares problems"
event: 6th IMA Conference on Numerical Linear Algebra and Optimization
event_url:
location: University of Birmingham
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "We present DFO-GN, a derivative-free version of the Gauss-Newton method for solving nonlinear least-squares problems. As is common in derivative-free optimization, DFO-GN uses interpolation of function values to build a model of the objective, which is then used within a trust-region framework to give a globally-convergent algorithm requiring $O(\\epsilon^{-2})$ iterations to reach approximate first-order criticality within tolerance $\\epsilon$. This algorithm is a simplification of the method by Zhang, Conn and Scheinberg (SIOPT, 2010), where we replace quadratic models for each residual with linear models. We demonstrate that DFO-GN performs comparably to the method of Zhang et al. in terms of objective evaluations, as well as having a substantially faster runtime and improved scalability. Finally, we present two extensions of DFO-GN designed to improve its performance on large-scale and noisy problems respectively."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-06-27
#date_end: 2018-06-27
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-09-24T11:43:03+10:00

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
