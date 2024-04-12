---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An adaptively inexact first-order method for bilevel optimization with application to hyperparameter learning"
authors: [M. S. Salehi, S. Mukherjee, L. Roberts, M. J. Ehrhardt]
date: 2024-04-10
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

abstract: "Various tasks in data science are modeled utilizing the variational regularization approach, where manually selecting regularization parameters presents a challenge. The difficulty gets exacerbated when employing regularizers involving a large number of hyperparameters. To overcome this challenge, bilevel learning can be employed to learn such parameters from data. However, neither exact function values nor exact gradients with respect to the hyperparameters are attainable, necessitating methods that only rely on inexact evaluation of such quantities. State-of-the-art inexact gradient-based methods a priori select a sequence of the required accuracies and cannot identify an appropriate step size since the Lipschitz constant of the hypergradient is unknown. In this work, we propose an algorithm with backtracking line search that only relies on inexact function evaluations and hypergradients and show convergence to a stationary point. Furthermore, the proposed algorithm determines the required accuracy dynamically rather than manually selected before running it. Our numerical experiments demonstrate the efficiency and feasibility of our approach for hyperparameter estimation on a range of relevant problems in imaging and data science such as total variation and field of experts denoising and multinomial logistic regression. Particularly, the results show that the algorithm is robust to its own hyperparameters such as the initial accuracies and step size."

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
