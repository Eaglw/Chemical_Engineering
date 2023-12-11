---
dg-publish: 
tags:
  - notdone
---
The solid domain that separates two fluids can have a very thin thickness d compared to the fluid domain. The accurate solution of the heat balance equation in the solid domain would require, then, a mesh with very small elements. For this reason, it could be useful (in terms of computational efficiency) to not solve the energy balance in the solid domain and approximate the heat transport as an [[Numerical Simulation/2. Boundary contiditions/BC - heat flux|heat flux]], with $q_{BC}=\frac{k}{\delta}(T_{1}-T_{2})$ where $\delta$ is the thickness of the layer with k as thermal conductivity.
It's the approximation of the 1D conductive transport through a sheet.