---
tags:
  - notdone
---
>[!important]
>$\LARGE \rho c_{P} \frac{\partial T}{\partial t} + \rho c_{P} \textbf{u} \cdot \nabla T = - \nabla \cdot \textbf{q} + \boldsymbol{\sigma} \nabla \textbf{u} - \frac{\partial ln \rho}{\partial ln T} \bigg|_{p} \left(\frac{\partial p}{\partial t}+\textbf{u} \cdot \nabla p \right) + S$

where:
1. The first term is *energy accumulation* term and $c_{p}$ is *specific heat at constant pressure* in $\frac{J}{kg \cdot K}$
2. Second term is the *convective term* and T is *fluid temperature* in K
3. The third is the *conductive term*, where $\textbf{q}$ is the *conductive heat flux* in $\frac{J}{m^{2} s}$
4. The fourth is the *viscous dissipation* term 
5. The fifth is the *variation of energy by compression* term
6. The sixth is the *energy generation* term and S is the *specific generation of thermal energy* in $\frac{J}{m^{3}s}$

The energy balance is a scalar equation. 

---
## Derivation of special cases for multicomponent systems

1. The conductive term can be modelled through the [[Basic concepts/Fourier constitutive equation|Fourier constitutive equation]]; 
2. If the fluid is a *multicomponent mixture* the conductive heat flux becomes:  $\LARGE \textbf{q} = -k \nabla T + \sum_{i=1}^{N} h_{i} \boldsymbol{j_{i}}$  where: 
	-  $h_{i}$ is the specific enthalpy of the i-th species in $\frac{J}{Kg}$ 
	-  $\boldsymbol{j_{i}}$ is the diffusive mass flux of the i-th species in $\frac{Kg}{m^{2}s}$ 
3. For a *newtonian fluid* we can use the deviatoric part of it's [[Basic concepts/Costitutive eq. for Newtornian fluids|constitutive equation]] in the viscous dissipation term:
	$\LARGE \boldsymbol{\sigma} : \nabla \textbf{u} = \frac{1}{2} \eta \sum_{j} \sum_{i} \left( \frac{\partial u_{i}}{\partial x_{j}} + \frac{\partial u_{j}}{\partial x_{i}} \right)^{2} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2} = \eta \Phi_{v} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2}$
	where:
	$\Phi_{v}= \frac{1}{2}\sum_{j} \sum_{i} \left( \frac{\partial u_{i}}{\partial x_{j}} + \frac{\partial u_{j}}{\partial x_{i}} \right)^{2}$  	
	so we have:
	$\LARGE \rho c_{P} \left(  \frac{\partial T}{\partial t} +  \textbf{u} \cdot \nabla T \right) =\nabla \cdot \left(k \nabla T \right) + \eta \Phi_{v} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2} - \frac{\partial ln \rho}{\partial ln T} \bigg|_{p} \left(\frac{\partial p}{\partial t}+\textbf{u} \cdot \nabla p \right) + S$
4. For [[Ideal gas|ideal gasses]] (that are newtonian) $\kappa = 0$ and $\frac{\partial ln \rho}{\partial ln T} \bigg|_{p} = -1$:
	$\LARGE \rho c_{P} \left(  \frac{\partial T}{\partial t} +  \textbf{u} \cdot \nabla T \right) =\nabla \cdot \left(k \nabla T \right) + \eta \Phi_{v} - \frac{2}{3} \eta \left( \nabla \cdot \textbf{u} \right)^{2} + \left(\frac{\partial p}{\partial t}+\textbf{u} \cdot \nabla p \right) + S$ 
5.  For *incompressible* fluids $\nabla \cdot \textbf{u} = 0$ and $\frac{\partial ln \rho}{\partial ln T} \bigg|_{p} =0$:
	$\LARGE \rho c_{P} \left(  \frac{\partial T}{\partial t} +  \textbf{u} \cdot \nabla T \right) =\nabla \cdot \left(k \nabla T \right) + \eta \Phi_{v} + S$

6. For *solids*, $\textbf{u}=0, \frac{\partial ln \rho}{\partial ln T} \bigg|_{p} =0$:
	$\LARGE \rho c_{P} \frac{\partial T}{\partial t} =\nabla \cdot \left(k \nabla T \right) + S$ 


