---
dg-publish: "true"
---
>[!important]
>$\LARGE \rho \frac{\partial \textbf{u}}{\partial t} + \rho \textbf{u} \cdot \nabla \textbf{u} = \nabla \cdot \textbf{T}+\textbf{F}$

where:
1. The first term is the momentum accumulation
2. The second term is the convective term, where $\nabla$ is the [[Gradient|gradient]] operator, in $\frac{1}{m}$
3. The third is the surface force term and *T* is the [[Stress tensor|stress tensor]], in $\frac{kg}{m\cdot s^{2}}$ 
4. The fourth term is external force term, where *F* is a generic force, like gravity, in $\frac{kg}{m^{2}\cdot s^{2}}$ 
## Steady-state conditions
Neglecting the accumulation term we have:
$\LARGE \rho \textbf{u} \cdot \nabla \textbf{u} = \nabla \cdot \textbf{T}+\textbf{F}$

To be solved we must provide a [[Basic concepts/Constitutive equations|constitutive equation]] for the stress tensor. The most common case is a [[Newtonian fluid|newtonian fluid]], leading to the [[Advanced Transport Phenomena/Navier-Stokes equations|Navier-Stokes equations]].