---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Online inference with debiased stochastic gradient descent"
authors: [Ruijian Han*, Lan Luo*, Yuanyuan Lin, Jian Huang]
date: 2023-06-12T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-12T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Biometrika, asad046"
publication_short: ""

abstract: "We propose a debiased stochastic gradient descent algorithm for online statistical inference with high-dimensional data. Our approach combines the debiasing technique developed in high-dimensional statistics with the stochastic gradient descent algorithm. It can be used for efficiently constructing confidence intervals in an online fashion. Our proposed algorithm has several appealing aspects: first, as a one-pass algorithm, it reduces the time complexity; in addition, each update step requires only the current data together with the previous estimate, which reduces the space complexity. We establish the asymptotic normality of the proposed estimator under mild conditions on the sparsity level of the parameter and the data distribution. We conduct numerical experiments to demonstrate the proposed debiased stochastic gradient descent algorithm reaches nominal coverage probability. Furthermore, we illustrate our method with a high-dimensional text dataset."
# Summary. An optional shortened abstract.
summary: ""

tags: [Confidence interval, High-dimensional statistics, Online learning, Stochastic gradient descent]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://academic.oup.com/biomet/advance-article-abstract/doi/10.1093/biomet/asad046/7232226
url_code: https://github.com/luolsph/OnlineDSGD
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
# projects: [MORA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
