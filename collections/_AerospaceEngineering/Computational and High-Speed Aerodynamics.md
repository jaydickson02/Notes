---
layout: post
title:  "Computational and High-Speed Aerodynamics"
toc: true
---

# Lecture 1 - Review of Aerodynamic Concepts

## Physical Quantities

* Every physical quantity can be expressed in terms of 4 fundamental properties
	* Mass (m)
	* Length (L)
	* Time (t)
	* Temperature (T)
	

## Properties of a Fluid
* Density
* Viscosity
	* No-Slip Condition
	* Gives rise to most important aerodynamic concepts
* Pressure
	* Normal force

## Dimensional Analysis
* We often have to rely on experiments to determine the answers
* We use dimensional analysis to reduce the number of variables we need to experimentally consider.


# The boundary layer concept (prandtl)

- In the flow past an airfoil, vicsous effecrts are mainly confined to a thin layer close to the surface of the airfoil (the boundary layer) and its wake.
- The BL is dominated by viscocity while the outer region can be considered inviscid

## Origin of boundary layer

### No-slip condition

- At a solid boundary, the fluid will have zeo velocity relative to the boundary. Molecules of fluid right at the surface stick to the surface as flow moves past.

- The flow around a body is determiedn by the action of viscosity in a thing later in th eimmediate vicinity of the body surface. 

- In this thin layer, fluid velocity increases from zero at the wall to the external flow value, where viscosity may be ignored.

- Even thought viscosity may be small, the shear stress will still be large near the wall, because of the large velocity gradient.

## Definition of boundary layer profile

- A boundary layer profile is a plot of streamwise velocity, U, against perpendicular wall distance, y. The boundary layer charecteristics are very sensistive to the shape of the profile.

- A comparison between two profile shapes is best made by using nondimensional profiles. In these profiles $U_1$ is the freestream velocity and $\delta_{99}$ is the 99% boundary layer thickness (defined as the point where the velocity reaches 99% of the freestream value).

## Boundary layer thickness

- The boundary layert thickness grows as the flow proceeds over the body, as more flow is affected by fluid friction as the flow proceeds over a body.
- There are different ways to define a boundary layer
	- **Physical Thickness:** 99% thickness, $\delta_{99}$, is the wall distance where velocity reaches 99% of the freestream value.
	- **Displacment Thickness:** Displacment thickness, $\delta^*$ is the distance that the external streamlines of the outer potential flow are shifted due to presence of the boundary layer.
		- Same mass flow rate would occur for frictionless flow if boundary was moved out by $\delta^*$
	- **Momentum thickness:** Thickness of freestream fluid with same momentum as the momentum defect due to the boundary layer

## Some definitions

- Viscosity is responsible for the formation of shear stress $\tau = {\mu \partial u /\partial y}$
- $\mu$ is the coefficient of **dynamic** viscosity and v is the coefficient of **kinematic** viscosity: $v = \mu/\rho$
- Viscosity is a physical property of a fluid and it varies differently for gases and fluids
	- Variation with T 
		- Liquids $\mu$ decreases as T increases
		- Gases $\mu$ increases as T increases.
		- For air at sea level conditions: $\mu = 1.7894 \times 10^{-5} kg/(m\cdot s)$ and $v = 1.4607 \times 10^{-5} m^2/s$
- Reynolds number is a measure of the ratio of inertial forces to viscous forces

$$
Re = {{\rho_{\infty V_{\infty} L}} \over \mu_{\infty}} = {{V_{\infty} L} \over v_{\infty}}
$$

- Exact similtude will only exist between a wind tunnel model, CFD analysis and a real aircraft at the same Re.