---
dg-publish: true
---
Colloidal particles have a well-defined size and shape, and solid bodies cannot interpenetrate. That is because of the [[Pauli's exclusion principle|Pauli's exclusion principle]]. It's defined as:
$\LARGE w(r)= + \left( \frac{\sigma}{r}   \right)^{n}$with $\LARGE n \to \infty$   
Given its mathematical nature it's problematic to use for the presence of the infinity in calculations, especially for computational ones. 
### What can we use instead of the hard-core repulsion, given it's complex mathematical nature?
The *Soft repulsion pair potential* takes into account it's problematic nature. It'a a power law:
$\LARGE w(r)= \left( \frac{\sigma}{r}\right)^{n}$ 
where $\sigma$ is the *hard sphere diameter* and $n$ is an *integer in between 9 and 16*. 
![[Helper/media/Hard-soft repulsion graph.png]]
In the [[Soft Matter/Lennar Jones pair potential|Lennar Jones pair potential]] n is equal to 12.
The only parameter appearing in this potential is $r$, because is universally valid, and will be always present in every pair potential.
<!--ID: 1698399778476-->




