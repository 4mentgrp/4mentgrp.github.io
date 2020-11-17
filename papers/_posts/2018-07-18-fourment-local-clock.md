---
layout: papers
title: "Local and relaxed clocks: the best of both worlds"
authors: ['Fourment M', 'Darling AE']
year: 2018
journal: PeerJ
doi: 10.7717/peerj.5140
preprint: 10.7287/peerj.preprints.26744v1
image: /images/papers/fourment-local-clock.png
github: https://github.com/4ment/flc
---

# Abstract

Time-resolved phylogenetic methods use information about the time of sample collection to estimate the rate of evolution. Originally, the models used to estimate evolutionary rates were quite simple, assuming that all lineages evolve at the same rate, an assumption commonly known as the molecular clock. Richer and more complex models have since been introduced to capture the phenomenon of substitution rate variation among lineages. Two well known model extensions are the local clock, wherein all lineages in a clade share a common substitution rate, and the uncorrelated relaxed clock, wherein the substitution rate on each lineage is independent from other lineages while being constrained to fit some parametric distribution. We introduce a further model extension, called the flexible local clock (FLC), which provides a flexible framework to combine relaxed clock models with local clock models. We evaluate the flexible local clock on simulated and real datasets and show that it provides substantially improved fit to an influenza dataset. An implementation of the model is available for download from [https://www.github.com/4ment/flc](https://www.github.com/4ment/flc).