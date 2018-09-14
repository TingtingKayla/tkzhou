+++
title = "Variable Selection in Causal Inference"
date = "2018-09-14"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tingting Zhou", "Michael R. Elliott", "Roderick J.A. Little"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "manuscript in preparation "
publication_short = ""

# Abstract and optional shortened version.
abstract = "Inference about causal effects from observational studies requires the measurement and control of confounding variables. A useful class of methods is based on estimating the propensity of treatment assignment, given potential confounding variables, and then using the estimated propensity as a weight, or as a predictor in regression models for the outcome under alternative treatment assignments. In particular, we recently proposed a robust multiple-imputation based method, penalized spline of propensity for treatment comparisons (PENCOMP), that included a spline of the assignment propensity as a predictor. These methods are vulnerable to bias and inefficiency when the distributions of estimated propensities in the treatment groups have limited overlap. This situation can arise when conditioning on covariates that are strong predictors of treatment assignment but not confounders, because they are not related to the outcome. We consider here variable selection techniques that seek to restrict predictors in the propensity model to true confounders, thus improving overlap in the propensity distributions and increasing efficiency. We examine by simulation studies the impact of alternative variable selection techniques, including an extension of the adaptive lasso, on inferences from PENCOMP and weighting approaches. We also compare alternative approaches to estimating standard errors of estimated causal effects, finding that  the bootstrap method based on Efron's formula for incorporating the variability of model selection is advantageous when the data are noisy."

abstract_short = "We consider variable selection techniques that seek to restrict predictors in the propensity model to true confounders, thus improving overlap in the propensity distributions and increasing efficiency. We also propose a new version of PENCOMP via bagging that also incorporates the variability of model selection, which can be advantageous when the data are noisy. We examine by simulation studies and the MACS dataset the impact of various variable selection techniques, including an extension of the adaptive lasso, on inferences from both versions of PENCOMP, AIPTW and IPTW."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
#url_pdf = "#"
#url_preprint = "#"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

#More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
