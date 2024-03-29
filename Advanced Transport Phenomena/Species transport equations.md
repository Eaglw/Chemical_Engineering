---
tags: 
dg-publish: "true"
---
If a fluid is not homogeneous but a mixture, where two or more miscible species flow, mix and eventually react, the time and space evolutino of the mixture composition is governed by a *species transport equation on each species*.
# Mathematical expression
For a mixture of N components, the number of independent species transport equations is N-1.
We can express these equations in 4 physically equivalent ways, writing them in terms of mass, moles, mass fraction or mole fraction:
- [[Advanced Transport Phenomena/Mass expression of the species transport equation|Mass expression]]
- [[Advanced Transport Phenomena/Mass fraction expression of the species transport equations|Mass fraction expression]]
- [[Advanced Transport Phenomena/Moles expression of the species transport equations|Moles expression]]
- [[Advanced Transport Phenomena/Molar fraction expression of the species transport equations|Molar fraction expression]]

Each of them has the following terms:
1. The first is the *accumulation term*
2. The second is the *convective term*
3. The third is the *diffusion term*
4. The forth is the *generation/disappearence term due to chemical reaction*
5. The fifth, present only in the molar fraction expression, is a corrective term to take into account the moles variations during the reactions. 
# Modeling of the diffusion term
Through the [[Basic concepts/Fick's law|Fick's law]], for a binary mixture, we can express the diffusive fluxes of species A and B as:
- In term of *mass diffusive fluxes*: $\mathbf{j}_{A}=-\rho D_{AB}\nabla \omega_{A}$ and $\mathbf{j}_{B}=-\rho D_{BA}\nabla \omega_{B}$
- In term of *molar diffusive fluxes*: $\mathbf{j}^{*}_{A}=-c D_{AB}\nabla x_{A}$ and $\mathbf{j}^{*}_{B}=-c D_{BA}\nabla x_{B}$
where $D_{AB}=D_{BA}$ are the *diffusion coefficient of the binary mixtures*, in $\frac{m^{2}}{s}$.
In the case of mixtures made by more than two components, the expressions for the diffusive fluxes are more complex. 

# Final expression for species A in a binary A-B mixture
In mass terms:
$\LARGE \rho(\frac{\partial\omega_{A}}{\partial t}+\mathbf{\overline{u}} \cdot \nabla \omega_{A})=\nabla \cdot(\rho D_{AB}\nabla \omega_{A})+r_{A}$
In molar terms:
$\LARGE c\left( \frac{\partial x_{A}}{\partial t}+ \mathbf{\overline{u^{*}}} \cdot \nabla x_{A} \right)=\nabla \cdot(c D_{AB}\nabla x_{A})+(1-x_{A})R_{A}-x_{A}R_{B}$

## Dilute liquid mixture, with constant temperature and pressure
The product $\rho D_{AB}$ is constant, so the balance on species A in mass term simplifies as:
$\LARGE \rho(\frac{\partial\omega_{A}}{\partial t}+\mathbf{\overline{u}} \cdot \nabla \omega_{A})=\rho D_{AB}\nabla^{2} \omega_{A}+r_{A}$
## Low density gaseous mixture, with constant temperature and pressure
The product $cD_{AB}$ is constant, so the balance on species A in molar terms simplifies as:
$\LARGE c\left( \frac{\partial x_{A}}{\partial t}+ \mathbf{\overline{u^{*}}} \cdot \nabla x_{A} \right)=c D_{AB}\nabla^{2} x_{A}+(1-x_{A})R_{A}-x_{A}R_{B}$
