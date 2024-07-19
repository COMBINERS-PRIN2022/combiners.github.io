---
title: Poster session of the workshop on Complex Graphical Models for Biological Network Science
authors: [Stingo, Roverato, Consonni, Augugliaro]
#summary: This workshop focuses on the development of novel principled statistical tools for the analysis of complex networks under non-standard experimental setups.
#abstract: TBA
address:
  city: PADUA
  country: Italy
  postcode: "35121"
  region: IT
  street: Via Cesare Battisti, 241
all_day: false
date: "2024-09-04T09:00:00Z"
date_end: ""
location: Department of Statistical Sciences, University of Padova
event: Workshop on Complex Graphical Models for Biological Network Science
#event_url: https://example.org
featured: false
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right
#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#projects:
#- internal-project
publishDate: "2023-12-18T00:00:00Z"
#slides: example
tags: [Workshop]
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

# Poster Session
---

## Authors: Luca Aiello, Sudipto Banerjee
## Title: Detecting spatial health disparities using disease maps
### Abstract: Epidemiologists commonly use regional aggregates of health outcomes to map mortality or incidence rates and identify geographic disparities. However, to detect health disparities across regions, it is necessary to identify “difference boundaries” that separate neighboring regions with significantly different spatial effects. This can be particularly challenging when dealing with multiple outcomes for each region and accounting for dependence among diseases and across regions. We address detection of multivariate difference boundaries for correlated diseases by formulating the problem in terms of Bayesian pairwise multiple comparisons by extending it through the introduction of adjacency modeling and disease graph dependencies. Specifically, we seek the posterior probabilities of neighboring spatial effects being different. To accomplish this, we adopt a class of multivariate areally referenced Dirichlet process models that accommodate spatial and inter-disease dependence by endowing the spatial random effects with a discrete probability law. Our method is evaluated through simulation studies and applied to detect difference boundaries for multiple cancers using data from the Surveillance, Epidemiology, and End Results Program of the National Cancer Institute.
---

## Authors: Erika Banzato, Davide Risso, Monica Chiogna, Vera Djordjilovic
## Title: Two-stage differential network analysis
### Abstract: In this work, we propose a novel two-stage methodology for differential network analysis in two-sample problems. The focus is on estimating and localizing differences in the networks of two conditions. The first stage involves node-level screening to test the equality of node-conditional distributions under two conditions. Each node-conditional distribution is modeled using generalized linear models, and the equality of distributions is tested via likelihood ratio tests. In this stage, the overall false discovery rate is controlled across all nodes. The second stage delves deeper into the nodes where the initial hypothesis of equality was rejected, testing each individual parameter within these node-conditional distributions to identify and localize specific differences. This method is suitable for situations without prior knowledge about the network structure in the two conditions and can also include a preliminary step to estimate the networks to increase the power of the procedure. It can also incorporate prior information about the network structure if available.
---

## Authors: Francesco Barile, Simón Lunagómez, Bernardo Nipoti
## Title: Bayesian nonparametric modeling of heterogeneous populations of networks
### Abstract: The increasing availability of multiple network data has been calling for the development of statistical models for heterogeneous populations of networks. A convenient framework to model multiple network data makes use of distance metrics that measure the similarity between networks. In this context, we propose a novel Bayesian nonparametric model allowing for the identification of clusters of networks characterized by similar patterns in the connectivity of nodes. Our construction relies on the definition of a location-scale Dirichlet process mixture of centered Erdős–Rényi kernels, with components conveniently parametrized by a unique mode, or network representative, and a univariate measure of dispersion around the mode. An efficient Markov chain Monte Carlo scheme is proposed to carry out posterior inference and conveniently cluster the multiple network data. The number of clusters in the population is not set a priori but inferred from the data. We investigate the performance of our model through extensive simulation studies and the analysis of a popular human brain network data set by confirming improved achievements compared to state-of-the-art models. Finally, we present a strategy to extend the application of the proposed model to datasets characterized by a large number of nodes. We illustrate this approach through the analysis of the human brain network data set with a more granular brain parcellation and the FAO food trade market data set.
---

## Authors: Laura Ferrini, Federico Castelletti
## Title: Bayesian nonparametric mixtures of categorical networks for heterogeneous causal inference
### Abstract: Estimating causal effects between variables is crucial in various scientific domains. As an example, in medical science one aims at identifying the effect of some medical treatment on the progression of a disease. Being able to answer this question at subject-specific level rather than at population level would guarantee a more reliable decision-making process for personalized therapies. Causal inference based on graphical models typically relies on the assumption that observations are homogeneous, meaning that they come from the same Structural Causal Model (SCM). Accordingly, for a given treatment, the same causal effect on a response of interest is attributed to all subjects. We relax this assumption by allowing for the presence of latent subgroups of observations that are associated to different causal graphical structures and different model parameters. We consider categorical data and assume that the graph is directed and acyclic, which represents a classical requirement in the framework of causal inference based on graphical models. We address the issue of heterogeneity in the population by developing a Dirichlet Process mixture of categorical Directed Acyclic Graphs (DAGs). This allows to cluster individuals into homogeneous sub-groups, and to estimate treatment effects at subject-specific level. We develop both a joint and marginal sampler for posterior inference. While the former allows to approximate the posterior distribution of DAGs, DAG parameters and clustering, the latter directly targets a marginal posterior over the DAGs and clustering partition, thus improving MCMC efficiency. We compare our methodology with alternative state-of-the-art model-based clustering techniques that ignore possible dependencies between variables. Our results show that cluster identification improves when the multivariate model accounts for such dependence structure. Moreover, such improvement is more evident when marginal distributions are similar across clusters, a scenario in which methods neglecting dependencies between variables fail to recover the clustering structure. Finally, we consider patients affected by breast cancer, treated with oncologic drugs that may cause cardiotoxicity as a side effect. Importantly, the development of such side effect can vary among patients, thus requiring models accounting for heterogeneity.
---

## Authors: Thi Kim Hue Nguyen, Monica Chiogna, Davide Risso
## Title: Unguided structure learning of DAGs for count data
### Abstract: In various fields such as single-cell sequencing, spatial incidence analysis, and sports science, there has been a noticeable increase in the prevalence of large-scale multivariate count data. Researchers have acknowledged the importance of capturing directional dependence relationships among the variables of interest, leading to the consideration of graphs as modelling tools. Here, we present a new algorithm, called learnDAG, for learning the structure of directed acyclic graphs (DAGs). In particular, the proposed algorithm tackled the problem of learning DAGs from observational data in three steps: 1) preliminary neighbourhood selection using methods for learning undirected graphs; 2) orienting edges using a log-likelihood score (or a BIC score); and 3) pruning the resulting DAG using variable selection algorithms such as Lasso, or significance tests. We experimentally compare learnDAG to several popular competitors in recovering the true structure of the graphs in situations where relatively moderate sample sizes are available. Furthermore, to make our algorithm is stronger, a validation of the algorithm is presented through the analysis of real datasets.
---

## Authors: Elena Stenghellini, Marco Doretti, Chris Caroni, Konstantina Gourgoura, Taiki Tezuka
## Title: Causal inference and selection bias
### Abstract: The poster contains some recent developments in causal inference and selection bias. In particular, it shows how some recent results in mediation analysis (Doretti et al., 2024) can also be used to correct for the bias on causal effects induced by informative selection of units into the analysis, thereby enlarging existing results (Mathur and Shpitser, 2024). Some real-data anaysis on Post/Long Covid will also be presented.
