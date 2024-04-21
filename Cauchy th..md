---
dg-publish: "false"
tags:
  - notdone
---
>[!definition]
>By knowing the stress state for 3 different attitudes in P, it's possibile to determine the stress on any other attitude in P.

## Mathematical expression
The component of the *stress vector* in point P are:
$\underline{t}_{n}=(t_{nx},t_{ny},t_{nz})=\underline{\underline{T}}\cdot\underline{n}$
where:
$t_{nx}=\sigma_{xx}dx+\tau_{yx}dy+\tau_{zx}dz$
$t_{ny}=\tau_{xy}dx+\sigma_{yy}dy+\tau_{zy}dz$
$t_{nz}=\tau_{xz}dx+\tau_{yz}dy+\sigma_{zz}dz$

## Demonstration

![[Helper/media/Cauchy th..png|200]]
Considering an infinitesimal *tetrahedron* with 3 faces parallel to x,y,z and the last one described by $\underline{n}$.
![[Helper/media/Cauchy th.-1.png|200]]
If the surface of the plane defined by $\underline{n}$ is $dA$, the projections on the axis will be:
$dA_{x}=dA\cdot \alpha x; dA_{y}=dA\cdot \alpha y$
![[Helper/media/Cauchy th.-2.png|200]]
Applying the [[Structure Engineering/3. Basic/Equations of equilibrium|equations of equilibrium]] on x axis:
$t_{nx}\cdot dA-\sigma_{xx}dA_{x}-\tau_{yx}dA_{y}-\tau_{zx}dA_{z}+F_{x}dV=0$
Dividing by $dA$:
$dA\left( t_{nx}-\sigma_{xx}\alpha_{x}-\tau_{yx}\alpha y-\tau_{zx}\alpha z+F_{x}\frac{dV}{dA} \right)=0$
$\frac{dV}{dA}$ is an infinitesima of higher order respect to the other, so:
$t_{nx}=\sigma_{xx}dx+\tau_{yx}dy+\tau_{zx}dz$



