---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Online Two-Way Estimation and Inference via Linear Mixed-Effects Models"
authors: [Lan Luo, Lexin Li]
date: 2022-08-02T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-02T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Statistics in Medicine (Accepted)"
publication_short: ""

abstract: "In this article, we tackle the estimation and inference problem of analyzing distributed streaming data that is collected continuously over multiple data sites. We propose an online two-way approach via linear mixed-effects models. We explicitly model the site-specific effects as random-effect terms, and tackle both between-site heterogeneity and within-site correlation. We develop an online updating procedure that does not need to re-access the previous data and can efficiently update the parameter estimate, when either new data sites, or new streams of sample observations of the existing data sites, become available. We derive the non-asymptotic error bound for our proposed online estimator, and show that it is asymptotically equivalent to the offline counterpart based on all the raw data. We compare with some key alternative solutions both analytically and numerically, and demonstrate the advantages of our proposal. We further illustrate our method with two data applications."
# Summary. An optional shortened abstract.
summary: ""

tags: [Collaborative inference, Divide-and-conquer, Linear mixed-effects models, Meta-analysis, Online learning.]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.9557
#url_code: https://github.com/luolsph/OnlineCausal
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
projects: [OnlineMEM]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
