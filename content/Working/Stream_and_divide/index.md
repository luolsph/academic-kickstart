---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Statistical Inference for Streamed Longitudinal Data (under revision)"
authors: [Lan Luo, Emily C. Hector]
date: 2021-4-3T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-3T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: "The Canadian Journal of Statistics"
publication_short: ""

abstract: "Modern longitudinal data, for example from wearable devices, measures biological signals on a fixed set of participants at a diverging number of time points. Traditional statistical methods are not equipped to handle the computational burden of repeatedly analyzing the cumulatively growing dataset each time new data is collected. We propose a new estimation and inference framework for the streaming updating of point estimates and their standard errors across serially collected dependent datasets. The key technique is a decomposition of the extended score function of the quadratic inference function constructed over the cumulative longitudinal data into a sum of summary statistics over data batches. We show how this sum can be recursively updated without the need to access the whole dataset, resulting in a computationally efficient streaming procedure with minimal loss of statistical efficiency. We prove consistency and asymptotic normality of our streaming estimator as the number of data batches diverges, even as the number of independent participants remains fixed. Extensive simulations highlight the computational and statistical advantage of our approach over traditional statistical methods that analyze the cumulative longitudinal dataset. Finally, our streaming framework is used to investigate the relationship between physical activity and several diseases through the analysis of accelerometry data from the National Health and Nutrition Examination Survey."
# Summary. An optional shortened abstract.
summary: "Modern longitudinal data, for example from wearable devices, measures biological signals on a fixed set of participants at a diverging number of time points. Traditional statistical methods are not equipped to handle the computational burden of repeatedly analyzing the cumulatively growing dataset each time new data is collected. We propose a new estimation and inference framework for the streaming updating of point estimates and their standard errors across serially collected dependent datasets. The key technique is a decomposition of the extended score function of the quadratic inference function constructed over the cumulative longitudinal data into a sum of summary statistics over data batches. We show how this sum can be recursively updated without the need to access the whole dataset, resulting in a computationally efficient streaming procedure with minimal loss of statistical efficiency. We prove consistency and asymptotic normality of our streaming estimator as the number of data batches diverges, even as the number of independent participants remains fixed. Extensive simulations highlight the computational and statistical advantage of our approach over traditional statistical methods that analyze the cumulative longitudinal dataset. Finally, our streaming framework is used to investigate the relationship between physical activity and several diseases through the analysis of accelerometry data from the National Health and Nutrition Examination Survey."

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
#projects: [MORA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
