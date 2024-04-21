---
dg-publish: "false"
tags:
  - notdone
Resources: https://ocw.mit.edu/courses/2-25-advanced-fluid-mechanics-fall-2013/dd8d998533249b8496b2cc0a241dd478_MIT2_25F13_sym_of_str_ten.pdf
---
>[!definition]
>$\LARGE f=T\cdot A \mathbf{n}$

where:
- $f$ is the force that the surroundings exert on the element through the contact surface
- $T$ is the *stress tensor* in $\frac{N}{m^{2}}$
- $A$ is the area of the contact surface
- $n$ is the normal unit vector to the surface, pointing *outwards* of the element considered
With this choice of normal vector, *tractions come out as positive [[Rheology/Stress|stresses]] while compressions are negative*, which is the convention usually adopted in rheology. (Fluid dynamics uses the opposite one.)

## Components of the stress tensor
--- start-multi-column: 
```column-settings  
number of columns: 2  
largest column: right 
border: disabled
```
![[Helper/media/Stress tensor.png|350]]

--- end-column ---

$\Large ||T||=\begin{bmatrix}T_{xx}&T_{xy}&T_{xz}\\T_{yx}&T_{yy}&T_{yz}\\T_{zx}&T_{zy}&T_{zz}\end{bmatrix}=\begin{bmatrix}\sigma_{xx}&\tau_{xy}&\tau_{xz} \\ \tau_{yx}&\sigma_{yy}&\tau_{yz}\\ \tau_{zx}&\tau_{zy}&\sigma_{zz}\end{bmatrix}$

--- end-multi-column
The first index refers to the axis normal to the plane of the stress, indentifying it. The second index refers to the direction of the stress itself. 
$\tau_{xy}$ is positive if directed in a positive y direction, on the face having positive x as a normal vector.
The stress tensor is *symmetric*, $\tau_{ij}=\tau_{ji}$, so it's completely described with 6 values.
This can be demonstrated with the rotational equilibrium around each axis(see [resources](https://ocw.mit.edu/courses/2-25-advanced-fluid-mechanics-fall-2013/dd8d998533249b8496b2cc0a241dd478_MIT2_25F13_sym_of_str_ten.pdf)). 



