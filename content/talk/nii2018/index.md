---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving the Flexibility and Robustness of Derivative-Free Optimization Solvers"
event: National Institute of Informatics Invited Seminar
event_url:
location: National Institute of Informatics, Tokyo
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Classical nonlinear optimization algorithms require the availability of gradient evaluations for constructing local approximations to the objective and testing for convergence. In settings where the objective is expensive to evaluate or noisy, evaluating the gradient may be too expensive or inaccurate, so cannot be used; we must turn to optimization methods which do not require gradient information, so-called derivative-free optimization (DFO). In this talk, I will introduce DFO and discuss two new software packages for DFO: DFO-LS for nonlinear least-squares problems, and Py-BOBYQA (a Python implementation of Powell's BOBYQA) for general minimization problems. I will describe their novel features aimed at expensive and/or noisy problems, and show their state-of-the-art performance. Time permitting, I will also show a heuristic method which helps Py-BOBYQA to escape local minima, and show its favorable performance on global optimization problems."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-08-30
#date_end: 2018-08-30
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-09-24T11:42:52+10:00

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
