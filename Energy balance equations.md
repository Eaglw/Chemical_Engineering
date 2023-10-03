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
The conductive term can be modelled through the [[Basic concepts/Fourier constitutive equation|Fourier constitutive equation]] 

If the fluid is a *multicomponent mixture* the conductive heat flux becomes:
$\LARGE \textbf{q} = -k \nabla T + \sum_{i=1}^{N} h_{i} \boldsymbol{j_{i}}$ 
where:
1. $h_{i}$ is the specific enthalpy of the i-th species in $\frac{J}{Kg}$ 
2. $\boldsymbol{j_{i}}$ is the diffusive mass flux of the i-th species in $\frac{Kg}{m^{2}s}$ 

For a *newtonian fluid* we can use the deviatoric part of it's [[Basic concepts/Costitutive eq. for Newtornian fluids|constitutive equation]] in the viscous dissipation term:

$\LARGE \boldsymbol{\sigma} : \nabla \textbf{u} = \frac{1}{2} \eta \sum_{j} \sum_{i} \left( \frac{\partial u_{i}}{\partial x_{j}} + \frac{\partial u_{j}}{\partial x_{i}} \right)^{2} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2} = \eta \Phi_{v} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2}$ where:
$\Phi_{v}= \frac{1}{2}\sum_{j} \sum_{i} \left( \frac{\partial u_{i}}{\partial x_{j}} + \frac{\partial u_{j}}{\partial x_{i}} \right)^{2}$  

so we have:

$\LARGE \rho c_{P} \left(  \frac{\partial T}{\partial t} +  \textbf{u} \cdot \nabla T \right) =\nabla \cdot \left(k \nabla T \right) + \eta \Phi_{v} + \left(  \kappa -\frac{2}{3} \eta  \right)\left( \nabla \cdot \textbf{u} \right)^{2} - \frac{\partial ln \rho}{\partial ln T} \bigg|_{p} \left(\frac{\partial p}{\partial t}+\textbf{u} \cdot \nabla p \right) + S$







