# A11 – Motor Selection (Team Project) 

## Member 1: Pierce Brown

### Objective

The objective of part 1 was to select a gear-motor for each lead screw using torque and speed requirements from the previous assignment, A10. Document the motor's rated output torque, speed, efficiency, voltage, current, and mounting. Use the motor's torque-speed curve to verify the motors can handle the 2kN total test load across the 1-50mm/min speed range with the required safety factor of 4. 

### Part 1 - Motor Selection and Attachments


<img width="955" height="438" alt="image" src="https://github.com/user-attachments/assets/6ca56df2-92ea-48b4-9b4c-9862d3f5ea56" />

The McMaster-Carr 4855N17 gear motor is listed as base mounted. It has a 1/2 ich diameter by 1 inch long keyed output shaft. The reference drawing also shows four #10-32 face holes on a 2.645 by 2.645 inch pattern.

Using the 2.54mm/rev screw lead from A10, the required crosshead speed of 1-50 mm/min corresponds to 0.394-19.685 rpm per motor. The operating thread torque from A10 is 1.36 N*m per screw. Applying the requires safety factor I got a torque of Td = 5.44 N*m or 48.1 lbf*in. 

<img width="748" height="567" alt="image" src="https://github.com/user-attachments/assets/dd9c7e8f-f04f-4140-8896-dbf6662e0823" />
<img width="751" height="574" alt="image" src="https://github.com/user-attachments/assets/948478c9-c1e8-4681-bbd2-a9b42f47f1f5" />

at the maximum required speed of 19.685 rpm, the 90 V DC torque-speed chart shows around 80-85 lbf*in per moor. the plotted torque is higher at all lower speeds in the required range, supporting the selection of motor 4955N17. https://www.mcmaster.com/4855N17/

## Member 2: Rama Hamid

## Objective

The objective of this assignment was to design and analyze the motor mounting bracket, shaft coupler, and frame connections for our dual-leadscrew tensile testing machine. The components were designed to support the required loading, transmit motor torque, and maintain proper alignment while considering the required safety factor of 4

## Analyze

### section 2- Motor Mount Bracket Design

For the motor mounting bracket, we selected 6061-T6 aluminum because it offers good strength, low weight, and ease of machining. We proposed a 6.35 mm (1/4 in) thick mounting plate with four holes corresponding to the motor's mounting pattern. We used bearing stress analysis to determine the minimum required plate thickness under the applied motor torque

#### Knowns & Unknowns

<img width="1180" height="568" alt="image" src="https://github.com/user-attachments/assets/97d8d138-e5cf-4ed6-b407-e4d8d111bf23" />

#### FBD & handwritten calculations 
<img width="768" height="960" alt="image" src="https://github.com/user-attachments/assets/703c154e-de98-47a3-8354-aa443f2009ad" />

<img width="1544" height="1542" alt="image" src="https://github.com/user-attachments/assets/b475d392-c851-4c97-b9f4-d4a2414ba65a" />

<img width="828" height="576" alt="image" src="https://github.com/user-attachments/assets/af45dd9e-2e03-4819-81f3-f891f90c0dfb" />

The calculated minimum thickness was approximately 0.086 mm for the simplified bolt bearing-stress model. We selected a thicker 6.35 mm plate to provide a more practical and rigid mounting surface. This thickness satisfies the preliminary bearing-stress check, although bracket bending, frame attachment loads, and deflection still require verification.

source: https://www.mcmaster.com/4855N17/

### Section 3- Coupler Design

The coupler connects the motor output shaft to the leadscrew and transfers the torque required to operate the tensile testing machine. We initially analyzed a hollow cylindrical coupler using 6061-T6 aluminum to estimate the minimum outer diameter and wall thickness. We then selected a commercially available flexible coupling to accommodate small shaft misalignments and simplify assembly

#### Knowns & Unknowns

<img width="1184" height="880" alt="image" src="https://github.com/user-attachments/assets/176ee0d1-b9a0-417c-b733-6e25d33590da" />

<img width="1176" height="590" alt="image" src="https://github.com/user-attachments/assets/2dea67bc-87ce-4b7c-97ac-86ea53b1715b" />

#### FBD & handwritten calculations

<img width="828" height="812" alt="image" src="https://github.com/user-attachments/assets/c5bb2b8a-25fb-4427-8d82-b907ebd106a3" />

<img width="828" height="902" alt="image" src="https://github.com/user-attachments/assets/0eae6f5b-6c03-47e3-86c1-43ce89521211" />

<img width="3172" height="1640" alt="image" src="https://github.com/user-attachments/assets/b5b95761-de36-4bb7-a566-722d4ce8bdae" />

We selected McMaster-Carr Precision Flexible Shaft Coupling #6208K569 as our preliminary coupler. It has two 12.70 mm (1/2 in) bores, a 31.75 mm outer diameter, and a 31.75 mm overall length. Its maximum rated torque of 9.49 N·m exceeds our design torque of 5.44 N·m. We chose this coupling because its flexible design accommodates small misalignments and its clamp-on mounting simplifies assembly. The motor's keyed shaft and the leadscrew coupling end still need to be checked for compatibility


Our preliminary cylindrical analysis gave a minimum wall thickness of approximately 0.133 mm, and we initially proposed a 6.35 mm wall thickness. These calculations helped establish a preliminary design, but they do not directly represent the stress distribution in the purchased spiral-cut coupling. Therefore, the manufacturer's published torque rating was used for the preliminary product selection.

source: https://www.mcmaster.com/6208K569/


### Section 4- Frame Twist and T-Slot Connector Design

For the frame connections, we proposed heavy 40 Series aluminum T-slot framing with an 80 × 40 mm top profile and a preliminary support spacing of 400 mm. We analyzed the vertical reactions and twisting moments produced by the two motors to determine the loading that must be resisted at the frame connections. Symmetric loading and equal sharing of the motor reaction torques were assumed for the preliminary analysis


#### Knowns & Unknowns

<img width="1180" height="1116" alt="image" src="https://github.com/user-attachments/assets/791174bf-200c-4a9b-bde5-e34d6a06fa72" />


<img width="1178" height="636" alt="image" src="https://github.com/user-attachments/assets/aecfa39e-8286-48fb-abe2-93e0b0be73f0" />


#### FBD & handwritten calculations


<img width="828" height="909" alt="image" src="https://github.com/user-attachments/assets/245533e1-fb57-40da-bc72-afedc4ad5f3e" />


<img width="1642" height="1336" alt="image" src="https://github.com/user-attachments/assets/219d6b6a-ebe8-4ea9-abd3-1f0b200381f4" />


<img width="3070" height="1620" alt="image" src="https://github.com/user-attachments/assets/72ee13ea-b775-456d-be89-281590ef3c3d" />


<img width="2118" height="1524" alt="image" src="https://github.com/user-attachments/assets/59fcf3ac-ba3d-4536-93d1-99928e7db4ed" />


We selected the 80/20 Gusseted Inside-Corner Bracket, Grainger Item #5JRU3 (manufacturer model 40-4338), as our preliminary frame connector. The bracket is compatible with 40 Series T-slot framing and has eight mounting holes, allowing multiple fastening points. Its gusseted design was chosen to provide additional rigidity at the connection between the top beam and vertical supports. Grainger also lists a compatible M8 bolt and T-slot nut assembly, Item #5JRH6

The preliminary analysis gave vertical reactions of 1000 N and torsional reactions of 5.44 N·m at each support under the assumed loading conditions. The manufacturer's drawing confirmed a 40 mm spacing between mounting-hole columns, which was used as an assumed effective lever arm to calculate a 136 N force couple. The final fastener forces and connector capacity still require verification based on the actual bracket arrangement and loading direction

sources: 

Grainger product page: https://www.grainger.com/product/80-20-Inside-Corner-Bracket-Gusseted-5JRU3

Grainger dimension drawing:  https://www.grainger.com/ec/pdf/grainger-5jru3.pdf

### Lessons Learned 

Through this assignment, I learned how to apply bearing stress, torsional shear stress, and equilibrium equations to the design of mechanical components. I also learned that theoretical minimum dimensions are not always the most practical choices, since rigidity, alignment, assembly, and manufacturer specifications must also be considered. This assignment helped me understand how the motor mount, coupler, and frame connections work together in the tensile testing machine.


**_Time spent: 5 hours_**




## Member 3: Bridget Fagan

## Objective

The objective of this part of the assignment was to conduct simulations on the tensile tester assembly to verify that the assembly would survive its application. To do this, we had to apply meshes of three different sizes to the model and run the same study for convergence. The entire frame is made from aluminum with the exception of the steel lead screws.

## Analyze

### Section 5

#### Model Setup

Part 5 required the testing of the top of the frame against the applied torque from the motor as well as the axial force through the lead screws. To set up the model, I removed the crosshead assembly including the nut and flange and the lead screws. The crosshead assembly does not affect the results of the study, and the lead screws do not mesh correctly in coarser sizes. To get around this, I removed the lead screws and instead applied the axial force around the rim of the hole the lead screw was in. The hole has a sharp corner, and from the results of my first study with a coarse mesh, the maximum stress occurred at those corners. This would be concerning if not for the fact that the lead screw is not directly mounted to the top of the frame in the way that is described. The feet of the frame and the faces of the frame top were fixed as shown to provide more accurate results in the analysis. I conducted the study this way to understand the worst possible case of loading, and I found that the maximum stress was within the elastic region for aluminum.

#### Meshing and Results

I tested each size of mesh for convergence using the following table:


#### Optimization Suggestions

To optimize the model of the frame top, I would suggest adding fillets or chamfers around the holes in the rail. This will reduce stress around the hole and prevent edge degradation through use. To reduce the large deflection in the center, I would install the gusseted brackets discussed in Part 4 between the top rail and side rails to increase the support from the ends.

## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate

### Lessons Learned

A major holdup of this part of the project was the software itself. I had to keep troubleshooting issues with Solidworks for days before I could even run the FEA studies. Even during the FEA, the software would suddenly freeze the analysis for over an hour and refuse to continue. I still don't know what caused this issue, I have never experienced it before, however I did learn a lot about troubleshooting meshes and simulation errors.
