---
layout: default
title: Improving accuracy in chemical simulation
---

Chemical simulation is an important tool in the physical sciences. 
Offering an atomistic, or even electronic, insight into the relevant systems of interest. 
However, chemical simulation is computationally expensive and with growing economic and environmental costs associated with compute, it is important the chemical simulation that is run is analysed in such a way that the maximum information if obtained from the minimum simulation. 
To address this problem, we look to improve the analysis methods that are applied to simulation data. 
This has included the development of a statistically efficient Bayesian regression framework for diffusion coefficient estimation,[^1] which has been implemented in the open-source Python package [kinisi](https://kinisi.readthedocs.io).

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

Recently, we have address the problem of estimating the centre of mass of a molecule in a periodically repeating cell. 
Specifically, we have highlighted the need to compute the intrinsic centre of mass in the *circular* periodic cell, rather than the extrinsic centre of mass that is popularly used[^2]. 

<picture>
  <img alt="A wizard suggesting that the dark art of the intrisic mean is necessary for computing centre of mass" src="/assets/img/wizard.jpg">
</picture>
<center>
  <small>
    Some aspects of improving accuracy feel like the dark arts. 
    <br>
    <br>
  </small>
</center>

## Relevant Publications

[^1]: A. R. McCluskey, S. W. Coles, & B. J. Morgan. *J. Chem. Theory Comput.*, **21**(1), 79, 2025. DOI: [10.1088/2632-2153/ab94c4](https://doi.org/10.1088/2632-2153/ab94c4).
[^2]: H. Richardson, J. Dunn, & A. R. McCluskey. [*arXiv*:2501.14578](https://arxiv.org/abs/2501.14578), 2025. 
