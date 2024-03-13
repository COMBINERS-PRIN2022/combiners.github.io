---
title: "On the application of Gaussian graphical models to paired data problems"
authors:
- Ranciati
- Roverato
date: "2023-07-26T00:00:00Z"
doi: "10.48550/arXiv.230714160.09863"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: Gaussian graphical models are nowadays commonly applied to the comparison of groups sharing the same variables, by jointy learning their independence structures. We consider the case where there are exactly two dependent groups and the association structure is represented by a family of coloured Gaussian graphical models suited to deal with paired data problems. To learn the two dependent graphs, together with their across-graph association structure, we implement a fused graphical lasso penalty. We carry out a comprehensive analysis of this approach, with special attention to the role played by some relevant submodel classes. In this way, we provide a broad set of tools for the application of Gaussian graphical models to paired data problems. These include results useful for the specification of penalty values in order to obtain a path of lasso solutions and an ADMM algorithm that solves the fused graphical lasso optimization problem. Finally, we present an application of our method to cancer genomics where it is of interest to compare cancer cells with a control sample from histologically normal tissues adjacent to the tumor. All the methods described in this article are implemented in the 𝚁 package 𝚙𝚍𝚐𝚕𝚊𝚜𝚜𝚘 availabe at [this https URL](https://github.com/savranciati/pdglasso).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
 # url: http://example.org
url_pdf: https://arxiv.org/pdf/2307.14160.pdf
url_code: https://github.com/savranciati/pdglasso
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: https://arxiv.org/abs/2307.14160
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

