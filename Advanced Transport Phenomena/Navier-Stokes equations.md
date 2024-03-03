---
tags: 
dg-publish: "true"
---
>[!important]
>$\LARGE \nabla \cdot \textbf{u}=0$
>$\LARGE \rho \big( \frac{\partial \textbf{u}}{\partial t} +\textbf{u} \cdot \nabla \textbf{u} \big) = - \nabla p + \eta \nabla^{2} \textbf{u} +\textbf{F}$ 

## Derivation
Substituting the [[Advanced Transport Phenomena/Costitutive eq. for Newtornian fluids#^ccb40f|costitutive eq. for Newtornian incompressible fluids]] in the [[Advanced Transport Phenomena/Momentum balance equations|momentum balance equations]] we get:
$\LARGE \rho \big( \frac{\partial \textbf{u}}{\partial t} +\textbf{u} \cdot \nabla \textbf{u} \big) = \nabla \cdot \big( -p \textbf{I} + 2 \eta \textbf{D} \big) +\textbf{F}$ 
And adding there isothermal conditions hypotesis we can consider the dynamic viscosity $\eta$ constant:
$\LARGE \rho \big( \frac{\partial \textbf{u}}{\partial t} +\textbf{u} \cdot \nabla \textbf{u} \big) = - \nabla p + \eta \nabla^{2} \textbf{u} +\textbf{F}$ 
where $\nabla^{2}$ is the [[Laplacian operator|Laplacian operator]].

## Field of application
This system is valid for incompressible (constant $\rho$), newtonian fluids, in isothermal conditions (constant $\eta$). 
These are 4 partial differential equations in 4 unknowns:
1. Pressure
2. 3 components of velocity vector
As all differential equations they need initial and [[Basic concepts/Boundary conditions|boundary conditions]] in order to be solved. 
