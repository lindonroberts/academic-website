---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Dynamic Bilevel Learning with Inexact Line Search"
authors: [M. S. Salehi, S. Mukherjee, L. Roberts, M. J. Ehrhardt]
date: 2023-08-22
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-22T14:02:18+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In various domains within imaging and data science, particularly when addressing tasks modeled utilizing the variational regularization approach, manually configuring regularization parameters presents a formidable challenge. The difficulty intensifies when employing regularizers involving a large number of hyperparameters. To overcome this challenge, bilevel learning is employed to learn suitable hyperparameters. However, due to the use of numerical solvers, the exact gradient with respect to the hyperparameters is unattainable, necessitating the use of methods relying on approximate gradients. State-of-the-art inexact methods a priori select a decreasing summable sequence of the required accuracy and only assure convergence given a sufficiently small fixed step size. Despite this, challenges persist in determining the Lipschitz constant of the hypergradient and identifying an appropriate fixed step size. Conversely, computing exact function values is not feasible, impeding the use of line search. In this work, we introduce a provably convergent inexact backtracking line search involving inexact function evaluations and hypergradients. We show convergence to a stationary point of the loss with respect to hyperparameters. Additionally, we propose an algorithm to determine the required accuracy dynamically. Our numerical experiments demonstrate the efficiency and feasibility of our approach for hyperparameter estimation in variational regularization problems, alongside its robustness in terms of the initial accuracy and step size choices."

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

url_preprint: https://arxiv.org/abs/2308.10098
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
