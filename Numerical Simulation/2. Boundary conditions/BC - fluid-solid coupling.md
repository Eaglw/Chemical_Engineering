---
dg-publish: 
tags:
  - notdone
  - revision
---
>[!definition]
>$\large T_{f}=T_{s}$
>$\large -\mathbf{n}_{f}\cdot(-k_{f}\nabla T_{f})-\mathbf{n}_{s}\cdot(-k_{s}\nabla T_{s})=0$ 

One or more fluid-solid interfaces (i.e., boundaries shared by a fluid and a solid) are common in problems that simultaneously involve heat transfer in fluids and solids.

The conditions typically prescribed at the interface are: 
- equal fluid and solid temperatures at the interface 
- continuity of the normal fluxes across the interface 

Notice that the sign of the heat fluxes in the previous equation is equal since the normals at the interface $\mathbf{n}_{f}$ ed $\mathbf{n}_{s}$ are opposite in sign.

## Generation/adsorption of heat inside the interface
A more general condition for fluid-solid coupling: 
>[!definition]
>$\large T_{f}=T_{s}$
>$\large -\mathbf{n}_{f}\cdot(-k_{f}\nabla T_{f})-\mathbf{n}_{s}\cdot(-k_{s}\nabla T_{s})=q_{BC}$ 


where $q_{BC}$ is a known heat flux.
This condition is used when there is a generation/absorption of heat $q_{BC}$ inside the interface (for instance, an electric serpentine along the interface that produces heat by Joule effect). Hence, the heat flux normal to the interface is discontinuous, even if the 
fluid and solid temperature is equal.
These conditions can be straightforwardly extended to the  *solid-solid 
case*.