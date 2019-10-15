---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Derivative-Free Algorithms for Nonlinear Optimisation Problems"
authors: [L. Roberts]
date: 2019-08-27
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-09-24T11:22:55+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "DPhil Thesis (University of Oxford)"
publication_short: "DPhil Thesis"

abstract: "Minimising a nonlinear function is a ubiquitous problem in applications, and standard algorithms need accurate evaluations of the function and its derivatives. However, if the function is black-box, expensive to evaluate, or noisy, it may be impractical or even impossible to obtain accurate derivatives, and we require derivative-free optimisation (DFO). Model-based DFO methods perform well in practice, taking many features from derivative-based methods, but can have lower performance for noisy problems and a high linear algebra cost. In this thesis, we aim to improve the flexibility, robustness and scalability of state-of-the- art methods for model-based DFO by designing, analysing, implementing and comprehensively testing three new algorithms for nonlinear optimisation, with a special focus on nonlinear least-squares problems (such as parameter fitting). \n

The first, DFO-LS, is designed for nonlinear least-squares problems, and is simpler than existing methods, constructing linear residual models with a flexible approach. DFO-LS can benefit from a reduced initialisation cost, and has improved scalability and runtime over existing methods without a performance penalty. DFO-LS also has features for noisy problems, including a novel multiple restarts mechanism, which are low cost in evaluations and linear algebra, giving DFO-LS better performance compared to existing techniques for handling noise. \n

We then introduce Py-BOBYQA, an extension of BOBYQA (Powell, 2009) with a similar multiple restarts mechanism to DFO-LS, amongst other new enhancements. It matches or outperforms BOBYQA and other state-of-the-art solvers on both smooth and noisy problems. We also propose a simple extension of Py-BOBYQA that may enable it to escape local minima and progress towards the global optima. \n

Lastly, we introduce, for large-scale nonlinear least-squares problems, DFBGN, the first model-based DFO method to optimise in low-dimensional subspaces at each iteration. DFBGN has lower linear algebra costs, improved runtime, and hence improved performance on large-scale problems than DFO-LS, as it can perform many more iterations within a reasonable runtime limit. It can also make progress under very small evaluation budgets, with a low runtime cost."

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

url_pdf: https://ora.ox.ac.uk/objects/uuid:ec76e895-6eee-491a-88ed-b4ed10fa6003
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
