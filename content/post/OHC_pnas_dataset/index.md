---
title: Updated Datasets of ocean warming reconstruction
subtitle: Ocean Heat Content and Thermosteric Sea Level 
summary: Ocean Heat Content and Thermosteric Sea Level 
authors:
- admin
tags: []
categories: []
date: "2019-03-15T00:00:00Z"
lastMod: "2019-03-15T00:00:00Z"
featured: false
draft: false

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

The original data from our PNAS paper can be dowloaded [here](https://www.dropbox.com/s/wx3fj4w61b8yyud/OHC_GF_global.nc?dl=0)

We are continuously working on updating the datasets fairly regularly (thanks to many comments and sugg\
estions over the recent weeks). For the most recent update (March 15th, v0) which include:

- extending back to 1870 (rather than 1871),

- adding year 2018

- using Sea Surface Temperatures from NOAA Extended Reconstruction SSTsV4, COBE (in addition to HadISSTv1 and realisations from HadISST v2)

- thermal expansion coefficients calculated using annual-mean climatology for 2005-2012 of WOA2013.

The datasets for the upper 300 m, upper 700 m, upper 2000 m, below 2000 m, and full depth (with errors defined as one-SD and derived from perturbing the Green's Functions and from the use of different SSTs) are here:

- [Ocean Heat Content (v0) 1870-2018](https://www.dropbox.com/s/wa5u5bc5y5mym88/OHC_GF_1870_2018.nc?dl=0)

- [Thermosteric Sea Level (v0) 1870-2018](https://www.dropbox.com/s/4b1piqgjdekj1gc/ThSL_GF_1870_2018.nc?dl=0)

For further details regarding the method, please consult our [manuscript](https://laurezanna.github.io/files/Zanna-et-al-2019.pdf) and [supplementary material](https://laurezanna.github.io/files/Zanna-et-al-SI-2019.pdf).

