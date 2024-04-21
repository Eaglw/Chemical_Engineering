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
Considering an infinitesimal *tetrahedron* with 3 faces parallel to x,y,z and the last one described by $\underline{n}$.
--- start-multi-column: 
```column-settings  
number of columns: 2
border: disabled
```
![[Helper/media/Cauchy th..png]]

--- end-column ---

![[Helper/media/Cauchy th.-1.png]]

If the surface of the plane defined by $\underline{n}$ is $dA$, the projections on the axis will be:
$dA_{x}=dA\cdot \alpha x; dA_{y}=dA\cdot \alpha y$

---end-multi-column
--- start-multi-column: 
```column-settings  
number of columns: 2
border: disabled
```

![[Helper/media/Cauchy th.-2.png]]---end-column

$t_{nx}\cdot dA-\sigma_{xx}dA_{x}-\tau_{yx}dA_{y}-\tau_{zx}dA_{z}+F_{x}dV=0$
$dA\left( t_{nx}-\sigma_{xx}\alpha_{x}-\tau_{yx}\alpha y-\tau_{zx}\alpha z+\frac{dV}{dA} \right)$

---end-multi-column
