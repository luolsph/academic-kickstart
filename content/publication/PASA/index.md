---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel-and-Stream Accelerator for Computationally Fast Supervised Learning (submitted)"
authors: [Emily C. Hector*, Lan Luo*, and Peter X.-K. Song (* Co-first author)]
date: 2021-4-3T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-03T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "The Canadian Journal of Statistics"
publication_short: ""

abstract: "Two dominant distributed computing strategies have emerged to overcome the computational bottleneck of supervised learning with big data: parallel data processing in the MapReduce paradigm and serial data processing in the online streaming paradigm. Despite the two strategies' common divide-and-combine approach, they differ in how they aggregate information, leading to different trade-offs between statistical and computational performance. In this paper, we propose a new hybrid paradigm, termed a {\em Parallel-and-Stream Accelerator (PASA)}, that uses the strengths of both strategies for computationally fast and statistically efficient supervised learning. PASA's architecture nests online streaming processing into each distributed and parallelized data process in a MapReduce framework. PASA leverages the advantages and mitigates the disadvantages of both the MapReduce and online streaming approaches to deliver a more flexible paradigm satisfying practical computing needs. We study the analytic properties and computational complexity of PASA, and detail its implementation for two key statistical learning tasks. We illustrate its performance through simulations and a large-scale data example building a prediction model for online purchases from advertising data."
# Summary. An optional shortened abstract.
summary: ""

tags: [Confidence distribution, Divide and conquer, Generalized method of moments, Online learning, Prediction]
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
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
 projects: [PASA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
