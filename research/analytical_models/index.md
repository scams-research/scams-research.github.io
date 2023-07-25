---
layout: default
title: Analytical models from physical models
---

One approach to introduce our prior knowledge into the analysis of some data is by building an analysis model that respects the physics or chemistry of the system being studied. 

This could be something as simple as ensuring that chemical bonding is respected in the modelling of neutron and x-ray reflectometry measurements on phospholipid monolayers. 
This simple approach enables inference about structure that is not possible without such constraints.[^1] 

Alternatively, a probabilistic description of the system under investigation, using the physics of a model system, can be developed. 
For example, by constructing a probabilistic model for freely diffusing particles it is possible to estimate diffusion properties from molecular dynamics simulation with nearly maximal efficiency, achieving from a single simulation understanding that would otherwise take hundreds.[^2]

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/bjmorgan/kinisi/blob/master/docs/source/_static/schematic_light.png?raw=true">
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/bjmorgan/kinisi/blob/master/docs/source/_static/schematic_dark.png?raw=true">
  <img alt="A schematic of the process to estimate the self-diffusion coefficient." src="https://github.com/bjmorgan/kinisi/blob/master/docs/source/_static/schematic_dark.png?raw=true">
</picture>
<center>
  <small>
    A schematic of the approach taken in <code>kinisi</code> to estimate the diffusion coefficeint using a model system.
    <br>
    <br>
  </small>
</center>

## References

[^1]: A. R. McCluskey, A. Sanchez-Fernandez, K. J. Edler, S. C. Parker, A. J. Jackson, R. A. Campbell, & T. Arnold. *Phys. Chem. Chem. Phys.*, **21**(11), 6133-6141, 2019. DOI: [10.1039/C9CP00203K](https://doi.org/10.1039/C9CP00203K).
[^2]: A. R. McCluskey, S. W. Coles, & B J. Morgan. 2023. Available on [arXiv:2305.18244](https://arxiv.org/abs/2305.18244).