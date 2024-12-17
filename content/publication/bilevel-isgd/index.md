---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Bilevel Learning with Inexact Stochastic Gradients"
authors: [M. S. Salehi, S. Mukherjee, L. Roberts, M. J. Ehrhardt]
date: 2024-12-16
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-12-18T09:21:47+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Bilevel learning has gained prominence in machine learning, inverse problems, and imaging applications, including hyperparameter optimization, learning data-adaptive regularizers, and optimizing forward operators. The large-scale nature of these problems has led to the development of inexact and computationally efficient methods. Existing adaptive methods predominantly rely on deterministic formulations, while stochastic approaches often adopt a doubly-stochastic framework with impractical variance assumptions, enforces a fixed number of lower-level iterations, and requires extensive tuning. In this work, we focus on bilevel learning with strongly convex lower-level problems and a nonconvex sum-of-functions in the upper-level. Stochasticity arises from data sampling in the upper-level which leads to inexact stochastic hypergradients. We establish their connection to state-of-the-art stochastic optimization theory for nonconvex objectives. Furthermore, we prove the convergence of inexact stochastic bilevel optimization under mild assumptions. Our empirical results highlight significant speed-ups and improved generalization in imaging tasks such as image denoising and deblurring in comparison with adaptive deterministic bilevel methods."

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

url_preprint: https://arxiv.org/abs/2412.12049
url_pdf:
url_code:
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
