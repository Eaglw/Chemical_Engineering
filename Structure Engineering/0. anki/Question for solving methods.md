---
dg-publish: "false"
tags:
  - notdone
---
FILE TAGS: Solving

### what are the equation of equilibrium? 
[[Structure Engineering/3. Basic/Equations of equilibrium|Equations of equilibrium]] are a way to solve a structure, and tell us that the sum of all the forces and moments applied on a body must be zero, in order for the body to be at equilibrium.
$\LARGE\sum F_{x}=0;\sum F_{y}=0;\sum F_{z}=0$
$\LARGE\sum M_{x}=0;\sum M_{y}=0;\sum M_{z}=0$
3 in 2D and 6 in 3D.
ID: 1713347600894


### What is the convenction for positive moments?
counter-clockwise 
ID: 1713347600897


### what is the Principle of sectioning?
[[Structure Engineering/3. Basic/Principle of sectioning|Principle of sectioning]] tells us that if a structure is in equilibrium every part of the structure must be in equilibrium, so we can cut the structure in every part and apply the [[Structure Engineering/3. Basic/Equations of equilibrium|Equations of equilibrium]].
ID: 1713347600898


### are the internal characteristic of solicitations continouos functions?
yes unless there is some concentrated load applied in the section that we are considering.
ID: 1713347600899


### convenction for internal characteristic of solicitations?
![[Helper/media/Internal characteristics of solicitations.png]]
ID: 1713347600901

### expression of the indefinite equations of equilibrium? when can they be applied?
$\LARGE \frac{dT}{dx}=-q$ ; $\LARGE \frac{dM}{dx}=T$ also useful as $\LARGE dT=-qdx$ ; $\LARGE dM=Tdx$
[[Structure Engineering/4. Main concepts/Indefinite equations of equilibrium|Indefinite equations of equilibrium]]
only in tracs without any concentrated load
ID: 1713347796343

### why the internal characteristic of solicitations follow the indefinite equations of equilibrium?
In this case of no concentrated loads, the only case in which we can apply the [[Structure Engineering/4. Main concepts/Indefinite equations of equilibrium|Indefinite equations of equilibrium]], the [[Structure Engineering/3. Basic/Internal characteristics of solicitations|internal characteristics of solicitations]] are continuous functions. 
This can be seen in the limits of $dx \rightarrow 0$ in the second form of the equations, that gives $dT=dM=0$, so continuous functions.
ID: 1713434586667


###  how to apply the internal characteristic of solicitations

$\large T(x)= -\int q(x) \, dx+c_{1}$
$\large M(x)=\int T(x) \, dx+c_{2}$
where $c_{1}$ and $c_{2}$ can be derived applying the boundary conditions. 
$\large q=0 \rightarrow T=const \rightarrow linear \ M; \quad q=const\rightarrow linear\ T \rightarrow parabolic\ M$
ID: 1713434586698

### how to derive the indefinite equations of equilibrium?
![[Helper/media/Indefinite equations of equilibrium.png|300]]
Vertical equilibrium:
$T-T-dT-qdx=0 \rightarrow \frac{dT}{dx}=-q$
ID: 1713434586703


Rotational equilibrium:
$M+Tdx-qdx\cdot \frac{dx}{2}-M-dM=0 \rightarrow \frac{dM}{dx}=T$

The term $qdx\cdot \frac{dx}{2}$ has been canceled because it's an infinitesimal of higher order.

### Principle of Virtual Work
Necessary and sufficient condition for the position $S_{0}$ of the system S, having smooth bilateral supports, to be an equilibrium condition is that the virtual work $\delta L$ of forces is equal to zero for each virtual displacement d* from the position $S_{0}$
$\large \delta L=0$ for any virtual displacement
The virtual displacement d* is an infinitesimal displacement compatible with the supports.
ID: 1713434586705


### Purpose of the PLV?
The PLV is a useful tool for determining only one reaction of a support without having to solve the entire structure. This can be particularly advantageous in cases where solving the entire structure is too complex or time-consuming. But it can also be applied to each one of the supports in order to provide a more comprehensive analysis of the system.
ID: 1713434586708


### Theorem of collpsible mechanism?
Necessary and sufficient condition for the system to be 1 time unstable (l=1) is that for each couple of bodies i and j the absolute centers of rotation $C_{i}$ and $C_{j}$ and the relative center of rotation $C_{ij}$ are aligned
This theorem is applicable only for structure composed by at least 2 bodies
ID: 1713434586711
