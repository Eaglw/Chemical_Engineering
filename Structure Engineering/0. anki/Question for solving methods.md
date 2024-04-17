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

###  how to apply the internal characteristic of solicitations
