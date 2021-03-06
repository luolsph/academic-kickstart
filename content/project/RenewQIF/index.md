---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RenewQIF"
authors: [Lan Luo, Peter X.-K. Song]
date: 2020-12-02T14:27:48-07:00

# Summary. An optional shortened abstract.
summary: "An incremental data analytic based on quadratic inference function (QIF) to analyze streaming correlated datasets, with a screening procedure on occurrences of abnormal data batches."

tags: [Incremental statistical analysis, quadratic inference function, 
generalized estimating equation, Spark computing platform]
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
#url_code: https://github.com/luolsph/RenewQIF_pkg
url_dataset:
url_poster: 
url_project:
#url_slides: https://drive.google.com/file/d/1c9qwsu4Og7KN8WnLrFukijzZoh9Mbd6D/view?usp=sharing
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "RenewQIF overview"
  focal_point: "Smart"
#  preview_only: false

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

This paper develops an incremental learning algorithm based on quadratic infer- ence function (QIF) to analyze streaming datasets with correlated outcomes such as longitudinal and clustered data. We propose a renewable QIF (RenewQIF) method within a paradigm of renewable estimation and incremental inference, in which parameter estimates are recursively renewed with current data and summary statistics of historical data, but with no use of any historical subject-level raw data. We compare our renewable estimation method with the oracle generalized estimating equations (GEE) approach that processes the entire cumulative subject-level data, and show theoretically and numerically that our renewable procedure enjoys statistical and computational efficiency. We also consider checking the homogeneity assumption of regression coefficients via a sequential goodness-of-fit test as a screening procedure on occurrences of abnormal data batches. We implement the proposed methodology by expanding existing Spark’s Lambda architecture to accommodate the screening tool box, which is examined via extensive simulation studies. Also, we illustrate the proposed method by an analysis of streaming car crash datasets from the National Automotive Sampling System-Crashworthiness Data System (NASS CDS).
