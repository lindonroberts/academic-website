---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Improving the Flexibility and Robustness of Model-Based Derivative-Free Optimization Solvers"
authors: [C. Cartis, J. Fiala, B. Marteau, L. Roberts]
date: 2019-09-24T10:54:39+10:00
doi: "10.1145/3338517"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-24T10:54:39+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Mathematical Software"
publication_short: "ACM Trans. Math. Soft"

abstract: "We present two software packages for derivative-free optimization (DFO): DFO-LS for nonlinear least-squares problems and Py-BOBYQA for general objectives, both with optional bound constraints. Inspired by the Gauss-Newton method, DFO-LS constructs simplified linear regression models for the residuals and allows flexible initialization for expensive problems, whereby it can begin making progress after as few as two objective evaluations. Numerical results show DFO-LS can gain reasonable progress on some medium-scale problems with fewer objective evaluations than is needed for one gradient evaluation. DFO-LS has improved robustness to noise, allowing sample averaging, regression-based model construction, and multiple restart strategies with an auto-detection mechanism. Our extensive numerical experimentation shows that restarting the solver when stagnation is detected is a cheap and effective mechanism for achieving robustness, with superior performance over sampling and regression techniques. The package Py-BOBYQA is a Python implementation of BOBYQA (Powell 2009), with novel features such as the implementation of robustness to noise strategies. Our numerical experiments show that Py-BOBYQA is comparable to or better than existing general DFO solvers for noisy problems. In our comparisons, we introduce an adaptive accuracy measure for data profiles of noisy functions, striking a balance between measuring the true and the noisy objective improvement."

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

url_pdf: https://arxiv.org/abs/1804.00154
url_code: https://github.com/numericalalgorithmsgroup/pybobyqa
#url_code: https://github.com/numericalalgorithmsgroup/dfols
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
