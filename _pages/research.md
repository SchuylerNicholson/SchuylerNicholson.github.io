---
layout: page
title: Research
permalink: /research/
---

<div class="figure-container-horizontal-full">
    <div class="figure">
         <img src="../images/output.png">
  </div>
</div>
<p>
Many systems in nature and problems in scientific computing are inherently high-dimensional. Traditional approaches to understanding canonical systems such as interacting many-particle processes in Chemistry and Biology rely on kinetic Monte-Carlo sampling. For rare events or observables that live at the tails of a distribution, these brute force sampling methods become untenable which has led to the creation of rare event formalism's such as forward flux sampling or transition path sampling. But fundamentally all these methods are still built on sampling individual realization of many-body processes, which comes with inherent draw backs. Quantum many-body systems suffer from the identical problem of high dimensionality. There, tensor networks have been hugely powerful at performing time evolution or finding ground states, not through sampling but by creating reduced models that give access to the entire many-body ensemble. Access to the probability of any microstate of the system yields a plethora of simultaneous system information that often must be found individually using sampling methods.
</p>
<p>
We show that by incorporating tensor networks with a classical second quantized method called the Doi-Peliti formalism, one can calculate not just expected values, but rare events at the ensemble level. In [S.B. Nicholson T.R. Gingrich PRX 2023](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.13.041006), we estimate the exponentially rare rate of transition between two wells of a reaction-diffusion process by time evolving a joint probability distribution that consists of up to approximately $10^{15}$ microstates. Future work will apply tensor network methods to other stochastic processes in Biology and Chemistry where molecular copy numbers are small, but the number of microstates is exponentially large.
</p>
