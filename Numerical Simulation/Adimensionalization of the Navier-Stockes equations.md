---
dg-publish: "true"
tags:
  - notdone
---
>[!definition]
>$\large \nabla \cdot \mathbf{u}$
>$\large \frac{\partial\mathbf{u}}{\partial t}+\mathbf{u}\cdot \nabla \mathbf{u}=-\nabla p+\frac{1}{Re}\nabla^{2}\mathbf{u}$
All the parameter above lack the star of the dimentionless form

The main advantage is that the only parameter in these equation in the [[Dimentionless numbers/Reynolds number|Reynolds number]].
In order to make the [[Advanced Transport Phenomena/Navier-Stokes equations|Navier-Stokes equations]] in a pipe dimentionless we need to introduce some dimentionless parameters:
1. Spatial coordinate: $\mathbf{x}^{*}=\frac{\mathbf{x}}{D}$, where D=2R is the cylinder diameter
2. Velocity: $\mathbf{u}^{*}=\frac{\mathbf{u}}{U}$
3. Time: $t^{*}=t\frac{U}{D}$
4. Mathematical operators: $\nabla^{*}=D\nabla$, $\nabla^{*2}=D^{2} \nabla^{2}$
## Pressure adimensionalization
Pressure deserves more attention, because it can be make dimensionless in 2 ways:
1. Using the density: $p^{*}=\frac{1}{\rho U^{2}}p$
2. Using the viscosity:

They are both valid and are more or less useful depending on the specific problem.