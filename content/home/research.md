+++
# Research widget.
widget = "research"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Research"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[research]]
  title = "PASA"
  company = "University of Iowa"
  company_url = ""
  location = "Iowa City, Iowa"
  date_start = "2020-06-01"
  date_end = ""
  description = """ PASA is a hybrid architecture that integrates online streaming processing 
  into each distributed and parallelized data process in a MapReduce framework
  
  * Emily Hector, Lan Luo and Peter X.-K. Song (2020+) Parallel-and-stream accelerator (PASA) in fast computing for big data (submitted).
  """
  
[[research]]
  title = "RenewGLM"
  company = "University of Michigan"
  company_url = ""
  location = "Ann Arbor, Michigan"
  date_start = "2016-09-01"
  date_end = "2019-05-01"
  description = """Real-time regression analysis in generalized linear models with cross-sectional datasets
  
  * Lan Luo, Peter X.-K. Song (2020). Renewable Estimation and Incremental Inference in Generalized Linear Models with Streaming Datasets. Journal of the Royal Statistical Society: Series B, 82, Part 1, 69-97.
  * Observations are independent
  * Homogeneity assumption on model parameters
  * R package: RenewGLM
  """


[[research]]
  title = "RenewQIF"
  company = "University of Michigan"
  company_url = ""
  location = "Ann Arbor, Michigan"
  date_start = "2017-09-01"
  date_end = "2020-05-30"
  description = """Real-time regression analysis in quadratic inference functions with correlated streaming data
  
  * Lan Luo, Peter X.-K. Song (2020+). Real-time Regression Analysis of Streaming Clustered Data With Possible Abnormal Data Batches. Journal of the American Statistical Association (Theory and Methods) (invited revision).
  * Within-data batch correlation
  * Detection of abnormal data batches
  * R package: RenewQIF
  """

[[research]]
  title = "MORA"
  company = "University of Michigan"
  company_url = ""
  location = "Ann Arbor, Michigan"
  date_start = "2019-09-01"
  date_end = ""
  description = """ Real-time regression analysis in state-space mixed effects models with heterogeneous streaming data
  
  * Batch-specific effects are modeled as dynamically evolved latent states
  * Lan Luo, Peter X.-K. Song (2020+). Multivariate online regression analysis with heterogeneous streaming data (submitted).
  """

[[research]]
  title = "YONO"
  company = "University of Michigan"
  company_url = ""
  location = "Ann Arbor, Michigan"
  date_start = "2017-02-01"
  date_end = "2019-04-01"
  description = """
  Established procedures for pre-processing and modeling of high frequency
  basal body temperature measurements via Hidden Markov Model (HMM), as well as
  prediction of ovulation by incorporating biorhythm information
  """

+++
