---
layout: default
title: Research
---

The goal of any experiment or simulation is to gain an understanding of some physical observable. 
However, the process of making a measurement is a [noisy channel](https://en.wikipedia.org/wiki/Noisy-channel_coding_theorem), i.e. there is information loss in the measurement process. 
This means that our experimental or simulation data will not contain all of the information that is present in the original observable. 
The goal of any data analysis is then to try and reconstruct the physical observable (to decode the signal, in information parlance), leading to a fuzzy, noisy estimate. 

<picture>
  <source srcset="/assets/img/noisy_channel.png" media="(prefers-color-scheme: dark)">
  <img src="/assets/img/noisy_channel_light.png">
</picture>
<center>
  <small>
    The measurement-analysis workflow showing the information loss in the noisy channel.
    <br>
    <br>
  </small>
</center>

There are two ways to improve our estimates less uncertain; improving our measurement or improving our analysis. 
The former may be achieved experimentally with improved instrumentation or *in-silico* with higher levels of theory. 
However, we believe that significant improvements can be made to the measurement-analysis workflow by improving how we analyse our data. 

The research aim of the {{ site.title }} group is to develop powerful analysis methods for data from chemical measurements, by including what we already know about the world &mdash; some may call this *physics-informed* modelling. 
We believe that the next generation of data analysis, using machine learning and quantum computing, will be built on an understanding of the fundamental chemistry and physics of the systems of interest. 

```
             ,----------------,              ,---------,
        ,-----------------------,          ,"        ,"|
      ,"                      ,"|        ,"        ,"  |
     +-----------------------+  |      ,"        ,"    |
     |  .-----------------.  |  |     +---------+      |
     |  |                 |  |  |     | -==----'|      |
     |  |  I LOVE         |  |  |     |         |      |
     |  |  Molecular      |  |  |/----|`---=    |      |
     |  |  Dynamics       |  |  |   ,/|==== ooo |      ;
     |  |                 |  |  |  // |(((( [33]|    ,"
     |  `-----------------'  |," .;'| |((((     |  ,"
     +-----------------------+  ;;  | |         |,"     
        /_)______________(_/  //'   | +---------+
   ___________________________/___  `,
  /  oooooooooooooooo  .o.  oooo /,   \,"-----------
 / ==ooooooooooooooo==.o.  ooo= //   ,`\--{)B     ,"
/_==__==========__==_ooo__ooo=_/'   /___________,"

```

## Projects

- [Analytical models from physical models](./analytical_models/)
- [Harnessing our prior knowledge and combining measurements](./prior/)
- [Bayesian model selection](./model_selection/)
