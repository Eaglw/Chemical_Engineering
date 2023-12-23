---
tags:
  - notdone
---
If a fluid is not homogeneous but a mixture, where two or more miscible species flow, mix and eventually react, the time and space evolutino of the mixture composition is governed by a *species transport equation on each species*.
We can express this equation in 4 ways, writing them in terms of mass, moles, mass fraction or mole fraction. 

## Mass expression
$\LARGE \frac{\partial\rho_{i}}{\partial t}+\nabla \cdot (\rho_{i}\mathbf{\overline{u}})=-\nabla \cdot \mathbf{j_{i}}+r_{i}$
where:
- $\rho_{i}$ is the mass concentration of the i-th species, in $\frac{kg}{m^{3}}$
- $\overline{\mathbf{u}}=(\overline{u}_{x},\overline{u}_{y},\overline{u}_{z})$ is the mass average mixture velocity, in $\frac{m}{s}$
- $j_{i}=(j_{i,x},j_{i,y},j_{i,z})$ is the diffusive mass flux of the i-th species, in $\frac{kg}{m^{2}\cdot s}$
- $r_{i}$ is the rate of mass production/disappear of the i-th species, in $\frac{kg}{m^{3}\cdot s}$

and the mass average mixture velocity is defined as:
$\large \overline{u}=\frac{\sum^{N}_{i=1}\rho_{i}\mathbf{u}_{i}}{\sum^{N}_{i=1}\rho_{i}}=\frac{\sum^{N}_{i=1}\rho \mathbf{u}_{i}}{\rho}$
