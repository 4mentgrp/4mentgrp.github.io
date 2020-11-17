---
layout: papers
title: "19 dubious ways to compute the marginal likelihood of a phylogenetic tree topology"
authors: ['Fourment M', 'Magee A', 'Whidden C', 'Bilge A', 'Matsen IV FA', 'Minin VN']
year: 2019
journal: Syst Biol
doi: 10.1093/sysbio/syz046
preprint: https://arxiv.org/abs/1811.11804
github: https://github.com/4ment/marginal-experiments
image: /images/papers/fourment-dubious.png
---

# Abstract

The marginal likelihood of a model is a key quantity for assessing the evidence provided by the data in support of a model.
The marginal likelihood is the normalizing constant for the posterior density, obtained by integrating the product of the likelihood and the prior with respect to model parameters.
Thus, the computational burden of computing the marginal likelihood scales with the dimension of the parameter space.
In phylogenetics, where we work with tree topologies that are high-dimensional models, standard approaches to computing marginal likelihoods are very slow.
Here we study methods to quickly compute the marginal likelihood of a single fixed tree topology.
We benchmark the speed and accuracy of 19 different methods to compute the marginal likelihood of phylogenetic topologies on a suite of real datasets.
These methods include several new ones that we develop explicitly to solve this problem, as well as existing algorithms that we apply to phylogenetic models for the first time.
Altogether, our results show that the accuracy of these methods varies widely, and that accuracy does not necessarily correlate with computational burden.
Our newly developed methods are orders of magnitude faster than standard approaches, and in some cases, their accuracy rivals the best established estimators.