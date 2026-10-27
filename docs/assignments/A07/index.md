# A7 – Bracket FEA

## Objective

The objective of this assignment is to use the Finite Element Method of analysis to perform studies on our previously built bracket design using CAD. Analyses in this assignment will help the student understand the optimization steps of the engineering design process. We will perform analyses on stress and deflection, as well as change the driving geometry of the model to optimize the design.

## Analyze

My analysis of the design is performed in two loops. The first loop illustrates a change in the model geometry. Each change in geometry will be in response to the results of the second loop: FEA. Each FEA loop will be run three times, using different size meshes, and will be checked for convergence. Each loop will be run no more than three times. The first loops will be documented in a table like the following: 

<img width="413" height="89" alt="Outer Loop Blank A7" src="https://github.com/user-attachments/assets/cdfeb845-371a-4c53-8515-db14ec84656c" />


The second loop will be documented on the following table and checked for convergence:

<img width="335" height="74" alt="Inner Loop Blank A7" src="https://github.com/user-attachments/assets/0abf344c-cca4-45d0-b252-6cd8c3f220e8" />


**Iteration 1:**

Iteration 1 uses the initial geometry of the model after A6, therefore there are no geometry changes to commit. 

The constraints shown in the following picture are used across every iteration, with the pink arrows representing a force of 600 N and the green arrows representing a constrained face.

<img width="403" height="266" alt="Screenshot 2026-10-26 174848" src="https://github.com/user-attachments/assets/f93b8fc3-624a-4561-b4fa-c05127bd2c3f" />

The FEA study of Iteration 1 yielded the following results:

<img width="319" height="65" alt="Screenshot 2026-10-26 182733" src="https://github.com/user-attachments/assets/4dbd0b68-2dd2-474d-8b17-bff2e0ad14c8" />

Adding a finer mesh increased the calculated stress as well as strain, and decreased the safety factor, as expected. Based on these values, I determined that the connection between the strap support and its connector had the highest stress concentration.

**Iteration 2:**

Iteration 2 involved removing the stress concentration from the connection between the strap support and its connector. To eliminate this, I added a 0.05 inch fillet to the connection. After the analysis, the Factor of Safety went far down. This happened because I also decreased the diameter of the cylinder that holds the strap by a significant amount. The second iteration yielded the following results: 

<img width="328" height="74" alt="Screenshot 2026-10-26 200123" src="https://github.com/user-attachments/assets/87572716-cb36-4b2f-a194-cfb8840ee325" />

**Iteration 3:**

In iteration 3 I tried to increase the safety factor, mainly by increasing the width of each of the elements on the top of the bracket. I noticed that it did increase the safety factor, however not as much as I would have liked. Given another iteration, I would increase the dimensions again until a safety factor of 4 was reached again. The third iteration yielded the following results: 

<img width="326" height="70" alt="Screenshot 2026-10-26 200400" src="https://github.com/user-attachments/assets/744b6edf-67f4-4d05-8b02-1e3fd8aecc13" />


The final first loop table has the following data: 

<img width="453" height="77" alt="Screenshot 2026-10-26 200846" src="https://github.com/user-attachments/assets/c3d68d75-bba2-4240-80da-9b3824be964b" />

I noticed that the factor of safety fell significantly in each iteration, and the mass doubled with the increase in element size. Deflection also increased significantly due to the reduction in diameter of the cylinder. The maximum stress increased as well as a result of the reduction in diameter, however the fillets helped mitigate the damage.



## Communicate

**Reflection**

This assignment helped me understand the optimization process for solid materials. In my experience, I had only been working on surfaces and hydraulic profiles, with no regard for the solid mechanics of each model. Any time spent in CAD, I consider to be valuable, so while this assignment fell in my realm of prior knowledge, I was able to refine my CAD skills and increase my speed and understanding. In total, this assignment took 3 hours to complete. Most was spent editing the model properties to optimize the design. 
