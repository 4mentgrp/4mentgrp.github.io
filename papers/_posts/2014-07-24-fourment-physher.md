---
layout: papers
title: Novel non-parametric models to estimate evolutionary rates and divergence times from heterochronous sequence data
authors: ['Fourment M', 'Holmes EC']
year: 2014
journal: BMC Evol Biol
journalref: 14:163
doi: 10.1186/s12862-014-0163-6
github: https://github.com/4ment/physher
---

# Abstract

**Background.** Early methods for estimating divergence times from gene sequence data relied on the assumption of a molecular clock. More sophisticated methods were created to model rate variation and used auto-correlation of rates, local clocks, or the so called “uncorrelated relaxed clock” where substitution rates are assumed to be drawn from a parametric distribution. In the case of Bayesian inference methods the impact of the prior on branching times is not clearly understood, and if the amount of data is limited the posterior could be strongly influenced by the prior.

**Results.** We develop a maximum likelihood method – Physher – that uses local or discrete clocks to estimate evolutionary rates and divergence times from heterochronous sequence data. Using two empirical data sets we show that our discrete clock estimates are similar to those obtained by other methods, and that Physher outperformed some methods in the estimation of the root age of an influenza virus data set. A simulation analysis suggests that Physher can outperform a Bayesian method when the real topology contains two long branches below the root node, even when evolution is strongly clock-like.

**Conclusions.** These results suggest it is advisable to use a variety of methods to estimate evolutionary rates and divergence times from heterochronous sequence data. Physher and the associated data sets used here are available online at [http://code.google.com/p/physher/](https://www.github.com/4ment/physher).