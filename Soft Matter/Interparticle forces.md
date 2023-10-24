---
dg-publish: true
tags:
  - maintopic
---
There are various interparticle forces that become relevant in the field of [[Soft Matter/Soft matter|Soft matter]].
# Force scale respect to thermal energy
The fundamental unit of energy in the colloidal and molecular world is given by the [[Soft Matter/Thermal energy|thermal energy]], that is useful to scale all the other forces that can exist in a system.
### Comparison of the modulus of thermal energy, gravity and drag forces, with conseguences
| Particle size | Thermal agitation | Gravity | Drag |
|---| ---|---|---|
|eq.|$k_{b}T/a$|$\frac{4}{3}\pi a^{3} \Delta p$|$6\pi \mu a v$| 
|scaling on a|$\frac{1}{a}$|$a^{3}$|$a$|
|$1 \mu m$ |4fN|4fN|2fN|
|$10 \mu m$|0,4 fN|4000 fN|20 fN|

where $a$ is the characteristic dimension of the particle.
It's easy to understand that the thermal agitation is relevant only on very low scale. For example particles with $a<1 \mu m$ may not sediment because of thermal agitation, instead, larger particles feel gravity much more.
# Modelling approaches 
There are two approaches to understand the dispersion force attraction between particles and, although the *Lifshitz continuum description* is more reliable, a simpler one is the *molecular model* of the [[Soft Matter/Hamaker theory|Hamaker theory]]. He calculate the total attraction between particles summing the contributions of all pairs of particles.
The interactions can be often modelled as a [[Soft Matter/Pair potential|pair potential]], and can be *repulsive* like [[Soft Matter/Hard-core repulsion pair potential|hard-core repulsion]] and [[Soft Matter/Coulombic forces|electrostatic repulsion]], or *attractive*. The attractive ones can be of different natures:
### Which attraction forces can we find within atomic distances?
In the atomic scale we can fine chemical bonds and Lewis acid-based attractions.
### Which attraction forces can we find beyond bond-forming distances?
The most relevants are the [[Soft Matter/Coulombic forces|Coulombic forces]] and the [[Soft Matter/van der Walls forces|van der Walls forces]], with the London(dispersion) forces being the main ones between the van der Walls forces.
### Which is the effect of the presence of the *solvent* in the interparticle forces?
Interaction between molecules in a solvent medium can be very different from that of isolated molecules in free space or in a gas.
The presence of a suspending medium does more than simply reduce the interaction energy or force. The intrinsic dipole moment and polarizability of an isolated gas molecule may be different in the liquid state or when dissolved in a medium, in fact, a dissolved molecule can move only by displacing an equal volume of solvent from its path.

# Electrostatic interactions

# DLVO theory
It's a theory that describes the force between charged surfaces interacting through a liquid medium. It combines the effect of the [[Soft Matter/van der Walls forces|van der Walls attraction]] and [[Soft Matter/Coulombic forces|electrostatic repulsion]], due to the so called [[Electric Double Layer|double layer of counterions]], by linearly summing them.

$\LARGE w(H)= \frac{32n_{0}kT\pi d \Phi^{2}}{\kappa^{2}}exp\left(-\kappa H\right)-\frac{A_{121}d}{24H}$ 
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
2. *Additivity of the two contributions*.
3. Even distribution of particles and ions in the dispersion. 
4. Molecularly smooth and solid interfaces, which are chemically inert except as a source for counterions. 
5. Intervening solvent has bulk properties up to the particle surface. 
6. van der Walls force is obtained by pair wise summation of London dispersion forces and calculated assuming a uniform structure and orientation of the intervening solvent.
### Effect of parameter on the DLVO potential energy
- w(H) depends on particle size $d$, so *electrostatic stabilization is more important the larger the particle is*.
- 

# Entropic repulsion