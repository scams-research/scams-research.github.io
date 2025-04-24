---
layout: default
title: Improving accuracy in chemical simulation
---

Chemical simulation is an essential tool in the physical sciences. 
Offering an atomistic, or even electronic, insight into the relevant systems of interest. 
However, chemical simulation is computationally expensive. With growing economic and environmental costs associated with compute, it is necessary that the chemical simulation that is run is analysed so that the maximum information is obtained from the minimum simulation. 

To address this problem, we look to improve the analysis methods applied to simulation data. 
This work has included the development of a statistically efficient Bayesian regression framework for diffusion coefficient estimation,[^1] which we have implemented in the open-source Python package [kinisi](https://kinisi.readthedocs.io).
Recently, we have addressed the problem of estimating the centre of mass of a molecule in a periodically repeating cell. 
Specifically, we have highlighted the need to compute the intrinsic centre of mass in the *circular* periodic cell, rather than the extrinsic centre of mass that is popularly used[^2]. 

<picture>
  <img alt="A wizard suggesting that the dark art of the intrinsic mean is necessary for computing centre of mass" src="/assets/img/wizard.jpg">
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
