---
dg-publish: true
Wiki: https://en.wikipedia.org/wiki/DLVO_theory
---
It's a theory that describes the force between charged surfaces interacting through a liquid medium. It combines the effect of the [[Soft Matter/van der Walls forces|van der Walls attraction]] and [[Soft Matter/Coulombic forces|electrostatic repulsion]], due to the so called [[Electric Double Layer|double layer of counterions]], by linearly summing them.

>[!important]
>$\LARGE w(H)= \frac{32n_{0}kT\pi d \Phi^{2}}{\kappa^{2}}exp\left(-\kappa H\right)-\frac{A_{121}d}{24H}$ 

where:
- $n_{0}$ is the bulk concentration
- d is the particle diameter
- $\Phi$ is the electric potential
- $A$ is the [[Soft Matter/Hamaker theory#^649420|Hamaker constant]] 
- $H$ is the distance between particles
- $\kappa^{-1}$ is the characteristic length of the [[Electric Double Layer|Electric Double Layer]]
![[Helper/media/DLVO example graph.png|350]]
### Assumption of the DLVO theory:
1. There is a balance between electrostatic repulsion(EDL) and van der walls attraction. 
2. *Additivity of the two contributions*, so only the linear effects are considered.
3. *Even distribution of particles and ions* in the dispersion. 
4. *Molecularly smooth and solid interfaces*, which are chemically inert except as a source for counterions. 
5. Intervening solvent has bulk properties up to the particle surface. 
6. van der Walls force is obtained by pair wise summation of London dispersion forces and calculated assuming a uniform structure and orientation of the intervening solvent.
### Effect of parameter on the DLVO potential energy
- w(H) depends on particle size $d$, so *electrostatic stabilization is more important the larger the particle is*.
- The repulsion is higher for *higher potential at surface*(so the EDL).
- The attraction is higher for *higher Hamaker constant* $A_{121}$ 
- The distance from the surface before the repulsion drops significantly $\kappa^{-1}$ is *larger if we lower the electrolytes concentration*.
For low electrolyte concentrations (small $\kappa$) the EDL repulsion is higher than the van der Walls attractive force, instead for high salt concentrations (high $\kappa$) the van der Walls attraction is dominant respect the EDL repulsion. 
![[Helper/media/DLVO dependance on ions and R.png]]

The van der Walls attraction is independent of the ion concentration, but the EDL repulsion is strongly dependent over it.

|Salt concentration| DLVO is dominated by|
|---|---|
| Low  |EDL repulsion|
| High  |van der Walls attraction|

Relation between the ion concentration $\sigma_{0}$ and the surface potential $\psi_{0}$ is accessible by solving the [[Poisson-Boltzmann equation|Poisson-Boltzmann equation]], that for planar surfaces gives this result:
$\Large \sigma_{0}=\epsilon_{0}\epsilon \kappa \psi_{0}$ 
### Consequences of the parameter dependance of the DLVO potential for colloidal stability



