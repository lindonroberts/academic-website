---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Direct search based on probabilistic descent in reduced spaces"
authors: [L. Roberts, C. W. Royer]
date: 2022-04-05T17:38:14+10:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-04-05

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Submitted"
publication_short: ""

abstract: "Derivative-free algorithms seek the minimum value of a given objective function without using any derivative information. The performance of these methods often worsen as the dimension increases, a phenomenon predicted by their worst-case complexity guarantees. Nevertheless, recent algorithmic proposals have shown that incorporating randomization into otherwise deterministic frameworks could alleviate this effect for direct-search methods. The best guarantees and practical performance are obtained when employing a random vector and its negative, which amounts to drawing directions in a random one-dimensional subspace. Unlike for other derivative-free schemes, however, the properties of these subspaces have not been exploited.
In this paper, we study a generic direct-search algorithm in which the polling directions are defined using random subspaces. Complexity guarantees for such an approach are derived thanks to probabilistic properties related to both the subspaces and the directions used within these subspaces. By leveraging results on random subspace embeddings and sketching matrices, we show that better complexity bounds are obtained for randomized instances of our framework. A numerical investigation confirms the benefit of randomization, particularly when done in subspaces, when solving problems of moderately large dimension."

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

url_pdf: https://arxiv.org/abs/2204.01275
url_code: https://github.com/lindonroberts/directsearch
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
