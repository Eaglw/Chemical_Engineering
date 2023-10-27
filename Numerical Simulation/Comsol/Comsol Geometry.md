---
dg-publish: true
---
Geometry in Comsol is created by an ordered list of elements and tranformations on those elements. 
It's useful to define the objects properties through global parameter defined in the global definition section, in which we can specify the units in order to automatically convert them. Specification happens through square parenthesis. 
Every added elements is a region through which the fluid can flow, but we can add or subtract parts from it with some functions like union, difference, intersection, and some more advanced ones, like:
1. Fillet: Used to round squared edges with a given radius.
2. Chamfer: similar to fillet, but it cuts with a straight line instead of a circle. 
## Boundaries
The presence or absence of boundaries in the graph is irrelevant to the simulation, in fact the last element of a build all run is a "union". But they are relevant for the mesh construction. The presence of a boundary impose the mesh algorithm to use that boundary as one of the side of the triangles.
Lowering the amount of boundaries makes the mesh creation faster and better because of the presence of less constraints.
## 3D version
It works very similar, but there is also the possibility to plan a geometry in a 2D plane and the extrude or rotate it around an axis in order to obtain a 3D object.
