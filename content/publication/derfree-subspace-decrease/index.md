---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Expected decrease for derivative-free algorithms using random subspaces"
authors: [W. Hare, L. Roberts, C. W. Royer]
date: 2024-08-23
doi: "10.1090/mcom/4011"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-10T12:12:14+10:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Mathematics of Computation"
publication_short: ""

abstract: "Derivative-free algorithms seek the minimum of a given function based only on function values queried at appropriate points. Although these methods are widely used in practice, their performance is known to worsen as the problem dimension increases. Recent advances in developing randomized derivative-free techniques have tackled this issue by working in low-dimensional subspaces that are drawn at random in an iterative fashion. The connection between the dimension of these random subspaces and the algorithmic guarantees has yet to be fully understood. In this paper, we develop an analysis for derivative-free algorithms (both direct-search and model-based approaches) employing random subspaces. Our results leverage linear local approximations of smooth functions to obtain understanding of the expected decrease achieved per function evaluation. Although the quantities of interest involve multidimensional integrals with no closed-form expression, a relative comparison for different subspace dimensions suggest that low dimension is preferable. Numerical computation of the quantities of interest confirm the benefit of operating in low-dimensional subspaces."

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

url_preprint: https://arxiv.org/abs/2308.04734
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
