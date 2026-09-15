# A4 – Motor Mount

## Objective

Design a motor mount for the Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox motor linked [here](https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100) with analyses for both stress and deflection.

## Analyze

### Feature 1

Feature 1 was decided to have a height of 5 cm and a length of 10 cm. 

The formula used with respect to stress is:

<p align="center"> σ = Mc/I </p>

Where:

<p align="center"> I=bh<sup>3</sup>/12</p>

The formula used with respect to deflection is:

<p align="center"> δ=12ML<sup>2</sup>/2EI</p>

Where E is the material modulus of elasticity. In this case, the material chosen was ABS, with E = 1.79 GPa.

From the calculations with respect to stress, the base was found to be a minimum of .876 cm. From the calculations with respect to strain, the base was found to be a minimum of .00965 cm. These values include the safety factor of 3 and have been rounded up. The final base dimensions are b = 1 cm, h = 5 cm, L = 10 cm.
<img width="2531" height="1934" alt="Feature 1" src="https://github.com/user-attachments/assets/f2f00aa0-80fe-4bf8-babd-f8242cbf756a" />

### Feature 2

Feature 2 was decided to have a height of 5 cm and a length of 1 cm to accommodate holes for bolts to mount the motor to the wall.

The final base dimensions are b = 4 cm, h = 5 cm, L = 1 cm.
<img width="2264" height="1389" alt="Feature 2" src="https://github.com/user-attachments/assets/48614aeb-fffb-441b-9b5e-20398cde1409" />

### Sketch

The isometric sketch for my design is as follows.
<img width="2035" height="1847" alt="Iso Sketch" src="https://github.com/user-attachments/assets/c8e93644-f95b-4d4a-a76c-72b1bfbff474" />
Base dimensions were rounded up to accommodate for the size of the bolts needed to attach the mount to the rigid wall. While according to my calculations, the base could have been as small as 0.8 cm, this did not reasonably allow the bolts to fit in the bracket. On feature 1 where the motor shaft protrudes, a thickness of less than 1 cm would have collapsed under the stress from P = 300 N.

### CAD Model

Click [here](https://github.com/bfagan2/megr2156-portfolio/blob/595e7ef50b770f390088bd642f76b3d7c9bbf41b/2156%20A4.SLDPRT) to download the CAD file for this assignment.
