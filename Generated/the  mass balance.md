---
dg-publish: "false"
tags:
  - notdone
---

Source: [[PDFs/the  mass balance.pdf]]

---

###### Page 1

<sup>DRAFT</sup>

4The mass balance

# 4.1Macroscopic mass balance

### Intuitively, the principle of mass conservation is before our eyes in daily practice: if we draw biscuits from a bag, sooner or later, we will end up with an empty bag; if we drive our car without

refilling the tank, at some point we will run out of fuel; if we pour more water in the kitchen sink than it can flow away, water will eventually overflow. In these and many other common situations, we know that the mass entering or exiting a system cannot disappear or be created, but it must end up somewhere. From a scientific perspective, it was the french chemist AntoineLaurent de Lavoisier, in 1789, the first to establish the principle of mass conservation. His experiments led to the conclusion that the number of atoms of the single elements is preserved during chemical reactions. In other words, mass cannot be created nor destroyed (unless we consider nuclear reactions, which is beyond the scope of this course). The mass conservation in transport phenomena is expressed

in terms of general macroscopic and microscopic mass balance equations. Transport phenomena generally involve pipes, reactors, heat exchangers, or other instrumentation with well defined geometries and specific inlet and outlet sections. However, the mass balance equations are derived for the most general case, namely considering a control volume such as in Figure 4.1. The orientation of the surface*S*, defined by the normal unit vector **n**, is different in each point of*S*(by convention, the orientation of**n**is towards the outside of*V*). In addition, all infinitesimal elements of the surface*S*are permeable to mass (for simplicity, you can think of the surface as a net). Let the control volume*V* be fixed in space and subjected to an arbitrary mass flow field**v**. In other words, each point*P* = (*x*,*y*,*z*)of*V*corresponds to a specific density value*ρ* =*ρ*(*x*,*y*,*z*)and velocity vector**v** = **v**(*x*,*y*,*z*). Note that, in general, density and velocity are also functions of time*t*, hence the balance is referred to a generic interval time


---

###### Page 2

<sup>DRAFT</sup>

2 Macroscopic mass balance

*dt*. Since mass cannot be generated or consumed, the general equation of the mass balance is the following:

### *IN* − *OU T*=*ACC*(4.1)

**<sup>Figure 4.1 :</sup>**A generic control volume

In order to apply Equation 4.1 to the control volume of Figure 4.1, we need to divide the surface*S*in an infinite number of infinitesimal elements*dS*, small enough that they can be considered flat. In other words,*dS*must be small enough to be characterized by a single normal unit vector**n**, by a single density value*ρ*, and by a single velocity vector**v**. Let us assume that the single element*dS*is a square, as depicted in figure 4.2.

**Figure 4.2** **:**Evaluation of the flow rate through the infinitesimal surface element*dS*.

Let us consider an infinitesimal interval time*dt*. During*dt*, the fluid crossing*dS*travels the distance**v** *dt*. Therefore, the volume of fluid*dV*, crossing*dS*in the interval time*dt*, corresponds to the parallelepiped having base*dS*and lateral side**v** *dt*. In general, such parallelepiped is oblique, as**n**and**v**do not have the same direction. Hence, the volume*dV*is obtained from the product of*dS*by the height of the parallelepiped*h*, which is given by the projection of**v** *dt*along the direction of**n**. By using vector operations, we can express*h*through a scalar product:*h* = **v** *dt*·**n**. The volume*dV*is then obtained as follows:

*dV* = **v*dt*·**n*dS*(4.2)

The infinitesimal volumetric flow rate*dQ*, namely the volume of

fluid crossing the surface*dS*per unit time, is given by:

*dQ* =

*dV*

*dt*

= **v** · **n*dS*(4.3)

The infinitesimal mass flow rate*d* ˙

*m*is obtained multiplying the volumetric flow rate by density:

*d* ˙

*m* = *ρ***v**·**n*dS*(4.4)

Dr. Salvatore Costanzo DiCMaPI University of Naples Federico II

<sup>Advanced Transport Phenomena</sup>

<sup>for Industrial Bioengineering</sup>


---

###### Page 3

<sup>DRAFT</sup>

The mass balance3

It is now important to note that, since the unit vector**n**points towards the outside of the control volume, any infintesimal mass flow rate entering the control volume is negative. In fact, the mass flow rate*d* ˙

*m*enters the control volume if the angle*θ*between the velocity vector**v**and the unit vector**n**is comprised between90 °

and180°. In such an angle interval,cos (*θ*)is negative. On the other hand,*d* ˙

*m*exits the control volume if the angle*θ*is comprised between0 °and90 °. In such a rangecos (*θ*)is positive. Therefore, according to our convention, the mass flow rate contributions entering the control volume are negative whereas the ones exiting the control volume are positive. However, based on the signs in equation 4.1, it is more convenient to have the entering mass positive and the exiting mass negative. Hence, we add a minus on the left term of equation 4.4, and we write:

*d* ˙

*m* =−*ρ***v**·**n*dS*(4.5) The term*d* ˙

*m*refers to the infinitesimal surface*dS*. The global mass flow rate crossing the system per unit time is obtained by summing the contributions of all infinitesimal elements*dS*of the surface*S*. This is done through a surface integral:

### *IN* −*OU T*=

(

−

∫

*<sup>S</sup>*

*ρ* **v** ·**n*dS*

)

*dt* (4.6)

From Equation 4.6, we get a mathematical expression for the *IN* −*OU T*term of Equation 4.1. In order to obtain the mass balance equation, there remains to find a mathematical formulation of the accumulation term. The total mass contained in the control volume*V*at a time

instant*t*can be calculated as:

*m* *V*=

∫

*<sup>V</sup>*

*ρdV* (4.7)

Going through a volume integration in Equation 4.7 is necessary, as the density is generally not constant in each point of the volume*V*. Hence, we divide the volume*V*in an infinite number of infinitesimal elements*dV*, small enough that the density can be considered constant in each of them. Then, the mass*dm*contained in each element*dV*is given by the product*ρdV*. The total mass is the sum of all contributions coming from the elements *dV* , that is, the volume integral of Equation 4.7. Based on equation 4.7, the mass accumulated inside the control volume in the generic interval time*dt*is given by:

### *ACC*=

∫

*<sup>V</sup>*

*ρdV*

∣

∣

∣

∣

*<sup>t + dt</sup>*

−

∫

*<sup>V</sup>*

*ρdV*

∣

∣

∣

∣

*<sup>t</sup>*

(4.8)

Advanced Transport Phenomena for Industrial Bioengineering

Dr. Salvatore Costanzo

DiCMaPI

University of Naples

Federico II


---

###### Page 4

<sup>DRAFT</sup>

4Microscopic mass balance

Now we have found a mathematical expression for all terms of equation 4.1. Substituting Equation 4.6 and Equation 4.8 into Equation 4.1, we obtain: ( −

### ∫ *S*

*ρ* **v** ·**n*dS*

)

*dt* =

∫

*<sup>V</sup>*

*ρdV*

∣

∣

∣

∣

*<sup>t + dt</sup>*

−

∫

*<sup>V</sup>*

*ρdV*

∣

∣

∣

∣

*<sup>t</sup>*

(4.9)

Dividing equation 4.9 by*dt*and bringing it to the limit as*dt* approaches zero we have:

−

∫

*<sup>S</sup>*

*ρ* **v** · **n*dS*=

*d*

*dt*

∫

*<sup>V</sup>*

*ρ dV* (4.10) Equation 4.10 is the general equation for themacroscopic mass balance. The term*ρ* **v**is the mass flux (mass crossing a surface per unit

time and unit surface). As mentioned in the previous chapter, the mass flux is obtained by the product of velocity into mass concentration.

4.2 Microscopic mass balance

Equation 4.10 represents the macroscopic mass balance. In this section, we are going to derive a local expression of the mass balance, which is particularly useful for implementing computational fluid dynamics. In order to obtain the microscopic mass balance from Equation 4.10, we are going to use the divergence theorem (also known as Gauss’ theorem), in order to transform the surface integral into a volume integral.

Theorem 4.1: Divergence Theorem

Let*V*be a volume bounded by a piecewise smooth closed surface*S*with positive orientation pointing out of*V*, and let**a** = **a**(*x*,*y*,*z*)be a vector field with continuous first order partial derivatives, Then

∫

*<sup>S</sup>*

**a** · **n** *dS*=

∫

*<sup>V</sup>*

**∇** · **a** *dV*(4.11)

Applying the theorem 4.11 to the left term of equation 4.10, we have:

−

∫

*<sup>S</sup>*

*ρ* **v** · **n*dS*=−

∫

*<sup>V</sup>*

**∇** · *ρ* **v*dV*(4.12)

Substituting equation 4.12 into equation 4.10 we have:

−

∫

*<sup>V</sup>*

**∇** · *ρ***v*dV*=

*d*

*dt*

∫

*<sup>V</sup>*

*ρdV* (4.13)

Dr. Salvatore Costanzo DiCMaPI University of Naples Federico II

<sup>Advanced Transport Phenomena</sup>

<sup>for Industrial Bioengineering</sup>


---

###### Page 5

<sup>DRAFT</sup>

The mass balance5

Since the control volume*V*is fixed in space, the time derivative on the right term of Equation 4.13 can be swapped with the integral over the volume*V*, yielding:

−

∫

*<sup>V</sup>*

**∇** ·*ρ***v*dV*=

∫

*<sup>V</sup>*

*∂*

*∂t*

*ρdV* (4.14)

Using the linearity rules of integration, we can bring the left term of Equation 4.14 to the right side, and write: ∫

*<sup>V</sup>*

(

*∂ρ*

*∂t*

+ **∇**·*ρ***v**

)

*dV* =0(4.15)

Since the choice of the control volume is arbitrary, there is only one way to verify Equation 4.15: the integrand function must be identically zero in each point of the control volume. Hence, from Equation 4.15, it results that:

*∂ρ*

*∂t*

+ **∇**·*ρ***v**=0(4.16)

Equation 4.16 is the equation of themicroscopic mass balance, also referred to ascontinuity equation. Let us consider some particular cases of Equation 4.16. If we assume steady conditions, the time derivative of density is null, hence Equation 4.16 becomes the following:

**∇** ·*ρ***v**=0(4.17) If we consider an incompressible fluid (constant density), Equation 4.17 becomes:

**∇** ·**v**=0(4.18) namely, in a Cartesian coordinate system, we have:

*∂v* 1

*∂x* 1

+

*∂v* 2

*∂x* 2

+

*∂v* 3

*∂x* 3

= 0 (4.19)

Equation 4.19 states that, if the fluid velocity is decreasing in one direction, then it must increase in the others, in order to keep the sum of all velocity derivatives equal to zero.

4.3Lagrangian and Eulerian approach to mass balance

Equation 4.16 was derived considering a control volume fixed in space. Such an approach is calledEulerian. On the other hand, the microscopic mass balance can be reformulated considering a local reference system moving with the fluid particle. Such an approach is calledLagrangian, and uses the concept ofsubstantial derivative. In general, density depends on time

Advanced Transport Phenomena for Industrial Bioengineering

Dr. Salvatore Costanzo

DiCMaPI

University of Naples

Federico II


---

###### Page 6

<sup>DRAFT</sup>

6 Lagrangian and Eulerian approach to mass balance

and position. However, in a moving reference system we have to consider that position also depends on time. In such a case, the time dependence of density is expressed in the following way: *ρ*=*ρ*(*t*;*x*1(*t*),*x*2(*t*),*x*3(*t*))(4.20) Based on Equation 4.20, the time derivative of density is obtained through the chain rule of derivatives, as follows: *∂ρ* *∂t*

+

*∂ρ* *∂x*1

*∂x* 1

*∂t*

+

*∂ρ*

*∂x* 2

*∂x* 2

*∂t*

+

*∂ρ*

*∂x* 3

*∂x* 3

*∂t*

=

=

*∂ρ* *∂t*

+ *v* 1

*∂ρ*

*∂x* 1

+ *v* 2

*∂ρ*

*∂x* 2

+ *v* 3

*∂ρ*

*∂x* 3

=

=

*∂ρ* *∂t*

+ **v** ·**∇*ρ*=

*Dρ*

*Dt*

(4.21)

In Equation 4.21 we have used the definitions of velocity*v* *i* = *dxi*

*<sup>dt and substantial derivative.</sup> The Substantial derivative of a function*α* ( *t* ,*x*1(*t*),*x*2(*t*),*x*3(*t*))is

defined as: *Dα* *Dt*

=

*∂α* *∂t*

+ **v** ·**∇*α*=

*∂α*

*∂t*

+ *v* 1

*∂α*

*∂x* 1

+ *v* 2

*∂α*

*∂x* 2

+ *v* 3

*∂α*

*∂x* 3

(4.22)

Therefore, with the Lagrangian approach, Equation 4.16 can be

re-written as1:

<sup>1</sup>

note that: **∇** · *ρ* **v**=

*∂* *∂xi*

**e** *i*·*ρvj***e*j*=

=

*∂* *∂xi*

( *ρvj*)***δ**ij*=

*∂* *∂xi*

( *ρvi*) =

= *ρ*

*∂v* *i* *∂xi*

+ *vi*

*∂ρ* *∂xi* = *ρ***∇**·**v**+**v**·**∇*ρ*

*∂ρ* *∂t*

+ **∇**·*ρ***v**=

*∂ρ* *∂t*

+ **v** ·**∇*ρ*+*ρ***∇**·**v**=

*Dρ*

*Dt*

+ *ρ* **∇** ·**v**=0(4.23)

The two forms of the mass balance corresponding to the two

different approaches are listed in Table 4.1.

**Table 4.1** **:**mass balance in

Eulerian and Lagrangian approach.

Eulerian approach:

*∂ρ*

*∂t*

= − **∇**·*ρ***v**

Lagrangian approach:

*Dρ*

*Dt*

= − *ρ* **∇**·**v**

For an incompressible fluid, the density is constant in both time and space, then:

*Dρ*

*Dt*

= 0 (4.24) Hence, from equation 4.23, equation 4.18 is again obtained.

Dr. Salvatore Costanzo DiCMaPI University of Naples Federico II

<sup>Advanced Transport Phenomena</sup>

<sup>for Industrial Bioengineering</sup>


### Footnotes
