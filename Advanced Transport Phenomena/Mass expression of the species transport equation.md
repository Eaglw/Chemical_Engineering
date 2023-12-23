---
dg-publish: 
tags:
  - notdone
---
$\LARGE \frac{\partial\rho_{i}}{\partial t}+\nabla \cdot (\rho_{i}\mathbf{\overline{u}})=-\nabla \cdot \mathbf{j_{i}}+r_{i}$
where:
- $\rho_{i}$ is the mass concentration of the i-th species, in $\frac{kg}{m^{3}}$
- $\overline{\mathbf{u}}=(\overline{u}_{x},\overline{u}_{y},\overline{u}_{z})$ is the mass average mixture velocity, in $\frac{m}{s}$
- $\mathbf{j}_{i}=(j_{i,x},j_{i,y},j_{i,z})$ is the diffusive mass flux of the i-th species, in $\frac{kg}{m^{2}\cdot s}$
- $r_{i}$ is the rate of mass production/disappear of the i-th species, in $\frac{kg}{m^{3}\cdot s}$

and the mass average mixture velocity is defined as:
$\large \overline{u}=\frac{\sum^{N}_{i=1}\rho_{i}\mathbf{u}_{i}}{\sum^{N}_{i=1}\rho_{i}}=\frac{\sum^{N}_{i=1}\rho_{i} \mathbf{u}_{i}}{\rho}$

Regarding only this expression, for a mixture with N components, the summation of the diffusion and reaction terms is zero, for the [[Basic concepts/Lavoisier principle|Lavoisier principle]].
For this reason, summing up the N species transport equations we get the [[Advanced Transport Phenomena/Mass balance equation|continuity equation]] for the overall system. 
Therefore, the mass average mixture velocity coincides with the velocity $\mathbf{u}$ of the continuity equation. 