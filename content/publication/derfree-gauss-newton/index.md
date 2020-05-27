---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Derivative-Free Gauss-Newton Method"
authors: [C. Cartis, L. Roberts]
date: 2019-05-20
doi: "10.1007/s12532-019-00161-7"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-24T10:54:33+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematical Programming Computation"
publication_short: "Math. Prog. Comp"

abstract: "We present DFO-GN, a derivative-free version of the Gauss–Newton method for solving nonlinear least-squares problems. DFO-GN uses linear interpolation of residual values to build a quadratic model of the objective, which is then used within a typical derivative-free trust-region framework. We show that DFO-GN is globally convergent and requires at most $O(\\epsilon^{-2})$ iterations to reach approximate first-order criticality within tolerance $\\epsilon$. We provide an implementation of DFO-GN and compare it to other state-of-the-art derivative-free solvers that use quadratic interpolation models. We demonstrate numerically that despite using only linear residual models, DFO-GN performs comparably to these methods in terms of objective evaluations. Furthermore, as a result of the simplified interpolation procedure, DFO-GN has superior runtime and scalability. Our implementation of DFO-GN is available at https://github.com/numericalalgorithmsgroup/dfogn (https://doi.org/10.5281/zenodo.2629875)."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_preprint: https://arxiv.org/abs/1710.11005
url_code: https://github.com/numericalalgorithmsgroup/dfogn
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
