# A3 – Parametric and FEA

## Objective
The objective of this assignment is to design a fixed beam, applying principles of stress, strain, and deformation to create a 3D model analysis to prove our calculations. We will untilize a CAD software of our choosing to parametrically model the beam, using length as the driver for the rest of the dimensions of the beam. The beam is assumed to be rigidly fixed on one face with no deflection or stress concentrations at that point.

## Decide
Our design constraints outline that the beam should be made of Aluminum, for which we decide the Young's Modulus of the alloy we are to use. For this assingment I will be choosing varying Young's Moduli for each iteration of the beam. Doing this will allow me to better understand the relationship between the Young's Modulus and the dimensions of the bar as contained in the direct tension elongation equation.  I am aware that the assingment does not require the smallest possible beam be made, however, I am using this opportunity to explore rigidity in design applications as well as refine my ability to perform FEA. 

### First Iteration
For the first iteration I am defining the following values:

- diameter (d) = 2 cm
- Young's Modulus (E) = 8.5 x 10^6 psi

To parametrize elements of the beam, we are using the direct tension elongation equation as specified in the Machinery's Handbook, (FL/EA), where F is the tensile force applied to the beam, L is the longitudinal length of the beam, E is the Young's Modulus, and A is the cross-sectional area.

The chosen diameter will yield a cross sectional area A as described by this equation for circular cross-sections: 

<p align="center"> A = pi(d^2/4)</p>


## Communicate

