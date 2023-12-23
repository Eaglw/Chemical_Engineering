---
tags:
  - notdone
---
If a fluid is not homogeneous but a mixture, where two or more miscible species flow, mix and eventually react, the time and space evolutino of the mixture composition is governed by a *species transport equation on each species*.
# Mathematical expression
We can express this equation in 4 physically equivalent ways, writing them in terms of mass, moles, mass fraction or mole fraction:
1. [[Mass expression of the species transport equation|Mass expression]]
2. [[Mass fraction expression of the species transport equations|]]
3. [[Moles expression of the species transport equations|Moles expression]]
4. 
## Moles expression
$\LARGE \frac{\partial c_{i}}{\partial t}+\nabla \cdot (c_{i}\mathbf{\overline{u^{*}}})=-\nabla \cdot \mathbf{j^{*}_{i}}+R_{i}$
where:
- $c_{i}$ is the molar concentration of the i-th species, in $\frac{mol}{m^{3}}$
- $\overline{\mathbf{u^{*}}}=(\overline{u^{*}}_{x},\overline{u^{*}}_{y},\overline{u^{*}}_{z})$ is the molar average mixture velocity, in $\frac{m}{s}$
- $\mathbf{j^{*}}_{i}=(j^{*}_{i,x},j^{*}_{i,y},j^{*}_{i,z})$ is the diffusive mass flux of the i-th species, in $\frac{mol}{m^{2}\cdot s}$
- $R_{i}$ is the rate of mass production/disappear of the i-th species, in $\frac{mol}{m^{3}\cdot s}$

and the mass average mixture velocity is defined as:
$\large \overline{u^{*}}=\frac{\sum^{N}_{i=1}c_{i}\mathbf{u}_{i}}{\sum^{N}_{i=1}c_{i}}=\frac{\sum^{N}_{i=1}c_{i} \mathbf{u}_{i}}{c}$


