---
layout: papers
title: A surrogate function for one-dimensional phylogenetic likelihoods
authors: ['Claywell BC',  'Dinh V', 'Fourment M',  'McCoy CO', 'Matsen FA']
year: 2017
journal: "Mol Biol Evol"
doi: 10.1093/molbev/msx253
preprint: https://arxiv.org/abs/1706.00659
image: /images/papers/claywell-lcfit.png
github: https://github.com/matsengrp/lcfit
---

# Abstract

Phylogenetics has seen a steady increase in data set size and substitution model complexity, which require increasing amounts of computational power to compute likelihoods. This motivates strategies to approximate the likelihood functions for branch length optimization and Bayesian sampling. In this paper, we develop an approximation to the one-dimensional likelihood function as parametrized by a single branch length. Our method uses a four-parameter surrogate function abstracted from the simplest phylogenetic likelihood function, the binary symmetric model. We show that it offers a surrogate that can be fit over a variety of branch lengths, that it is applicable to a wide variety of models and trees, and that it can be used effectively as a proposal mechanism for Bayesian sampling. The method is implemented as a stand-alone open-source C library for calling from phylogenetics algorithms; it has proven essential for good performance of our online phylogenetic algorithm sts.