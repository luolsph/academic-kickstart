---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Identification of gene pairs through penalized regression
Subject to constraints"
authors: []
date: 2019-06-22T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-22T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: """In this paper, we propose a parsimonious model representation and develop efficient algorithms for identification. Particularly, we derive an equivalent model subject to a sum-to-zero constraint in penalized linear regression, where the correspondence between nonzero coefficients in these models is established. Most importantly, it reduces the model complexity of the traditional approach from the quadratic order to the linear order in the number of candidate genes, while overcoming the difficulty of model nonidentifiablity. Computationally, we develop an algorithm using the alternating direction method of multipliers (ADMM) to deal with the constraint. Numerically, we demonstrate that the proposed method outperforms the traditional method in terms of the statistical accuracy. Moreover, we demonstrate that our ADMM algorithm is more computationally efficient than a coordinate descent algorithm with a local search. Finally, we illustrate the proposed method on a prostate cancer dataset to identify gene pairs that are associated with pre-operative prostate-specific antigen."""

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

url_pdf:https://bmcbioinformatics.biomedcentral.com/track/pdf/10.1186/s12859-017-1872-9
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
