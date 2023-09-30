---
tags:
  - notdone
---
>[!important]
>$\textbf{T} = -p \textbf{I} + 2 \eta \textbf{D} + \left(\kappa - \frac{2}{3} \eta \right) ( \nabla \cdot \textbf{u} ) \textbf{I}$

where:
1. p is the pressure in $\frac{kg}{m s^{2}}$ 
2. $\textbf{I}$ is the identity tensor
3. $\eta$ is the fluid dynamic viscosity in $\frac{kg}{m s}$
4. $\textbf{D}$ is the [[Rate of deformation tensor|rate of deformation tensor]], the symmetric part of the [[Velocity gradient tensor|velocity gradient tensor]] in $\frac{1}{s}$
5. $\kappa$ is the fluid volume viscosity

This formula is valid for a [[Newtonian fluid|newtonian fluid]] and relates the [[Stress tensor|stress tensor]] components to other unknowns already present in the mass and momentum balance, in order to close the system.
In a more compact form, we can express the constitutive equation as:
$\LARGE \textbf{T} = -p \textbf{I} + \boldsymbol{\sigma}$ 
- The pressure term is called *isotropic* and is always present, even under quiescent conditions, his value is the *hydrostatic pressure*.
- The term $\boldsymbol{\sigma} = 2 \eta \textbf{D} + \left(\kappa - \frac{2}{3} \eta \right) ( \nabla \cdot \textbf{u} ) \textbf{I}$ is called *deviatoric* and is present only when the fluid flows. 
The flow mentioned is a relative flow between the layers of the fluid, because the absolute value of velocity is irrelevant for the stress evaluation. 

