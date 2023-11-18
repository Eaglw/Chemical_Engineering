---
dg-publish:
---
To write stochastic differential equations in matlab we need random number generators (RNG) to model the stochastic terms.
Examples can be the Linear Congruential RNG (special case the multiplicative or Lehmer RNG) or Gaussians RNGs, that are particulary useful because the random numbers generated are a gaussian distribution.
Examples of Gaussian RNGs are the Box-Muller method and the Central Limit theorem method.
Box muller generates one gaussian every uniform random number, but is computationally heavier. 
Central limit theorem instead generates one gaussian number every twelve uniform numbers, but it is computationally a lot lighter. 

what are the wiener processes?

️️To write stochastic differential equations in MATLAB, we require random number generators (RNGs) to model the stochastic terms. Examples of RNGs include the Linear Congruential RNG (a special case of the multiplicative or Lehmer RNG), and Gaussian RNGs, which are particularly useful because they generate random numbers that follow a Gaussian distribution.

Examples of Gaussian RNGs include the Box-Muller method and the Central Limit theorem method. The Box-Muller method generates one Gaussian number every uniform random number, but is computationally heavier. On the other hand, the Central Limit theorem method generates one Gaussian number every twelve uniform numbers, which is computationally lighter.

What are Wiener processes?️