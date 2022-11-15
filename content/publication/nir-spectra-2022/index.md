---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the selection of the weighting parameter value in optimizing Eucalyptus globulus pulp yield models based on NIR spectra"
authors: [Y. Zhen, T. X. Ho, L. Roberts, L. R. Schimleck, A. Sinha]
date: 2022-11-15
doi: "10.1007/s00226-022-01431-9"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-11-16T09:46:51+11:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Wood Science and Technology"
publication_short: ""

abstract: "Prediction of pulp yield of *Eucalyptus globulus* wood samples based on partial least squares (PLS) regression can be optimized by utilizing specific near infrared (NIR) wavelengths. A critical feature of this approach is the weighting of constraint conditions. Equal weighting balances optimization in terms of calibration and prediction; however, there is a lack of knowledge regarding prediction performance of wood property models when different weight factors are used. In this study, pulp yield models were developed using two *E. globulus* data sets characterized by narrow (5%) and extreme (22.6%) yield ranges and represented by untreated and second derivative NIR spectra. The global optimization solver pySOT was used to optimize the performance of a PLS regression model in terms of wavelengths selected and number of latent variables. A linear function of R-squares for calibration ($R_c^2$) and prediction ($R_p^2$) sets was utilized as the objective function with the aim of maximizing $\\alpha R_c^2 + (1-\\alpha)R_p^2$ for all values of $\\alpha$ between 0 (maximizing $R_p^2$ without concern for $R_c^2$) and 1 (only maximizing $R_c^2$). Values of $\\alpha \\leq 0.8$ provided good predictive performance, whereas $\\alpha \\geq 0.9$ tended to overfit the calibration data indicating that models are robust for values of $\\alpha$ from 0 to 0.8. Representative wavelengths for each data set were identified and assigned to corresponding wood components through a band assignment process. Strong agreement was observed for $\\alpha \\leq 0.8$; however, for $\\alpha \\geq 0.9$, identified wavelengths generally occurred in regions unrelated to vibrations arising from specific wood components."

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
