---
layout: papers
title: "Systematic exploration of the high likelihood set of phylogenetic tree topologies"
authors: ['Whidden C', 'Claywell BC', 'Fisher T', 'Magee AF', 'Fourment M', 'Matsen IV FA']
year: 2019
journal: Syst Biol
doi: 10.1093/sysbio/syz047
preprint: https://arxiv.org/abs/1811.11007
github: https://github.com/matsengrp/pt
---

# Abstract

Bayesian Markov chain Monte Carlo explores tree space slowly, in part because it frequently returns to the same tree topology. An alternative strategy would be to explore tree space systematically, and never return to the same topology. In this paper, we present an efficient parallelized method to map out the high likelihood set of phylogenetic tree topologies via systematic search, which we show to be a good approximation of the high posterior set of tree topologies. Here 'likelihood' of a topology refers to the tree likelihood for the corresponding tree with optimized branch lengths. We call this method 'phylogenetic topographer' (PT). The PT strategy is very simple: starting in a number of local topology maxima (obtained by hill-climbing from random starting points), explore out using local topology rearrangements, only continuing through topologies that are better than than some likelihood threshold below the best observed topology. We show that the normalized topology likelihoods are a useful proxy for the Bayesian posterior probability of those topologies. By using a non-blocking hash table keyed on unique representations of tree topologies, we avoid visiting topologies more than once across all concurrent threads exploring tree space. We demonstrate that PT can be used directly to approximate a Bayesian consensus tree topology. When combined with an accurate means of evaluating per-topology marginal likelihoods, PT gives an alternative procedure for obtaining Bayesian posterior distributions on phylogenetic tree topologies.