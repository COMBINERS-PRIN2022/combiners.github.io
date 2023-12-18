---
title: "Bayesian Estimation of Single and Multiple Graphs"
authors:
- Ni
- Stingo
- Baladandayuthapani

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
#date: "2022-09-01T00:00:00Z"
#doi: "10.1201/9781003089018"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Machine Learning Research, 23*(1-29)"
#publication_short: ""

abstract: We introduce Bayesian Gaussian graphical models with covariates (GGMx), a class of multivariate Gaussian distributions with covariate-dependent sparse precision matrix. We propose a general construction of a functional mapping from the covariate space to the cone of sparse positive definite matrices, which encompasses many existing graphical models for heterogeneous settings. Our methodology is based on a novel mixture prior for precision matrices with a non-local component that admits attractive theoretical and empirical prop- erties. The flexible formulation of GGMx allows both the strength and the sparsity pattern of the precision matrix (hence the graph structure) change with the covariates. Posterior inference is carried out with a carefully designed Markov chain Monte Carlo algorithm, which ensures the positive definiteness of sparse precision matrices at any given covariates’ values. Extensive simulations and a case study in cancer genomics demonstrate the utility of the proposed model.

# Summary. An optional shortened abstract.
# summary: ...

tags:
- paper

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.jmlr.org/papers/volume23/21-0102/21-0102.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://www.jmlr.org/papers/v23/21-0102.html
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides:
---
