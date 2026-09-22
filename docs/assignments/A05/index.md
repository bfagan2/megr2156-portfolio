# A5 – Bracket Design

## Objective

Design a rigid T-Beam bracket to hold a [U-Line strap]([url](https://www.uline.com/Product/Detail/S-12925/Poly-Cord-Strapping/Heavy-Duty-Polyester-Cord-Strapping-3-4-x-2500?pricode=WA9239&gadtype=pla&id=S-12925)) by analyzing both stress and stiffness. 

## Analyze

Design using a safety factor of 4 and applied load in between 500 lbf < F < 800 lbf. Choose one of three metals, aluminum 6061 T6, Steel (ASTM A36), or Titanium (Ti-6Al-V4). Furthermore, state assumptions and approximations about the design in order to use fundamental strength of materials analysis. For example, use the proper stress analysis and deflection analysis where appropriate. Assume no failure due to direct shear stress. 

## Design

Aluminum 6061 T6 was used in the design of this bracket due to its low material density and high strength to weight ratio. The design for this bracket is not particularly heavy-duty, so a lightweight aluminum alloy should suffice for this application while keeping manufacturing costs down. Aluminum is easy and cheap to manufacture while still maintaining high material strength.

### Step 1

The first step was to detail the overall shape of the bracket and determine the minimum geometric dimensions for each element. The bracket was split into 5 elements, labeled on the image below. Each element was individually analyzed and used to constrain the design of the next element. 
<img width="3024" height="4032" alt="Page 1" src="https://github.com/user-attachments/assets/4b72ad8d-86e9-4eb0-a06d-544793426e38" />
To start the dimensioning, a stress analysis was performed for each element using the fundamental equation for stress. Using the overall geometry, I was able to constrain each element to the next one in the sequence based on how they were mated together. Shown below are the hand calculations performed for the stress analysis.
<img width="1500" height="2000" alt="Page 2" src="https://github.com/user-attachments/assets/188f6ddd-1ee3-410b-a281-cc3280c47dc7" />
<img width="1500" height="2000" alt="Page 3" src="https://github.com/user-attachments/assets/51ae9332-1a05-4002-9a12-3cb02bed415d" />

### Step 2

Step 2 involved performing the same recursive algebraic analysis for each element, this time for stiffness. The maximum deflection allowed for each element was given as 0.005". Once again, using the dimensions for each element allowed me to constrain the elements together to make the analysis easier. Shown below are the hand calculations performed for the stiffness analysis.
<img width="3024" height="4032" alt="Page 4" src="https://github.com/user-attachments/assets/df244700-09e7-49c3-899a-1c3a37b1d606" />
<img width="3024" height="4032" alt="Page 5" src="https://github.com/user-attachments/assets/4bb23c44-2a22-4199-bae1-5fed536bd1b2" />

### Step 3

Step 3 involved creating hand sketches and comparing the allowable dimensions for each element based on their respective analyses. It was interesting that the stiffness calculation did not always yield a smaller dimension, rather the overall difference from the dimension derived from the stress analysis was similar on either side. Please note that the sketches shown below are not a scale representation of the values solved for, but rather a visual representation of the differences between each analysis result.
<img width="3024" height="4032" alt="Page 6" src="https://github.com/user-attachments/assets/6a964c6f-39b9-4100-a1e2-7eeb2444dd16" />

## Lessons Learned

In total I spent around 4 hours on this assignment. What I learned was that high stress and high deflection are not mutually inclusive. Rather, the individual geometry of the elements is what defines the stiffness and stress distributions. I did get caught on the fact that the dimensions found during my stiffness analysis were comparatively small, but that is due to aluminum's high elasticity. If I chose a different material with a lower elasticity, the results would have been larger numbers. For the most part, the stress analysis is the driving factor for the geometry of these elements. The stiffness analysis yielded smaller numbers than the stress analysis, meaning that the material would experience more stress than deflection. 
