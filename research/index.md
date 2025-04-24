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

The SCAMs@bristol group is principally a *method-development* group. 
We are interested in developing simulation and analysis methods that reduce the information loss in this measurement process. 

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
<small>Thanks to Archie McLuckie for this fun ASCII-art!</small>

There are, currently, three main areas of research in the group: 

- [Linking simulation and neutron scattering](./neutrons/)
- [Understanding diffusion in chemical systems](./diffusion/)
- [Improving analysis of NMR measurements](./nmr/)
