---
title: "Bayesian Inference of Multiple Ising Models for Heterogeneous Data"
authors:
- Pacheco
date: "2023-03-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Bayes Comp 2023*
publication_short: In *Bayes Comp 2023*

abstract: Multiple Ising models can be used to model the heterogeneity induced in a set of binary variables by external factors. These factors may influence the joint dependence relationships represented by a set of graphs across different groups. This talk presents the inference for this class of models and proposes a Bayesian methodology based on a Markov Random Field prior for the multiple graph setting. Such prior enables the borrowing of strength across the different groups to encourage common edges when supported by the data. Sparse inducing spike-and-slab priors are employed on the parameters that measure graph similarities to learn which subgroups have a shared graph structure. Two Bayesian approaches are developed for the inference of multiple Ising models with special focus on model selection, (i) a Fully Bayesian method for low-dimensional graphs based on conjugate priors specified with respect to the exact likelihood, and (ii) an Approximate Bayesian method based on a quasi- likelihood approach for high-dimensional graphs where the normalization constant required in the exact method is computationally intractable. The performance of the proposed methods are studied and compared with competing approaches through an extensive simulation study. Both inferential strategies are employed for the analysis of data resulting from two public opinion studies in US. The first one analyzes the confidence in political institutions in different groups divided by the time users spent on web pages. The second one studies the opinion on public spending in diverse inter-generational groups.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: 
url_pdf: https://img1.wsimg.com/blobby/go/4163f096-f0ee-419e-9105-9c6a8a61a862/downloads/BoA_20230313.pdf?ver=1678959827017
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://bayescomp2023.com/home
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**EcoSta2023**](http://www.cmstatistics.org/EcoSta2023/index.php)'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
