---
dg-publish: 
tags:
  - notdone
  - revision
---
>[!definition]
>$\large \mathbf{T\cdot n}=-p_{out}\mathbf{n}$

where:
1. $\mathbf{T}$ is the [[Stress tensor|stress tensor]].
2. $\mathbf{n}$ is the unit normal vector pointing outward. 

Physically, this condition represents an outlet in an ambient at pressure $p_{out}$   
With this condition on a boundary of the domain, the velocity profile is not univocally defined and depends on the specific problem.
The quantity $\mathbf{T\cdot n}$ is the «traction», which is the force exerted by the fluid   
on the boundary.

Esempio per vedere che in uscita abbiamo non fully developed flow

## Alternative BC that takes into account only the normal outflow
>[!definition]
>$\large \mathbf{n^{T}\cdot T\cdot n}=-f_{n}$
>$\large \mathbf{u\cdot t}=0$

where:
1. $\mathbf{n^{T}\cdot T\cdot n}$ is the component of the traction *normal* to the boundary
2. $f_{n}$ is a parameter that represent the normal force (for unit area) on the outflow boundary.
3. $\mathbf{t}$ is the unit vector *tangetial* to the boundary.

The second equation states that the tangential component of the   
velocity is zero, i.e., the fluid exits normal to the outflow boundary.