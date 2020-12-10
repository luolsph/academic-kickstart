---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MORA"
authors: [Lan Luo, Peter X.-K. Song]
date: 2020-12-02T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: "Journal of the Royal Statistical Society: Series B, 82, Part 1, 69-97"
#publication_short: ""


# Summary. An optional shortened abstract.
summary: "MORA is a real-time regression analysis method that incorporates both dynamics 
and inter-data batch correlation."

tags: [Dynamic effects, online learning, Kalman filter, streaming data, state-space mixed models]
categories: []
#featured: false

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
header:
image:
  caption: "MORA overview"
  focal_point: "Smart"
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

New data collection and storage technologies have given rise to a new field of streaming data analytics, including real-time statistical methodology for online data analyses. Most existing online learning methods are based on homogeneity assumption such that the sequence of samples are independent and identical. However, inter-data batch correlation and dynamically evolved batch-specific effects are among the key defining features in real-world streaming data such as electronic health records and mobile health data. This paper is built in the framework of state space mixed models in which the observed data stream is driven by a latent state process that follows a Markov process. In this setting, online maximum likelihood estimation is challenged by high-dimensional integrals and complex covariance structures. In this paper, we develop a Kalman filter based real-time regression analysis method that enables to update both point estimates and standard errors of the fixed population average effects while adjusting for dynamic hidden effects. Both theoretical justification and numerical experiments have demonstrated that our proposed online method has similar statistical properties to its offline counterpart but enjoys great computation efficiency. We also apply this method to analyze an electronic health record data example.
