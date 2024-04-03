---
dg-publish: "false"
tags:
  - notdone
---
>[!definition]
>$\LARGE \frac{dT}{dx}=-q$ ; $\LARGE \frac{dM}{dx}=T$ also useful as $\LARGE dT=-qdx$ ; $\LARGE dM=Tdx$

These are only applicable for continuous tracts, so without any concentr

## Application


$T(x)= -\int q(x) \, dx+c_{1}$
$M(x)=\int T(x) \, dx+c_{2}$


## Derivation
Referring to an infinitesimal slice of a beam, we can always assume that the distributed load is constant. We also assume that there are no concentrated loads applied in the infinitesimal slice. In this condition, we can safely assume that also the variation of the [[Structure Engineering/3. Basic/Internal characteristics of solicitations|internal characteristics of solicitations]] is infinitesimal.
--- start-multi-column: ExampleRegion1  
```column-settings  
number of columns: 2  
largest column: right  
```

![[Helper/media/Indefinite equations of equilibrium.png|300]]

--- end-column ---

Vertical equilibrium:
$T-T-dT-qdx=0 \rightarrow \frac{dT}{dx}=-q$

Rotational equilibrium:
$M+Tdx-qdx\cdot \frac{dx}{2}-M-dM=0 \rightarrow \frac{dM}{dx}=T$

--- end-multi-column
The term $qdx\cdot \frac{dx}{2}$ has been canceled because it's an infinitesimal of higher order 