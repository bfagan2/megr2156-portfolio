# A3 – Parametric and FEA

## Objective
The objective of this assignment is to design a fixed beam, applying principles of stress, strain, and deformation to create a 3D model analysis to prove our calculations. We will utilize a CAD software of our choosing to parametrically model the beam, using length as the driver for the rest of the dimensions of the beam. The beam is assumed to be rigidly fixed on one face with no deflection or stress concentrations at that point, and free to bend and move on the other end.

## Decide
Our design constraints outline that the beam should be made of Aluminum (S<sub>y</sub> = 40 ksi), for which we decide the Young's Modulus of the alloy we are to use. I will be using a value of 8.5 x 10<sup>6</sup> psi, a diameter of 2cm and an applied force of 500lbf.


## Communicate


For the second iteration I am defining the following values:

- d = 1 cm
- E = 8.5 x 10<sup>6</sup> psi
- F = 500 lbf

The chosen diameter will yield a cross sectional area A as described by this equation for circular cross-sections: 

<p align="center"> A = pi(d<sup>2</sup>/4)</p>

Therefore A for this iteration is equal to:

<p align="center"> A = 0.000315 m<sup>2</sup></p>

The following is the image of the parameters defined in the model tree:
<img width="777" height="172" alt="Eqs I2" src="https://github.com/user-attachments/assets/2da1a58b-f7ab-48e9-82cc-788a892f196f" />

The following is the image of the final displacement study results:
<img width="1173" height="532" alt="A3 displacement study (2)" src="https://github.com/user-attachments/assets/f1fd1503-0232-44e8-bcfe-7415781c1a52">

The study resulted in an axial deflection of .009 in, which is exactly the maximum allowed deflection. I used the deflection parameter to limit the length of the bar, to determine the maximum length the bar could be in order to fit the deflection parameter. For this calculation, I would trust the hand calculation more than the simulation, simply on the basis of mesh. Calculating the deflection of this bar is not difficult, and it requires one simple equation that takes into account the entirety of the bar, while using a mesh in the simulation allows for summation errors to occur when finalizing the value. Simulations would be more trustworthy where the geometry of the model renders hand calculations impossible, however they are not extremely exact values. This is why a safety factor is built into the design to account for possible error and design misuse.

The following is the image of the Von Mises Stress map:
<img width="1372" height="585" alt="Screenshot 2026-09-07 211656" src="https://github.com/user-attachments/assets/c83415d9-84e0-41e2-a5da-243e8f4f9149" />

The stress map details that the maximum stress experienced by the bar at these parameters is 4.403e+00 as compared to the yield strength of 4.000e+01, confirming that the bar survives the applied force with a safety factor of 11.

Imagining a substantial hole in the left side of the bar would put the surrounding area under an increased stress of around 2 times what the bar is already experiencing at that point. In this case the max stress would be 8.220e+00, which is well within the max stress allowance for the bar.

### Lessons Learned

I have worked in Solidworks before, however I have only done FEA and simulations in Siemens NX. Using the Solidworks UI took some time to get used to, and the tools are mostly the same. The total time spent on this assignment was approximately 3 hours.

