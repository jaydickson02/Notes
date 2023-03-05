---
layout: post
title:  "Aerospace Structures"
---



# Intro to Structural Analysis

Content Tags: Hookes Law, Internal Loads, Strain, Stress, Supports
Created: March 6, 2022 9:10 AM



## Stress

- Stress on a small element of a material under load
- 2 types of stresses:
  - Normal
  - Shear
- Ask what does a load do to a cross section?
  - What loads are there? Moments? Stresses?

## Shear and Normal stress produce fundamentally different forces in the material

- Normal is a compressive or stretching action
- Shear is considered as though it acts on a plane

## What is strain? What are the units of strain?

- Strain is a change in material distortion under the effect of a stress
- The units are dimensionless (Change in Length/Length)

## What is normal strain? What is shear strain?

- Normal strain acts through the cross section of the body to lengthen or contract it
- Shear strain creates torsion and warping

## What is a positive and negative normal strain?

- Positive normal acts in torsion
- Negative acts to compress

## What is a positive and negative shear strain?

- Positive and negative only alters the direction of the torsion. So clockwise or counter-clockwise

## Normal Strain is?

- The slope of displacement

## Shear Strain is? 

- Still non-dimensional
- Relationship??

## Poisson’s ratio?

- Ratio of strains. Reaction strain acting in orthogonal direction is cause by original strain.

## Hooke’s Law?

- Constant Value = Stress/Strain, while elastic.

## Plane (2D) Problems

- Disregard a particular aspect because nothing important is happening in the other access out of plane. This needs to be carefully evaluated.

## Beams and Plates

- Take a beam and extrude it for plates
- Plates have a poisson effect that beams don’t have

## 2D State of Stress

- Your stresses are dependant on your coordinate system
- Can resolve state of stress into principal stress
- Use Moores circle
- A cylinder under normal tension will fracture vertically
- A cylinder under shear will fracture diagonally. Imagine the shear diagram deforming a square into a kite shape.

## Aircraft Materials

- Common Materials:
  - Metals (Most discussed)
  - composites
  - Sandwich

## Static Equivalence

- Same forces and same moments
- Internal loads must be equivalent to the external load that is acting on the body.
- Internal reaction loads are equal and opposite. The internal loads are not.

## Partial Derivative

- The partial derivative is the derivative of a function with respect to one variable only
- This gives the rate of change, or slope, of a function with respect to one variable

## Support Conditions

- Import drawings for supports. (Roller, Fixed, Pin). Add degree of freedom info.
- Rollers always provide a force in the Y direction regardless of the sign of the force. Not in the X direction. Or vice versa depending on the unit system.

## Internal Loads

- 4 Types of internal loads:
  - Normal (N)
  - Shear (V)
  - Torsional (T)
  - Bending (M)

## Force and Moment Diagrams

- Take a slice and determine the shear force and moment at that point (This is important for this course)

### Reference Material

[(1A)_Intro_to_structural_analysis-1.pdf](AerospaceStructuresMedia/(1A)_Intro_to_structural_analysis-1.pdf)

---



# Euler Buckling


Created: April 28, 2022 11:02 AM

## Euler Column Theory

- Valid, within the limits of assumptions
- Based on a perfect stable section column
  - The column is perfectly straight
  - Load is applied at the section centroid
  - Column material is homogenous
  - Stresses are in the elastic range
  - No local section instabilities (no twist or deformation)

![Untitled](AerospaceStructuresMedia/Untitled.png)

- Perfect column under compressive load P
- Load associated with buckling is $P_{CR}$
- If column is displaced by lateral load F

## Derivation of Euler Buckling Equation

![Untitled](AerospaceStructuresMedia/Untitled%201.png)

![Untitled](AerospaceStructuresMedia/Untitled%202.png)

## Buckling Modes

- Each n buckling mode (displacement shape) has an associated buckling load
- n = number of “half waves” in buckling mode shape

$$
P_{CR} = {n^2\pi^2EI\over L^2}
$$

## Effective Length

![Untitled](AerospaceStructuresMedia/Untitled%203.png)

## End Fixity

- How the ends of the columns are restrained
- Most columns have some form of restraint (end fixity)
- To account for this, the effective length L’ is adopted $P_{CR} = {\pi^2EI\over (L')^2}$

![Untitled](AerospaceStructuresMedia/Untitled%204.png)

## Second Moment of Area

![Untitled](AerospaceStructuresMedia/Untitled%205.png)

- Buckling always occurs around the axis of $I_{min}$

## Stress Form of Buckling Equation

![Untitled](AerospaceStructuresMedia/Untitled%206.png)

## Column Curve

![Untitled](AerospaceStructuresMedia/Untitled%207.png)
