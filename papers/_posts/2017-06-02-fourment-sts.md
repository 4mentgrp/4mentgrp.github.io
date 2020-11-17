---
layout: papers
title: Effective Online Bayesian Phylogenetics Via Sequential Monte Carlo With Guided Proposals
authors: ['Fourment M', 'Claywell BC', 'Dinh V', 'McCoy C', 'Matsen FA', 'Darling AE']
year: 2017
journal: Syst Biol
doi: 10.1093/sysbio/syx090
preprint: 10.1101/145219
image: /images/papers/fourment-sts.png
github: https://github.com/OnlinePhylo/sts
---

# Abstract

Modern infectious disease outbreak surveillance produces continuous streams of sequence data which require phylogenetic analysis as data arrives. Current software packages for Bayesian phylogenetic inference are unable to quickly incorporate new sequences as they become available, making them less useful for dynamically unfolding evolutionary stories. This limitation can be addressed by applying a class of Bayesian statistical inference algorithms called sequential Monte Carlo (SMC) to conduct online inference, wherein new data can be continuously incorporated to update the estimate of the posterior probability distribution. In this paper we describe and evaluate several different online phylogenetic sequential Monte Carlo (OPSMC) algorithms. We show that proposing new phylogenies with a density similar to the Bayesian prior suffers from poor performance, and we develop ‘guided’ proposals that better match the proposal density to the posterior. Furthermore, we show that the simplest guided proposals can exhibit pathological behavior in some situations, leading to poor results, and that the situation can be resolved by heating the proposal density. The results demonstrate that relative to the widely-used MCMC-based algorithm implemented in MrBayes, the total time required to compute a series of phylogenetic posteriors as sequences arrive can be significantly reduced by the use of OPSMC, without incurring a significant loss in accuracy.