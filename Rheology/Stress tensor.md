---
dg-publish: "false"
tags:
  - notdone
---
>[!definition]
>$\LARGE f=T\cdot A \mathbf{n}$

where:
- $f$ is the force that the surroundings exert on the element through the contact surface
- $T$ is the *stress tensor* in $\frac{N}{m^{2}}$
- $A$ is the area of the contact surface
- $n$ is the normal unit vector to the surface, pointing *outwards* of the element considered


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







The [[Rheology/Stress|stress]] generally depends on how the contact surface is oriented.   
The contact surface can be characterize by both its extent (the area A) and its orientation(the unit vector n normal to the surface).
• Indicating with f the force exchanged through the surface An, the relationship between   
these vectors is (provided the element is sufficiently small) a linear one. Hence:   
where T is the stress tensor (dimensions of force/square length).   
• To complete the definition we need to specify that, choosing to orient n, say, outwards from   
the element, then f is taken to be the force exerted by the surroundings upon the element.   
With such a choice, tractions come out as positive stresses while compressions are negative,   
which is the convention usually adopted in rheology. (Fluid dynamics uses the opposite   
one.)



