---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inexact Derivative-Free Optimization for Bilevel Learning"
authors: [M. J. Ehrhardt, L. Roberts]
date: 2021-02-07
doi: "10.1007/s10851-021-01020-8"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-24

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "J. Math. Imaging Vision"
publication_short: ""

abstract: "Variational regularization techniques are dominant in the field of mathematical imaging. A drawback of these techniques is that they are dependent on a number of parameters which have to be set by the user. A by now common strategy to resolve this issue is to learn these parameters from data. While mathematically appealing this strategy leads to a nested optimization problem (known as bilevel optimization) which is computationally very difficult to handle. A key ingredient in solving the upper-level problem is the exact solution of the lower-level problem which is practically infeasible. In this work we propose to solve these problems using inexact derivative-free optimization algorithms which never require to solve the lower-level problem exactly. We provide global convergence and worst-case complexity analysis of our approach, and test our proposed framework on ROF-denoising and learning MRI sampling patterns. Dynamically adjusting the lower-level accuracy yields learned parameters with similar reconstruction quality as high-accuracy evaluations but with dramatic reductions in computational work (up to 100 times faster in some cases)."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_preprint: https://arxiv.org/abs/2006.12674
url_code: https://github.com/lindonroberts/inexact_dfo_bilevel_learning
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
