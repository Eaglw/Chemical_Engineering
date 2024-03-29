---
dg-publish: "true"
tags:
  - notdone
---
$\LARGE \frac{\partial c_{i}}{\partial t}+\nabla \cdot (c_{i}\mathbf{\overline{u^{*}}})=-\nabla \cdot \mathbf{j^{*}_{i}}+R_{i}$
where:
- $c_{i}$ is the molar concentration of the i-th species, in $\frac{mol}{m^{3}}$
- $\overline{\mathbf{u^{*}}}=(\overline{u^{*}}_{x},\overline{u^{*}}_{y},\overline{u^{*}}_{z})$ is the molar average mixture velocity, in $\frac{m}{s}$
- $\mathbf{j^{*}}_{i}=(j^{*}_{i,x},j^{*}_{i,y},j^{*}_{i,z})$ is the diffusive mass flux of the i-th species, in $\frac{mol}{m^{2}\cdot s}$
- $R_{i}$ is the rate of mass production/disappear of the i-th species, in $\frac{mol}{m^{3}\cdot s}$

and the mass average mixture velocity is defined as:
$\large \overline{u^{*}}=\frac{\sum^{N}_{i=1}c_{i}\mathbf{u}_{i}}{\sum^{N}_{i=1}c_{i}}=\frac{\sum^{N}_{i=1}c_{i} \mathbf{u}_{i}}{c}$

Differently from the [[Advanced Transport Phenomena/Mass expression of the species transport equation|mass expression]], in a mixture of N components, summing up the N species transport equations in molar terms *don't* results in the [[Advanced Transport Phenomena/Mass balance equation|continuity equation]] of the overall system since, during a reaction, the moles do not remain constant in general, but only the mass is conserved. 