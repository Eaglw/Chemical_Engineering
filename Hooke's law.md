---
dg-publish: "false"
tags:
  - notdone
---
>[!definition]
>$\LARGE \sigma=E \cdot \epsilon$

![[Helper/media/Hooke's law.png]]

where:
- $\sigma$ is the [[Rheology/Stress|Stress]], defined as $\frac{F}{A}$ in Pa
- E is the *elastic modulus*
- $\epsilon$ is the elongation
This law is applicable only in case of [[Rheology/Elasticity|linear elastic]] materials, where stress is linear with deformation, and the elastic modulus is the slope of the graph.

At the elongation in the direction of the force, a corresponding contraction occurs in the other directions, and the magnitude of this contraction can be expressed as a function of the elongation through a constant value $\nu$, known as *Poisson's ratio*: if $\epsilon_{x}=\frac{\sigma_{x}}{E}$, then $\epsilon_{y}=-\nu\frac{\sigma_{x}}{E}$.
Common values for the Poisson's ratio $\nu$ are:
- 0,3 for [[Steel|steel]]
- 0,25 for many materials
- In general $0\leq \nu \geq 0.5$.
The assumption of only one *elastic modulus* and *Poisson's ratio* is valid only for *homogeneous*, *isotropic* materials, otherwise we should consider different values for different directions.

## Elasticity in shear
Also a shear stress can cause an elastic response, a