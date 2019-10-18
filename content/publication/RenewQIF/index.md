---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Real-time Regression Analysis of Streaming Clustered Data With Possible Abnormal Data Batches."
authors: [Lan Luo, Peter X.-K. Song]
date: 2019-10-22T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-22T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Journal of the American Statistical Association (Theory and Methods) 
(submitted)"
publication_short: ""

abstract: "This paper develops an incremental data analytic based on quadratic inference function (QIF) to analyze streaming datasets with correlated outcomes such as longitudinal and clustered data. We propose a renewable QIF (RenewQIF) method in a paradigm of renewable estimation and incremental inference, in which parameter estimates are recursively renewed with current data and summary statistics of historical data, but with no use of any historical subject-level raw data. We show theoretically and numerically that our renewable estimation method is asymptotically equivalent to the oracle generalized estimating equations (GEE) approach that directly processes the entire cumulative subject-level data. We also consider checking the homogeneity assumption of regression coefficients via a sequential goodness-of-fit test as a screening procedure on occurrences of abnormal data batches. We implement the proposed methodology on an expanded platform of existing Spark’s Lambda architecture to accommodate the screening tool box. Through extensive simulation studies we demonstrate that RenewQIF enjoys both statistical and computational efficiencies. In addition, we illustrate the proposed method by an analysis of streaming car crash datasets from the National Automotive Sampling System-Crashworthiness Data System (NASS CDS)."

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

url_pdf: 
url_code: https://github.com/luolsph/RenewQIF_pkg
url_dataset:
url_poster: 
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
