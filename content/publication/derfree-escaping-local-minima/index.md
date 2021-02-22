---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Escaping local minima with local derivative-free methods: a numerical investigation"
authors: [C. Cartis, L. Roberts, O. Sheridan-Methven]
date: 2021-02-19
doi: "10.1080/02331934.2021.1883015"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-24T10:54:50+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Optimization"
publication_short: ""

abstract: "We apply a state-of-the-art, local derivative-free solver, Py-BOBYQA, to global optimization problems, and propose an algorithmic improvement that is beneficial in this context. Our numerical findings are illustrated on a commonly-used test set of global optimization problems and associated noisy variants, and on hyperparameter tuning for the machine learning test set MNIST. As Py-BOBYQA is a model-based trust-region method, we compare mostly (but not exclusively) with other global optimization methods for which (global) models are important, such as Bayesian optimization and response surface methods; we also consider state-of-the-art representative deterministic and stochastic codes, such as DIRECT and CMA-ES. We find Py-BOBYQA to be competitive with global solvers that are provably designed for finding global optima, for all accuracy/budget regimes, in both smooth and noisy settings. In particular, Py-BOBYQA variants are best performing for smooth and multiplicative noise problems in high-accuracy regimes. As a by-product, some preliminary conclusions can be drawn on the relative performance of the global solvers we have tested with default settings."

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

url_preprint: https://arxiv.org/abs/1812.11343
url_code: https://github.com/numericalalgorithmsgroup/pybobyqa
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
