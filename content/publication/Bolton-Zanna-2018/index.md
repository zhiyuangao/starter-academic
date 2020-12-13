---
title: "Regional and Temporal Variability of Lateral Mixing in the North Atlantic"
authors:
- "T. Bolton"
- R. Abernathey
- L. Zanna
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-01-05T00:00:00Z"
doi: "10.1175/JPO-D-19-0042.1"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*J. of Phys. Oceanogr.*, 49(10), 2601-2614."
publication_short: ""

abstract: 

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: files/Bolton-et-al-2019.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
# url_custom = [{name = "Online Article", url = "https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2018MS001472"},{name = "Code", url = "https://github.com/TomBolton/DeepEddy"}]


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
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
slides: example

# {{% alert note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /alert %}}
# 
# {{% alert note %}}
# Click the *Slides* button above to demo Academic's Markdown slides feature.
# {{% /alert %}}
# 
# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
---
Oceanographic observations are limited by sampling rates, while ocean models are limited by finite resolution and high viscosity and diffusion coefficients. Therefore both data from observations and ocean models lack information at small- and fast-scales.
Methods are needed to either extract information, extrapolate, or up-scale existing oceanographic datasets, to account for or represent unresolved physical processes.
Here we use machine learning to leverage observations and model data by predicting unresolved turbulent processes and sub-surface flow fields.
As a proof-of-concept, we train convolutional neural networks on degraded-data from a high-resolution quasi-geostrophic ocean model.
We demonstrate that convolutional neural networks successfully replicate the spatio-temporal variability of the sub-grid eddy momentum forcing, are capable of generalising to a range of dynamical behaviours, and can be forced to respect global momentum conservation.
The training data of our convolutional neural networks can be sub-sampled to 10-20\% of the original size without a significant decreasein accuracy.

We also show that the sub-surface flow field can be predicted using only information at the surface (e.g., using only satellite altimetry data).
Our study indicates that data-driven approaches can be exploited to predict both sub-grid and large-scale processes, while respecting physical principles, even when data is limited to a particular region or external forcing. Our in-depth study presents evidence for the successful design of ocean eddy parameterisations for implementation in coarse-resolution climate models.