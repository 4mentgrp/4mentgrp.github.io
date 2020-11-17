---
layout: papers
title: "Evaluating probabilistic programming and fast variational Bayesian inference in phylogenetics"
authors: ['Fourment M', 'Darling AE']
year: 2019
journal: PeerJ
doi: 10.7717/peerj.8272
preprint: 10.1101/702944
github: https://github.com/4ment/phylostan
---

# Abstract

Recent advances in statistical machine learning techniques have led to the creation of probabilistic programming frameworks. These frameworks enable probabilistic models to be rapidly prototyped and fit to data using scalable approximation methods such as variational inference. In this work, we explore the use of the Stan language for probabilistic programming in application to phylogenetic models. We show that many commonly used phylogenetic models including the general time reversible (GTR) substitution model, rate heterogeneity among sites, and a range of coalescent models can be implemented using a probabilistic programming language. The posterior probability distributions obtained via the black box variational inference engine in Stan were compared to those obtained with reference implementations of Markov chain Monte Carlo (MCMC) for phylogenetic inference. We find that black box variational inference in Stan is less accurate than MCMC methods for phylogenetic models, but requires far less compute time. Finally, we evaluate a custom implementation of mean-field variational inference on the Jukes-Cantor substitution model and show that a specialized implementation of variational inference can be two orders of magnitude faster and more accurate than a general purpose probabilistic implementation.