---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RenewGLM"
authors: [Lan Luo, Peter X.-K. Song]
date: 2016-09-01T14:27:48-07:00


# Summary. An optional shortened abstract.
summary: "A new framework of real-time estimation and incremental inference in generalized
linear models (GLMs) with cross-sectional data streams."

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

url_pdf: https://rss.onlinelibrary.wiley.com/doi/full/10.1111/rssb.12352
url_code: https://github.com/luolsph/RenewGLM_pkg
url_dataset:
#url_poster: https://drive.google.com/file/d/1s9m6lB5HDWhc9jFlHGPnq7-Q3peC5bdh/view?usp=sharing
url_project:
#url_slides: https://drive.google.com/file/d/1c9qwsu4Og7KN8WnLrFukijzZoh9Mbd6D/view?usp=sharing
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "RenewGLM overview"
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
This paper presents an incremental updating algorithm to analyze streaming datasets using generalized linear models. The proposed method is formulated within a new framework of renewable estimation and incremental inference, in which the maximum likelihood estimator is renewed with current data and summary statistics of historical data. Our framework can be implemented within a popular distributed computing environment, known as Apache Spark, to scale up computation. Consisting of two data-processing layers, the Rho architecture enables to accommodate inference related statistics and to facilitate sequential updating of the statistics used in both estimation and inference. We establish estimation consistency and asymptotic normality of the proposed renewable estimator, in which the Wald test is utilized for an incremental inference. Our methods are examined and illustrated by various numerical examples from both simulation experiments and a real-world data analysis.
