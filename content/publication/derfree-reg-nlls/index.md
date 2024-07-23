---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Black-box Optimization Algorithms for Regularized Least-squares Problems"
authors: [Y. Liu, K. H. Lam, L. Roberts]
date: 2024-07-20
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-07-23T12:20:50+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We consider the problem of optimizing the sum of a smooth, nonconvex function for which derivatives are unavailable, and a convex, nonsmooth function with easy-to-evaluate proximal operator. Of particular focus is the case where the smooth part has a nonlinear least-squares structure. We adapt two existing approaches for derivative-free optimization of nonsmooth compositions of smooth functions to this setting. Our main contribution is adapting our algorithm to handle inexactly computed stationary measures, where the inexactness is adaptively adjusted as required by the algorithm (where previous approaches assumed access to exact stationary measures, which is not realistic in this setting). Numerically, we provide two extensions of the state-of-the-art DFO-LS solver for nonlinear least-squares problems and demonstrate their strong practical performance."

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

url_preprint: https://arxiv.org/abs/2407.14915
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
