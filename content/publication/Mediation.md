---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multivariate dynamic mediation analysis under a reinforcement learning framework"
authors: [Luo, L., Shi, C., Wang, J., Wu, Z., and Li, L.]
date: 2024-11-3T14:27:48-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-11-03T14:27:48-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint/Working paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "The Annals of Statistics (accepted)"
publication_short: ""

abstract: "
Mediation analysis is an important analytic tool commonly used in a
broad range of scientific applications. In this article, we study the problem of
mediation analysis when there are multivariate and conditionally dependent
mediators, and when the variables are observed over multiple time points. The
problem is challenging, because the effect of a mediator involves not only the
path from the treatment to this mediator itself at the current time point, but
also all possible paths pointed to this mediator from its upstream mediators,
as well as the carryover effects from all previous time points. We propose
a novel multivariate dynamic mediation analysis approach. Drawing inspiration
from the Markov decision process model that is frequently employed
in reinforcement learning, we introduce a Markov mediation process paired
with a system of time-varying linear structural equation models to formulate
the problem. We then formally define the individual mediation effect, built
upon the idea of simultaneous interventions and intervention calculus. We
next derive the closed-form expression, propose an iterative estimation procedure
under the Markov mediation process model, and develop a bootstrap
method to infer the individual mediation effect. We study both the asymptotic
property and the empirical performance of the proposed methodology,
and further illustrate its usefulness with a mobile health application.
"
# Summary. An optional shortened abstract.
summary: ""

tags: [Longitudinal data, Markov process, Mediation analysis, Mobile health, Reinforcement learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2310.16203
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
# projects: [MORA]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
