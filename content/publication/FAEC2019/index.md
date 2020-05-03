---
abstract: "In the framework of Mixed Models, it is often of interest to provide an 
  estimate of the uncertainty in predictions for the random effects, customarily 
  defined by the Mean Squared Error of Prediction (MSEP). To address this 
  computation in the Generalized Linear Mixed Model (GLMM) context, a 
  non-parametric Bootstrap algorithm is proposed. 
  
  First, a newly developed Bootstrap scheme relying on random weighting of cluster 
  contributions to the joint likelihood function of the model and the Laplace 
  Approximation is used to create bootstrap replicates of the parameters. 
  
  Second, these replicates yield in turn bootstrap samples for the random effects 
  and for the responses. 
  
  Third, generating predictions of the random effects employing the 
  bootstrap samples of observations produces bootstrap replicates of the random 
  effects that, in conjunction with their respective bootstrap samples, are used in the 
  estimation of the MSEP. 
  
  To assess the validity of the proposed method, two simulation 
  studies are presented. The first one in the framework of Gaussian LMM, contrasts the 
  quality of the proposed approach with respect to: (i) analytical estimators of MSEP 
  based on second-order correct approximations, (ii) Conditional Variances obtained with 
  a Bayesian representation and (iii) other bootstrap schemes, on the grounds of 
  relative bias, relative efficiency and the coverage ratios of resulting prediction 
  intervals. The second simulation study serves the purpose of illustrating the 
  properties of our proposal in a Non-Gaussian GLMM setting, namely a Mixed Logit 
  Model, where the alternatives are scarce."

authors:
- admin
- Eva Cantoni
date: "2019-02"
# doi: "https://doi.org/10.1016/j.csda.2018.08.006"
featured: false
projects: []
publication: '*Computational Statistics & Data Analysis* (130)'
publication_short: ""
publication_types:
- "0"
publishDate: "2017-01-01T00:00:00Z"
summary: "A new way of computing the uncertainty in prediction of Random Effects with a novel Bootstrapping method."
tags:
- Source Themes
title: Bootstrap estimation of uncertainty in prediction for generalized linear mixed models
url_code: ""
url_dataset: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0167947318301890
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
