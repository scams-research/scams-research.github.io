---
layout: post
title: Harry's First Paper
date: 2025-01-27
author: Andrew
---

In September of 2024, Harry Richardson joined the SCAMs@bristol group as the first PhD student, of which Andrew would be the lead supervisor. 
Harry has gotten off to a great start, settling into the group and getting a handle on all the new areas of science he needs to learn about. 

Early in his project, Harry started speaking to Josh Dunn about a problem Josh had been trying to resolve for a few months now. 
That of calculating the centre of mass of a group of particles in a periodic system. 
It might seem trivial, but where the group spans the periodic cell, the naïve approach would produce the wrong position. 
A paper from [Bai and Breen](https://doi.org/10.1080/2151237X.2008.10129266) proposed a nice solution to this, involving projecting the coordinates onto a circle and computing the centre of mass on the circle before back projecting. 
However, this approach came with a numerical error that Josh (and Andrew!) couldn't quite wrap our heads around. 

Harry's solution to this was to use the slightly wrong estimate from the Bai and Breen method to ensure that the particles were all on the same periodic image and then calculate the naïve centre of mass before restoring things to the original space, and this worked perfectly. 
Since then, we have been trying to explain the source of the numerical error, and it turned out to involve some interesting Fourier series maths. 
This problem and Harry and Josh's solution have now been written up and put on [arXiv](https://arxiv.org/abs/2501.14578) for all to see, and we hope to submit it to a journal this week. 

So congratulations, Harry and Josh; this is Harry's first paper with the SCAMs@bristol group, and based on the trajectory of one paper in four months -- I don't think it will be his last. 

[See the paper on arXiv here](https://arxiv.org/abs/2501.14578). 
