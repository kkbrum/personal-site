---
abstract: "What is the best way to split one stratum into two to maximally reduce the within-stratum imbalance in many covariates? We formulate this as an integer program and approximate the solution by randomized rounding of a linear program. A linear program may assign a fraction of a person to each refined stratum. Randomized rounding views fractional people as probabilities, assigning intact people to strata using biased coins. Randomized rounding is a well-studied theoretical technique for approximating the optimal solution of certain insoluble integer programs. When the number of people in a stratum is large relative to the number of covariates, we prove the following new results: (i) randomized rounding to split a stratum does very little randomizing, so it closely resembles the linear programming relaxation without splitting intact people, (ii) the linear relaxation and the randomly rounded solution place lower and upper bounds on the unattainable integer programming solution, and because of (i) these bounds are often close, thereby ratifying the usable randomly rounded solution. We illustrate using an observational study that balanced many covariates by forming matched pairs composed of 2016 patients selected from 5735 using a propensity score. Instead, we form five propensity score strata and refine them into ten strata, obtaining excellent covariate balance while retaining all patients. An R package optrefine at CRAN implements the method. Supplementary materials are available online."
authors:
- admin
- Dylan S. Small
- Paul R. Rosenbaum
date: "2024-06-18T00:00:00Z"
doi: "10.1093/biomtc/ujae061"
featured: false
image:
projects: []
publication: 'Biometrics'
publication_short: ""
publication_types: ["2"]
publishDate: "2024-06-18T00:00:00Z"
slides: 
summary: 
tags:
title: Optimal Refinement of Strata to Balance Covariates
url_code: https://cran.r-project.org/web/packages/optrefine/index.html
url_dataset: ""
url_pdf: 
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---


