---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Statistical Inference for Streamed Longitudinal Data"
authors: [Lan Luo, Jingshen Wang, and Emily C. Hector]
date: 2023-02-05T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-05T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Biometrika, 110(4), 841-858"
publication_short: ""

abstract: "Modern longitudinal data, for example from wearable devices, measure biological signals on a fixed set of participants at a diverging number of time points. Traditional statistical methods are not equipped to handle the computational burden of repeatedly analyzing the cumulatively growing dataset each time new data is collected. We propose a new estimation and inference framework for dynamic updating of point estimates and their standard errors along sequentially collected datasets with dependence both within and between datasets. The key technique is a decomposition of the extended inference function vector of the quadratic inference function constructed over the cumulative longitudinal data into a sum of summary statistics over data batches. We show how this sum can be recursively updated without the need to access the whole dataset, resulting in a computationally efficient streaming procedure with minimal loss of statistical efficiency. We prove the consistency and asymptotic normality of our streaming estimator as the number of data batches diverges, even as the number of independent participants remains fixed. Simulations highlight the advantages of our approach over traditional statistical methods that assume independence between data batches. Finally, we investigate the relationship between physical activity and several diseases through the analysis of National Health and Nutrition Examination Survey accelerometry data."
# Summary. An optional shortened abstract.
summary: ""

tags: [Generalized method of moments, Online learning, Quadratic inference functions, Scalable computing, Serial dependence]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://academic.oup.com/biomet/article-abstract/110/4/841/7048657
url_code: https://github.com/ehector/SLA
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
projects: [SLA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
