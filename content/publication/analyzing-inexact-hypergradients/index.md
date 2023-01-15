---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Analyzing Inexact Hypergradients for Bilevel Learning"
authors: [M. J. Ehrhardt, L. Roberts]
date: 2023-01-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-16T09:23:49+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Submitted"
publication_short: ""

abstract: "Estimating hyperparameters has been a long-standing problem in machine learning. We consider the case where the task at hand is modeled as the solution to an optimization problem. Here the exact gradient with respect to the hyperparameters cannot be feasibly computed and approximate strategies are required. We introduce a unified framework for computing hypergradients that generalizes existing methods based on the implicit function theorem and automatic differentiation/backpropagation, showing that these two seemingly disparate approaches are actually tightly connected. Our framework is extremely flexible, allowing its subproblems to be solved with any suitable method, to any degree of accuracy. We derive a priori and computable a posteriori error bounds for all our methods, and numerically show that our a posteriori bounds are usually more accurate. Our numerical results also show that, surprisingly, for efficient bilevel optimization, the choice of hypergradient algorithm is at least as important as the choice of lower-level solver."

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

url_preprint: https://arxiv.org/abs/2301.04764
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
