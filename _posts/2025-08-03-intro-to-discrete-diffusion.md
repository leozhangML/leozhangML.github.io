---
layout: post
title:  an introduction to discrete diffusion and time-inhomogeneous CTMCs
date:   2025-08-03 16:40:16
description: or, why does no one talk about time-inhomogeneous Markov processes?
---

**See the notes [here](/assets/pdf/Introduction_to_Discrete_Diffusion.pdf)**

I've recently been working with discrete diffusion models and from digging into the literature around this topic, I've been annoyed at just how hard it is to find a good, unified presentation of the main theory behind discrete diffusion, namely time-inhomogeneous continuous-time Markov chains (CTMCs).

The issue arises from the fact that most mathematical presentations of CTMCs only work with the time-homogeneous case. Hence, finding an explanation of the time-dependent rate matrix, and how this gives rise to important results like the Kolmogorov forward and backward equations (and more generally, the theory of time-inhomogeneous Markov processes described by evolution systems) is a frustrating process. 

To help others skip this time-consuming journey, I've collected the main results, theory and references which I've found helpful to learn about time-inhomogeneous CTMCs in these slides which can be found [here](/assets/pdf/Introduction_to_Discrete_Diffusion.pdf). I also provide an introduction to the main papers on discrete diffusion models and discuss how they connect to the underlying theory. I hope these notes can be useful to the wider machine learning community.
