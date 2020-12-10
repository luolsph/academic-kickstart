---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "YONO"
authors: [Lan Luo, Xichen She, Jiexuan Cao, Yunlong Zhang, Yijiang Li, Peter X.K. Song]
date: 2020-12-02T14:27:48-07:00

# Summary. An optional shortened abstract.
summary: "Detection and prediction of ovulation by incorporating biorhythm information in processing high frequency
  basal body temperature measurements via hidden Markov model (HMM)."

tags: [Basal body temperature, hidden Markov model, prediction, ovulation, tracking data, wearable]
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
url_media: https://spectrum.ieee.org/the-human-os/biomedical/devices/a-wearable-that-helps-women-get-not-get-pregnant
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "YONO overview"
  focal_point: "Right"
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

Objective: We present a non-invasive wearable device for fertility monitoring and propose an effective and flexible statistical learning algorithm to detect and predict ovulation using data captured by this device. Methods: The system consists of an earpiece, which measures the ear canal temperature every 5 minutes during night sleep hours, and a base station that transmits data to a smartphone application for analysis. We establish a data-cleaning protocol for data preprocessing and then fit a Hidden Markov Model (HMM) with two hidden states of high and low temperature to identify the more probable state of each time point via the predicted probabilities. Finally, a post-processing procedure is developed to incorporate biorhythm information to form a time-course biphasic profile for each subject. Results: The performance of the proposed algorithms applied to data collected by the device are compared with traditional methods in terms of match rate with self-reported ovulation days confirmed with Ovulation Prediction Kit. Empirical study results from a group of 34 users yielded significant improvements over the traditional methods in terms of detection accuracy (with sensitivity 92.31%) and prediction power (23.07% higher). Conclusion: We demonstrated the feasibility for reliable ovulation detection and prediction with high-frequency temperature data collected by a non-invasive wearable device. Significance: Traditional fertility monitoring methods are often either inaccurate or inconvenient. The wearable device and learning algorithm presented in this paper provides a user-friendly and reliable platform for tracking ovulation, which may have a broad impact on both fertility research and real-world family planning.
