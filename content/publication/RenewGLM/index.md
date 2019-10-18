---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Renewable Estimation and Incremental Inference in Generalized Linear Models
with Streaming Datasets"
authors: [Lan Luo, Peter X.-K. Song]
date: 2019-10-18T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-22T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of the Royal Statistical Society: Series B (Statistical Methodology) 
(accepted)"
publication_short: ""

abstract: "This paper presents an incremental updating algorithm to analyze streaming datasets using generalized linear models. The proposed method is formulated within a new framework of renewable estimation and incremental inference, in which the estimates are renewed with current data and summary statistics of historical data. We design a new paradigm named as the Rho architecture consisting of two data-processing lay- ers to implement the proposed method. This implementation platform expands the current popular Apache Spark Lambda architecture which enables to accommodate the inference-related statistics and to facilitate sequential updating of estimation and inference. Both estimation consistency and asymptotic normality of the renewable estimator are established, through which the Wald test is utilized for incremental inference. Our methods are examined and illustrated by various numerical examples from both simulation experiments and a real-world data analysis."

# Summary. An optional shortened abstract.
summary: ""

tags: [Incremental statistical analysis, Lambda architecture, online learning, 
stochastic gradient descent algorithm, Spark computing platform]
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
url_code: https://github.com/luolsph/RenewGLM_pkg
url_dataset:
url_poster: https://drive.google.com/file/d/1s9m6lB5HDWhc9jFlHGPnq7-Q3peC5bdh/view?usp=sharing
url_project:
url_slides: https://drive.google.com/file/d/16qfcZqwK8qUD-Kgb_QfMGv8GB3ejxtvi/view?usp=sharing
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
