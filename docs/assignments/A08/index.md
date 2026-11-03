# A8 – Gears

## Objective

The objective of this assignment is to design a gearbox around two gears rotating on separate shafts. The assignment will involve calculations to determine the strength through torque of the shafts, input and output power, and fit connections. The following design parameters are given:

- Gear Ratio: 24:9
- Output Torque: 1.25 in-lbf
- Output Speed: 1100 rpm
- Pinion shaft diameter: .125 in
- Gear shaft diameter: .25 in
- Pinion/Gear shaft length: 1 in

Along with these design parameters, there are a few assumptions to be made. Namely, we must assume that the gear train is ideal and the moment created from the interference of the gears is ignored.

## Analyze

### Part A: Input Shaft

The input shaft was given to have a diameter of .125 in. The goal of this section of the assignment was to determine if a diameter of .125 in was sufficient to keep the material in tact while spinning. It was assumed from the Machinery's Handbook page 295 Table 2 that the maximum torque stress of a shaft made of commercial steel undergoing pure torsion was 8000 psi. After calculations, I determined that the diameter of .125 in was indeed sufficient.

<img width="2738" height="1174" alt="IMG_4584" src="https://github.com/user-attachments/assets/9ed370ae-ac5a-419b-9992-240ad5f61e03" />

### Part B: Output Shaft

The output shaft process was similar to the input shaft with a few key differences. The input shaft was assumed to be a power-transmitting shaft, therefore requiring an equation that factored in the combined shock and fatigue factor K. The output shaft, however is simply a short shaft, which requires a simpler equation. It was also determined that the given diameter of .25 in was sufficient to transmit the required torque.

<img width="2724" height="678" alt="IMG_4584 (1)" src="https://github.com/user-attachments/assets/c58be63e-191e-4082-9016-15bfc5ac310f" />

## Decide

### Part C: Journal Bearings

Part C required me to choose a length and size of the journal bearings to be used, as well as the pressure, velocity and PV rating. Through my calculations I encountered roundoff error, meaning that my final values are likely not precise. However, I selected the material to be Dry Graphite. 

<img width="2749" height="1992" alt="IMG_4584 (2)" src="https://github.com/user-attachments/assets/3a2dd688-d855-4336-a09d-065db1ddac72" />

### Part D: Bearing Thickness

In part D, I calculated the required thickness of the bearing to be 0.0625 in for both the input and output shaft bearings. What I found interesting was the the material selection had nothing to do with the thickness calculations, it was all dependent on the diameters of the bearings. 

<img width="2874" height="1967" alt="IMG_4582" src="https://github.com/user-attachments/assets/78f74ed6-71c2-49e2-804d-e2b7dc67b720" />

<img width="1580" height="1087" alt="IMG_4582 (1)" src="https://github.com/user-attachments/assets/17db4e52-faac-4f46-9eac-5d05d667b9ca" />

### Part E: Component Selection

Part E required using the McMaster-Carr website to locate the bearings and shafts that I decided to use. 

I chose the Graphite Lubricated Bearing with part number: 7943K22

### Sketch

The sketch of my gearbox housing design requires four bolts to hold together, one on each side. It will be made of two identical parts with flanges to connect the two sides. As this gearbox is small, the housing will likely be made of plastic, with the bolts also being made of a low density plastic. 

<img width="3024" height="1814" alt="Image (2)" src="https://github.com/user-attachments/assets/fecb2044-3bb6-4e6e-b6b8-423336816626" />

### CAD Model

Click https://github.com/bfagan2/megr2156-portfolio/raw/refs/heads/main/A8.SLDPRT to download the CAD file.

## Lessons Learned

Throughout this assignment I struggled with finding the right equations to use. In my experience, I have never encountered a design problem similar to this so I felt in the dark about where to start. I deepened my understanding of the Machinery's Handbook and was able to use it to find my way through the assignment. Modeling in CAD, as always was the simple part.
