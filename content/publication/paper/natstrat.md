---
abstract: In causal inference, natural strata are a new compromise between conventional strata and matching in a fixed ratio, say pair matching or matching two controls to each treated individual. Like matching in a fixed ratio, natural strata (a) do not require weights, (b) balance many measured covariates beyond those that define the strata and (c) provide closer balance for a measured continuous covariate coarsely cut to form strata. Unlike matching in a fixed ratio, the ratio of controls to treated individuals need not be an integer, so if the data permit a fixed ratio comparison of 1-to-2.5 or even 1-to-0.75, then these ratios are possible using natural strata. Optimal natural strata are defined by a moderate number of fixed strata plus an integer program that minimizes the imbalance in many other measured covariates that are not used to specify the strata. Solving large integer programs is computationally difficult. A tool in the theory of approximation algorithms is ‘randomized rounding of a linear program’ to produce an integer solution-- a fractional solution to a linear program defines a probability distribution for an integer-valued random variable which is sampled. We apply this tool in a new way to produce natural strata and develop new properties of randomized rounding in this context. When proportional strata are impractical, we approximate them by minimizing the earthmover distance to proportionality. The method is applied to study birth outcomes for older and younger mothers in the United States in 2018. An R package natstrat is available at CRAN.
authors:
- admin
- Dylan S. Small
- Paul R. Rosenbaum
date: "2022-05-17T00:00:00Z"
doi: "10.1111/rssa.12848"
featured: false
image:
projects: []
publication: 'Journal of the Royal Statistical Society: Series A'
publication_short: ""
publication_types: ["2"]
publishDate: "2022-05-17T00:00:00Z"
slides: 
summary: 
tags:
title: Using randomized rounding of linear programs to obtain unweighted natural strata that balance many covariates
url_code: https://cran.r-project.org/web/packages/natstrat/index.html
url_dataset: ""
url_pdf: 
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---


