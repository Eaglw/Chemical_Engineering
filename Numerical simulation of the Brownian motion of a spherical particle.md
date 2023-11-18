---
dg-publish:
---
Stochastic differential equations (SDEs) are mathematical models that describe the evolution of a system over time in the presence of random fluctuations or noise. To model the stochastic terms in SDEs, we often use random number generators (RNGs) to generate random numbers that follow a certain distribution, such as a Gaussian distribution.

Linear Congruential RNGs (LCRNGs), also known as multiplicative or Lehmer RNGs, are a type of RNG that generates a sequence of pseudo-random numbers by iteratively applying a linear congruential function to an initial seed value. LCRNGs have been widely used in computer science and engineering applications due to their simplicity and speed.

Gaussian RNGs, on the other hand, generate random numbers that follow a Gaussian distribution, which is useful because many physical phenomena can be modeled using a gaussian distribution. Examples of Gaussian RNGs include the Box-Muller method and the Central Limit theorem method. The Box-Muller method generates one gaussian every uniform random number, while the Central Limit theorem method generates one gaussian number every twelve uniform numbers, but the Central Limit theorem is computationally lighter.

Wiener processes are a type of stochastic process that describes the evolution of a system with random fluctuations over time. 