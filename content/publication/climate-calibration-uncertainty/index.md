---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Does Model Calibration Reduce Uncertainty in Climate Projections?"
authors: [S. F. B. Tett, J. M. Gregory, N. Freychet, C. Cartis, M. J. Mineter, L. Roberts]
date: 2021-06-04
doi: "10.1175/JCLI-D-21-0434.1"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-01

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Climate"
publication_short: "J. Climate"

abstract: "Uncertainty in climate projections is large as shown by the likely uncertainty ranges in Equilibrium Climate Sensitivity (ECS) of 2.5-4K and in the Transient Climate Response (TCR) of 1.4-2.2K. Uncertainty in model projections could arise from the way in which unresolved processes are represented, the parameter values used, or the targets for model calibration. We show that, in two climate model ensembles which were objectively calibrated to minimise differences from observed large scale atmospheric climatology, uncertainties in ECS and TCR are about two to six times smaller than in the CMIP5 or CMIP6 multi-model ensemble. We also find that projected uncertainties in surface temperature, precipitation and annual extremes are relatively small. Residual uncertainty largely arises from unconstrained sea-ice feedbacks. The 20+ year old HadAM3 standard model configuration simulates observed hemispheric scale observations and pre-industrial surface temperatures about as well as the median CMIP5 and CMIP6 ensembles while the optimised configurations simulates these better than almost all the CMIP5 and CMIP6 models. Hemispheric scale observations and pre-industrial temperatures are not systematically better simulated in CMIP6 than in CMIP5 though the CMIP6 ensemble seems to better simulate patterns of large-scale observations than the CMIP5 ensemble and the optimised HadAM3 configurations. Our results suggest that most CMIP models could be improved in their simulation of large scale observations by systematic calibration. However, the uncertainty in climate projections (for a given scenario) likely largely arises from the choice of parametrisation schemes for unresolved processes (“structural uncertainty”), with different tuning targets another possible contributor."

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

#url_pdf: https://doi.org/10.1175/JCLI-D-21-0434.1
url_code: https://github.com/SimonTett/Jclim21_calibrate
url_dataset: https://doi.org/10.7488/ds/3051
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

### Mathematical summary

Typically parameter tuning for large-scale climate models is not easy, as the models are computationally expensive and include chaotic dynamics (so small parameter perturbations can produce large differences in results). Here, we use the derivative-free optimization solver [DFO-LS](https://github.com/numericalalgorithmsgroup/dfols) to perform parameter tuning of the atmostpheric physics model [HadAM3](https://doi.org/10.1007/s003820050009) to several global climate observations using a limited number of model runs. We found DFO-LS to be more effective and robust than previous optimizers. 

We found multiple locally optimal parameter combinations which fit observed climate data well - in fact, just as well as the new [CMIP5](https://pcmdi.llnl.gov/mips/cmip5/) and [CMIP6](https://pcmdi.llnl.gov/CMIP6/) model collections (which include much newer climate models than HadAM3). Interestingly, further analysis shows that these quite different parameter combinations give quite similar climate predictions, with a much smaller range of uncertainties than the different models in the CMIP5/CMIP6 collections. This suggests that much of the uncertainty in global climate predictions is not due to the specific parameter tuning approach, but to the modelling choices (e.g. parametrizations of different physical processes) and perhaps the specific observational data used for parameter fitting. It also suggests that newer climate models would benefit from more sophisticated parameter calibration techniques.


