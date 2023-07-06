---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Real-time Regression Analysis of Streaming Clustered Data With Possible Abnormal Data Batches"
authors: [Lan Luo, Ling Zhou, and Peter X.-K. Song]
date: 2022-01-01T14:27:48-07:00
doi: "https://doi.org/10.1080/01621459.2022.2026778"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-22T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of the American Statistical Association (Theory and Methods)"
publication_short: ""

abstract: "This paper develops an incremental learning algorithm based on quadratic inference function (QIF) to analyze streaming datasets with correlated outcomes such as longitudinal data and clustered data. We propose a renewable QIF (RenewQIF) method within a paradigm of renewable estimation and incremental inference, in which parameter estimates are recursively renewed with current data and summary statistics of historical data, but with no use of any historical subject-level raw data. We compare our renewable estimation method with both offline QIF and offline generalized estimating equations (GEE) approach that process the entire cumulative subject-level data all together, and show theoretically and numerically that our renewable procedure enjoys statistical and computational efficiency. We also propose an approach to diagnose the homogeneity assumption of regression coefficients via a sequential goodness-of-fit test as a screening procedure for occurrences of abnormal data batches. We implement the proposed methodology by expanding existing Spark's Lambda architecture for the operation of statistical inference and data quality diagnosis. We illustrate the proposed methodology by extensive simulation studies and an analysis of streaming car crash datasets from the National Automotive Sampling System-Crashworthiness Data System (NASS CDS). The supplementary material is available online."

# Summary. An optional shortened abstract.
summary: ""

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

url_pdf: https://arxiv.org/pdf/2106.15794.pdf
url_code: https://github.com/luolsph/RenewQIF_pkg
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
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [RenewQIF]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
