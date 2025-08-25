
# Variational inference for approximate objective priors using neural networks

Authors :

- Nils Baillie
  - Université Paris-Saclay, CEA, Service d'Études Mécaniques et Thermique
  - CMAP, CNRS, École polytechnique, Institut Polytechnique de Paris
- Antoine Van Biesbroeck
  - Université Paris-Saclay, CEA, Service d'Études Mécaniques et Thermique
  - CMAP, CNRS, École polytechnique, Institut Polytechnique de Paris
- Clément Gauchy
  - Université Paris-Saclay, CEA, Service de Génie Logiciel pour la Simulation



## Abstract

In Bayesian statistics, the choice of the prior can have an important influence on the posterior and the parameter estimation, especially when few data samples are available. To limit the added subjectivity from a priori information, one can use the framework of objective priors, more particularly, we focus on reference priors in this work. However, computing such priors is a difficult task in general. Hence, we consider cases where the reference prior simplifies to the Jeffreys prior. We develop in this paper a flexible algorithm based on variational inference which computes approximations of priors from a set of parametric distributions using neural networks. We also show that our algorithm can retrieve modified Jeffreys priors when constraints are specified in the optimization problem to ensure the solution is proper. We propose a simple method to recover a relevant approximation of the parametric posterior distribution using Markov Chain Monte Carlo (MCMC) methods even if the density function of the parametric prior is not known in general. Numerical experiments on several statistical models of increasing complexity are presented. We show the usefulness of this approach by recovering the target distribution. The performance of the algorithm is evaluated on both prior and posterior distributions, jointly using variational inference and MCMC sampling.



## Guidelines

The main notebook is obtained by default by loading every necessary data file without doing the computations, some options in the beginning of the code can be changed if one wants to re-train the networks or re-sample the posterior distributions. These files are mainly there to generate the plots rapidly, they can be found in the folder "plots_data".

For the probit model, the computations were made on many different RNG seeds, the output files and the corresponding scripts can be found in the folders "data_probit/Multiseed_VARP" and "data_probit/Multiseed_AJ".

NB : We use the 2.2.0 version of the torch package.
