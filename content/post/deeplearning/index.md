---
title: Press for our 2019 Ocean Warming Paper in PNAS 
subtitle: Some links (press and radio) discussing our work
summary: Some links (press and radio) discussing our work
authors:
- admin
tags: []
categories: []
date: "2020-08-20T00:00:00Z"
featured: false
draft: false
math: true
diagram: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Our new work with Tom Bolton on physics-aware & interpretable ML to improve ocean models is out in [GRL](http://tinyurl.com/y3chr7jr). 

Our new approach to the parameterization/closure problem: learning differential equations of missing physics in coarse-res ocean models from data. We use a machine learning (ML) method that relies on sparse Bayesian inference / relevance vector machine to learn ocean eddy parameterizations of momentum, buoyancy, and energy. We compare it to a ML parameterization which uses convolutional neural nets with conservation-law embedded in the architecture. Each approach has pros and cons (interpretability, generalization, numerical stability) in our proof-of-concept. Many aspects need to be improved but we are moving one step closer towards blending physics and machine learning for climate modeling.
