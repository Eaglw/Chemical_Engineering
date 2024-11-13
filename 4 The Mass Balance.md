---
dg-publish: "false"
tags:
  - notdone
---
### 4.1 Macroscopic Mass Balance

  

The principle of mass conservation is something we see in daily life: if we draw biscuits from a bag, we eventually end up with an empty bag; if we drive a car without refilling the tank, we will run out of fuel; if we pour more water into a sink than it can drain, the water will overflow. These examples show us that mass entering or exiting a system doesn’t disappear but must accumulate somewhere. Scientifically, Antoine Laurent de Lavoisier established the principle of mass conservation in 1789, showing that atoms of each element are preserved in chemical reactions, meaning mass cannot be created nor destroyed (ignoring nuclear reactions).

In transport phenomena, mass conservation is expressed through macroscopic and microscopic mass balance equations. These principles apply to systems like pipes, reactors, and heat exchangers, which have defined inlet and outlet sections. However, mass balance equations are derived for a general control volume, as shown in **Figure 4.1**. The surface *S* has an orientation defined by a normal unit vector **n**, pointing outward from *V*. All elements of *S* are permeable to mass. Let the control volume *V* be fixed in space with a mass flow field **v**. Each point *P = (x, y, z)* in *V* has specific density *ρ = ρ(x, y, z)* and velocity **v = v(x, y, z)**, which may also vary over time.

Since mass cannot be generated or consumed, the general equation of mass balance is given by:

  

$$

\text{IN} - \text{OUT} = \text{ACC} \tag{4.1}

$$

  

To apply this to the control volume in **Figure 4.1**, we divide the surface *S* into an infinite number of infinitesimal elements *dS*, each small enough to be considered flat, characterized by a single normal unit vector **n**, a single density *ρ*, and a single velocity vector **v**. Let *dS* be square-shaped, as depicted in **Figure 4.2**.

For an infinitesimal time interval *dt*, the fluid crossing *dS* travels a distance **v** *dt*, forming a parallelepiped with base *dS* and height given by the projection of **v** *dt* along **n**. Using vector operations, we get:
$$

dV = (\mathbf{v} \cdot \mathbf{n}) \, dS \, dt \tag{4.2}

$$
The infinitesimal volumetric flow rate *dQ*, or the volume of fluid crossing *dS* per unit time, is:

  

$$

dQ = \frac{dV}{dt} = \mathbf{v} \cdot \mathbf{n} \, dS \tag{4.3}

$$

  

The infinitesimal mass flow rate *d\dot{m}* is obtained by multiplying the volumetric flow rate by density:

  

$$

d\dot{m} = \rho \, \mathbf{v} \cdot \mathbf{n} \, dS \tag{4.4}

$$

  

Since the unit vector **n** points outward from the control volume, any mass flow rate entering *V* is negative. Therefore, we add a negative sign to denote the mass flow rate entering as positive:

  

$$

d\dot{m} = -\rho \, \mathbf{v} \cdot \mathbf{n} \, dS \tag{4.5}

$$

  

To find the total mass flow rate across the system per unit time, we sum the contributions of all infinitesimal elements *dS* of *S* through a surface integral:

  

$$

\text{IN} - \text{OUT} = \left(- \int_{S} \rho \, \mathbf{v} \cdot \mathbf{n} \, dS \right) dt \tag{4.6}

$$

  

The total mass in the control volume *V* at a given time *t* can be calculated as:

  

$$

m_V = \int_{V} \rho \, dV \tag{4.7}

$$

  

Since density generally varies within *V*, we divide *V* into infinitesimal elements *dV*. Then, the mass *dm* in each element is *ρ dV*, and the total mass is the integral over all elements in *V*. The mass accumulation over a time interval *dt* is given by:

  

$$

\text{ACC} = \int_{V} \rho \, dV \bigg|_{t+dt} - \int_{V} \rho \, dV \bigg|_{t} \tag{4.8}

$$

  

By substituting **Equations 4.6** and **4.8** into **Equation 4.1**, we get:

  

$$

\left(- \int_{S} \rho \, \mathbf{v} \cdot \mathbf{n} \, dS \right) dt = \int_{V} \rho \, dV \bigg|_{t+dt} - \int_{V} \rho \, dV \bigg|_{t} \tag{4.9}

$$

  

Dividing by *dt* and taking the limit as *dt* approaches zero gives:

  

$$

- \int_{S} \rho \, \mathbf{v} \cdot \mathbf{n} \, dS = \frac{d}{dt} \int_{V} \rho \, dV \tag{4.10}

$$

  

### 4.2 Microscopic Mass Balance

  

Equation 4.10 represents the macroscopic mass balance. To derive a local, or microscopic, form of the mass balance, we use the divergence theorem, which converts a surface integral to a volume integral.

  

**Divergence Theorem**: For a vector field **a** with continuous first-order partial derivatives, over a volume *V* bounded by a surface *S*,

  

$$

\int_{S} \mathbf{a} \cdot \mathbf{n} \, dS = \int_{V} \nabla \cdot \mathbf{a} \, dV \tag{4.11}

$$

  

Applying the theorem to the left side of **Equation 4.10**:

  

$$

- \int_{S} \rho \, \mathbf{v} \cdot \mathbf{n} \, dS = - \int_{V} \nabla \cdot (\rho \mathbf{v}) \, dV \tag{4.12}

$$

  

Substituting into **Equation 4.10** yields:

  

$$

- \int_{V} \nabla \cdot (\rho \mathbf{v}) \, dV = \frac{d}{dt} \int_{V} \rho \, dV \tag{4.13}

$$

  

Since the control volume *V* is fixed in space, we can swap the time derivative with the volume integral on the right side of **Equation 4.13**:

  

$$

- \int_{V} \nabla \cdot (\rho \mathbf{v}) \, dV = \int_{V} \frac{\partial \rho}{\partial t} \, dV \tag{4.14}

$$

  

Using integration linearity, we obtain:

  

$$

\int_{V} \left( \frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{v}) \right) dV = 0 \tag{4.15}

$$

  

Since *V* is arbitrary, the integrand must be zero at each point in *V*, leading to the continuity equation:

  

$$

\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{v}) = 0 \tag{4.16}

$$

  

### 4.3 Lagrangian and Eulerian Approach to Mass Balance

  

Equation 4.16 was derived using a fixed control volume, known as the Eulerian approach. Alternatively, using a reference frame moving with the fluid particle, the Lagrangian approach, we can rewrite the continuity equation using the substantial derivative:

  

$$

\frac{D \rho}{D t} = \frac{\partial \rho}{\partial t} + \mathbf{v} \cdot \nabla \rho \tag{4.21}

$$

  

In the Lagrangian form, the continuity equation becomes:

  

$$

\frac{D \rho}{D t} = -\rho \, \nabla \cdot \mathbf{v} \tag{4.23}

$$

  

For an incompressible fluid, density is constant, giving:

  

$$

\frac{D \rho}{D t} = 0 \tag{4.24}

$$

  

Thus, equation 4.18 is satisfied again:

  

$$

\nabla \cdot \mathbf{v} = 0

$$