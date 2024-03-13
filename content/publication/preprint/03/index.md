---
title: "Exploration of the search space of Gaussian graphical models for paired data"
authors:
- Roverato
- Nguyen
date: "2023-03-09T00:00:00Z"
doi: "10.48550/arXiv.2303.05561"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: We consider the problem of learning a Gaussian graphical model in the case where the observations come from two dependent groups sharing the same variables. We focus on a family of coloured Gaussian graphical models specifically suited for the paired data problem. Commonly, graphical models are ordered by the submodel relationship so that the search space is a lattice, called the model inclusion lattice. We introduce a novel order between models, named the twin order. We show that, embedded with this order, the model space is a lattice that, unlike the model inclusion lattice, is distributive. Furthermore, we provide the relevant rules for the computation of the neighbours of a model. The latter are more efficient than the same operations in the model inclusion lattice, and are then exploited to achieve a more efficient exploration of the search space. These results can be applied to improve the efficiency of both greedy and Bayesian model search procedures. Here we implement a stepwise backward elimination procedure and evaluate its performance by means of simulations. Finally, the procedure is applied to learn a brain network from fMRI data where the two groups correspond to the left and right hemispheres, respectively.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
 # url: http://example.org
url_pdf: https://arxiv.org/pdf/2303.05561
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://arxiv.org/abs/2303.05561
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

