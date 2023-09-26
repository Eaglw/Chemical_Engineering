Geometry in Comsol is created by an ordered list of elements and tranformations on those elements. 
It's useful to define the objects properties through global parameter defined in the global definition section, in which we can specify the units in order to automatically convert them. Specification happens through square parenthesis. 
Every added elements is a region through which the fluid can flow, but we can add or subtract parts from it with some functions like union, difference, intersection, and some more advanced ones, like:
1. Fillet: Used to round squared edges with a given radius.
2. 