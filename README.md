# Variational inference for approximate objective priors using neural networks
Nils Baillie, Antoine Van Biesbroeck, Clément Gauchy
2025-12-01

### Citation

Nils Baillie, Antoine Van Biesbroeck and Clément Gauchy (December 2025). Variational inference for approximate objective priors using neural networks. Computo.
<https://doi.org/10.57750/76fh-t442>

### Badges

[![build and
publish](https://github.com/computorg/published-202512-baillie-varp/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202512-baillie-varp/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202512-baillie-varp/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202512-baillie-varp)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202512-baillie-varp)
[![DOI:10.57750/76fh-t442](https://img.shields.io/badge/DOI-10.57750%2F76fh--t442-034E79.svg)](https://doi.org/10.57750/76fh-t442)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- Nils Baillie (Université Paris-Saclay, CEA, Service d’Études Mécaniques et Thermiques, 91191 Gif-sur-Yvette, France, CMAP, CNRS, École polytechnique, Institut Polytechnique de Paris, 91120 Palaiseau, France)
- Antoine Van Biesbroeck (Université Paris-Saclay, CEA, Service d’Études Mécaniques et Thermiques, 91191 Gif-sur-Yvette, France, CMAP, CNRS, École polytechnique, Institut Polytechnique de Paris, 91120 Palaiseau, France, (Now at Centre Borelli, ENS Paris-Saclay, Université Paris-Saclay, 91190 Gif-sur-Yvette, France))
- Clément Gauchy (Université Paris-Saclay, CEA, Service de Génie Logiciel pour la Simulation, 91191 Gif-sur-Yvette, France)

### Abstract

In Bayesian statistics, the choice of the prior can have an important
influence on the posterior and the parameter estimation, especially when
few data samples are available. To limit the added subjectivity from a
priori information, one can use the framework of objective priors, more
particularly, we focus on reference priors in this work. However,
computing such priors is a difficult task in general. Hence, we consider
cases where the reference prior simplifies to the Jeffreys prior. We
develop in this paper a flexible algorithm based on variational
inference which computes approximations of priors from a set of
parametric distributions using neural networks. We also show that our
algorithm can retrieve modified Jeffreys priors when constraints are
specified in the optimization problem to ensure the solution is proper.
We propose a simple method to recover a relevant approximation of the
parametric posterior distribution using Markov Chain Monte Carlo (MCMC)
methods even if the density function of the parametric prior is not
known in general. Numerical experiments on several statistical models of
increasing complexity are presented. We show the usefulness of this
approach by recovering the target distribution. The performance of the
algorithm is evaluated on both prior and posterior distributions,
jointly using variational inference and MCMC sampling.
