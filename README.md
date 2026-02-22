# TASK 1 INTRODUCTION TO AERODYNAMICS AND AIRCRAFT STRUCTURES :
**Objective :**\
1.Understand Bernoulli's Principle, Newton's Third Law, and aerodynamic forces.\
2.Explain lift, drag, thrust, weight, and aircraft stability.\
3.Learn about primary and secondary control surfaces.\
4.Study basic components like the pitot tube and radio altimeter.\
**Learnings and Outcomes :**
### BERNOULLI'S PRINCIPLE IN AVIATION :
**Bernoulli's Principle states:** Fast-moving air has low pressure, and slow-moving air has high pressure.\
This principle is the magic behind how an airplane wing generates lift, the force that pushes the plane up.\
**Significance in Aircraft lift**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/0c7f6273d37e0da735d15a9f3e5977cd0d0bddcf/WhatsApp%20Image%202025-10-26%20at%204.05.57%20PM.jpeg)\
 The significance of Bernoulli's Principle is that it explains the fundamental pressure difference that, along with Newton's 3rd Law, creates the necessary lift for everything from a massive jumbo jet to a small drone.
### NEWTON'S THIRD LAW OF MOTION IN AVIATION :
Newton's 3rd Law of Motion, is stated as "for every action, there is an equal and opposite reaction," is fundamental to understanding how aircraft generate lift and propulsion.\
 In aviation, this law is crucial for explaining how forces are created to enable flight.\
 **Significance :**\
 ​1. Generating Lift:\
*​Action: An aircraft's wings (or helicopter blades) are designed to push air downwards.\
*​Reaction: The air, in turn, pushes the wings (or blades) upwards with an equal and opposite force. This upward force is what we call lift, which directly opposes gravity and allows the aircraft to become airborne. The shape of the wing, called an airfoil, is specifically designed to create this downward push of air.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/b5d0794ad4f289cfa6ea151edefc2f1c4c29b556/WhatsApp%20Image%202025-10-26%20at%202.26.30%20AM.jpeg)\
2. Producing Thrust:\
*​Action: Jet engines and propellers work by expelling a mass of air (or exhaust gases) backward at high velocity.\
*​Reaction: The expelled air/gases push the engine and, consequently, the entire aircraft forward with an equal and opposite force. This forward force is known as thrust, which overcomes drag and propels the aircraft through the air.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/77dff0e0295665d5700269ab6ac8b4ca78062063/WhatsApp%20Image%202025-10-26%20at%202.00.46%20AM.jpeg)\
3.Helicopter Anti-Torque Systems:\
*Action (Main Rotor): The main rotor blades of a helicopter push a large volume of air downwards to create lift. However, as the blades spin in one direction, they also impart an opposite rotational force (torque) on the helicopter body.\
*Reaction (Tail Rotor/Other Systems): To prevent the fuselage from spinning uncontrollably, a tail rotor (or other anti-torque systems like NOTAR, coaxial rotors, etc.) performs an "action" by pushing air sideways. This creates a "reaction" force that counteracts the main rotor's torque, keeping the helicopter stable and allowing it to control its heading (yaw).\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/65b6b3663a48e301ee1c9754ad13aa9e35c485d0/WhatsApp%20Image%202025-10-26%20at%202.12.21%20AM.jpeg)\
4. Control Surfaces (Ailerons, Elevators, Rudder):\
*​Action: When a pilot moves a control surface (like an aileron on the wing, an elevator on the horizontal stabilizer, or a rudder on the vertical stabilizer), it deflects the airflow around it.\
*​Reaction: This deflection of air creates an equal and opposite force on the control surface, which then causes the aircraft to pitch up/down, roll, or yaw. This allows for precise control of the aircraft's attitude and direction of flight\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/f36b26e5a642455b56d8f5dc87a6a45375b4a4ef/WhatsApp%20Image%202025-10-26%20at%202.08.36%20AM.jpeg)\
*NOTE*\
**Bernoulli: Creates lift by "pulling" the wing up from above (low pressure).**\
**Newton: Creates lift by "pushing" the wing up from below (deflecting air down).**
### DIFFERENCE BETWEEN UAV & UAS:
*UAV (Unmanned Aerial Vehicle)* refers to the flying object alone, like the drone.\
*UAS refer (Unmanned Aerial System)* refers to the complete aerial system i.e., it includes the drone, payload, control system etc.
### BASICS OF DRONE SCIENCE:
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/24aaa2e11bbfd768ecc92b28eec2b413665f4c82/WhatsApp%20Image%202025-10-26%20at%203.25.29%20AM.jpeg)
### QUAD X FLIGHT DYNAMICS:
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/539efb3934582346442403538d50f3e34ef18c58/WhatsApp%20Image%202025-10-26%20at%203.34.01%20AM.jpeg)\
**DRONE COMPONENTS IN UAS:**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/44cc74f31e1bb47c30400ec339c696dac02e9332/WhatsApp%20Image%202025-10-26%20at%2012.18.19%20AM.jpeg)\
1.​Core: The Flight Controller (FC) is the "brain," powered by a LiPo Battery.\
2.​Propulsion: The FC sends signals to ESCs, which control the speed of the motors.\
3.​Control: The pilot uses a Radio (TX) to send commands to the drone's Receiver (RX).\
4.​Navigation: A GPS provides location data, and an OSD overlays flight info onto the video.\
​5.FPV System: An FPV Camera sends a live video feed via a VTX to the pilot's Goggles.\
​6.HD Recording: A separate HD Camera, steadied by a Gimbal, records high-quality footage.\
**SENSOR UNIT:**\
a. Inertial Measurement Unit (IMU):\
It's a sensor system that measures the drone’s orientation, acceleration, and angular velocity. It helps the flight controller understand how the drone is moving and correct its position in real time. The 2 main sensors which fall under IMU are:\
*Accelerometers:* Measures the linear acceleration (linear motion) and force exerted on the drone in X, Y, Z axes.
Accelerometers no not report current speed, they report only the acceleration in a direction.\
*Gyroscopes:* Measure angular velocity (rotational motion) around X, Y, Z axes.
Gyroscopes do not report the current angle, they report only the rate at which the device turns.\
b. Barometer: \
As the altitude increases the atmospheric pressure decreases, so pressure sensors like barometers help us give information about the altitude of the drone.\
**FREE BODY DIAGRAM OF INCLINED DRONE:**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/a876e88ec6c1a2fdc45e5e51594edd95b00073e9/Screenshot%202025-10-26%20040137.png)\
Here, the weight of the drone is 1KG. Therefore, the minimum required thrust being 10 N, the external thrust given by the RC is also 10 N. Since, the drone is inclined at an angle of 45° wrt ground, the vertical component would be 10 Sin 45 = 7 N & horizontal component being 10 Cos 45 = 7 N. Since the 7 N of vertical force isn't sufficient to counteract the 10 N of gravity acting on the drone, the drone won't fly. The minimum required thrust in this case would be 14 N only then the vertical component would get 10 N of force, which is the minimum required force for the drone to hover.
### FOUR BASIC FORCES OF AVIATION:
*Four physical forces: lift, drag, weight, and thrust.*\
For flight, an aircraft's lift must balance its weight, and its thrust must exceed its drag. A plane uses its wings for lift and its engines for thrust. Drag is reduced by a plane's smooth shape and its weight is controlled by the materials it is constructed of.\
1.*Lift (L)* is the upward force that opposes weight and is produced mainly by the aircraft’s wings. It is generated because air moves faster over the curved upper surface of the wing and slower below, creating a pressure difference as explained by Bernoulli’s Principle. The lift can be calculated using the formula:\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/334de38f1409e7a5f239265b3014af81b8346042/WhatsApp%20Image%202025-10-26%20at%204.50.57%20PM.jpeg)\
2.*Weight (W)* is the downward force caused by gravity acting on the aircraft’s mass, given by\
W = mg\
3.*Thrust (T)* is the forward force produced by engines or propellers that moves the aircraft through the air. It must overcome drag for acceleration and steady flight.\
 F=mg\
4.*Drag (D)* is the backward or resisting force caused by air friction and pressure differences around the aircraft body. The drag force is calculated as:\
 ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/d2cbe05380e646e75621f1b20ae8405157cd4a20/image.png)
### CONCEPT OF LIFT:
 Lift is the product of air we're moving through and deflecting it downward.If we deflect more air downward more lift we produce.\
 FORMULA
 ![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/8d14539db5dce2052bdda42d135f6b9f6bb08eee/Screenshot%202025-10-26%20233223.png)\
 The Four Factors That Create Lift:
C_L (Coefficient of Lift): This represents how effective the wing is at creating lift . It's determined by the wing's shape (like its camber) but is most importantly controlled by the pilot changing the angle of attack. Increasing the angle of attack (pitching the wing up) deflects more air down, increasing the coefficient of lift .\
ρ (Rho - Air Density): This is a measure of how many air molecules are in a given space . Denser air (lower altitudes, colder temperatures) means there are more molecules for the wing to push down, which creates more lift.\
V (Velocity): This is the aircraft's true airspeed .The faster the aircraft moves, the more air molecules it deflects per second, which increases lift.\
S (Surface Area): This is the size of the wing. A larger wing can affect a larger swath of air compared to a smaller wing allowing it to generate more lift .\
A pilot can change only velocity and coefficient of lift.\
To keep lift constant, if Velocity decreases, the Coefficient of Lift (angle of attack) must increase . The same is true in reverse when accelerating.
### FLIGHT CONTROL SURFACES:
**PRIMARY CONTROL SURFACES :**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/98e188e115da340b364b5732eed7de5fee67127e/WhatsApp%20Image%202025-10-27%20at%2012.10.09%20AM.jpeg)\
**SECONDARY CONTROL SURFACES :**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/69b280d1156e89b12b6aeec826c7277df434616e/WhatsApp%20Image%202025-10-27%20at%2012.15.43%20AM.jpeg)
### BRIEF ABOUT PITOT TUBE AND RADIO ALTIMETER :
**Pitot Tube:** A sensor that measures airspeed by comparing incoming ram air pressure with static air pressure.\
**Radio Altimeter:** A device that measures an aircraft's exact height above the ground by bouncing radio waves off the terrain.\
![image](https://github.com/tejashreehn610-blip/Level-1-report/blob/main/Gemini_Generated_Image_otzme3otzme3otzm.png?raw=true)
# TASK 2 UNDERSTANDING AND DESIGNING AN AIR FOIL:
**Objective :**
* Understand the fundamentals of an Aerofoil, terms associated with it, the nomenclature, concept of turbulence.
* Use Fusion 360 to model an NACA 4412 air foil of 100 mm chord length & 160 mm air foil span, in Fusion 360 using DAT to Spline/Canvas tool.
* Simulate lift and drag at 25 m/s wind speed to ensure at least 5N lift, use Autodesk CFD for simulation. (Compare with 2 materials, composite based air-foil & wood based air-foil), also state the Angle of Attack in your report.

**Learnings and Outcomes:**
### Basic Aviation terminology:
* Airfoil: Any structure designed to produce lift; while wings are the most common example, propellers are also considered airfoils, generating thrust (forward lift).
* Leading Edge: The very front part of an airfoil.
* Trailing Edge: The rear end of an airfoil.
* Chord Line: An imaginary straight line connecting the leading edge to the trailing edge of an airfoil.
* Camber: The curvature of an airfoil, consisting of the Upper Camber (top surface), Lower Camber (bottom surface), and Mean Camber (the average of the two).
* Wingspan: The total distance from one wingtip to the other.
* Wing Area: Calculated by multiplying the average length by the average width of the wing.
* Planform: The shape of the wing as viewed from above.
* Aspect Ratio: The ratio of the wingspan to the wing chord; gliders utilize high aspect ratios for reduced drag, while fighter jets use low aspect ratios for high maneuverability.
* Angle of Incidence: The angle between the chord line and the longitudinal axis of the aircraft, typically fixed for optimal takeoff speed.
* Relative Airflow: The airflow with respect to the wings, opposing the aircraft's true motion.
* Angle of Attack: The angle between the chord line and the relative airflow, determining many operational limits.\
here are the images of each and every technology to understant the terminologies visually.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/4863d8f5b29880b19d5616c5007122035d865be9/WhatsApp%20Image%202026-02-09%20at%209.12.52%20PM.jpeg)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/81e8cb84c2fc01c2e31d9691757daee214f13550/WhatsApp%20Image%202026-02-09%20at%209.20.07%20PM.jpeg)
### Airfoil Nomenclature:
For 4 digit\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/af54c68f1fcf2058488ee90b68a50104ea9d34e8/Screenshot%202026-02-09%20225610.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/8387b265480f4d10ba6f261e9ade44e214e62bec/WhatsApp%20Image%202026-02-09%20at%2011.53.38%20PM.jpeg)\
below you can watch the mindmap and understand how nomenclature is done for 4, 5 & 6 digits\
[click here](https://youtu.be/QG9Ft9BPh8Y)\
**Turbulence:**\
Turbulence occurs when airflow separates from a surface, forming a low-pressure wake with swirling vortices behind the object.
#  TASK 3 BASIC UAV ASSEMBLY & COMPONENT FAMILLIZATION :
**Objective :** \
To understand and identify essential UAV components and their compatibility.\
Identify and understand flight controllers (Pixhawk, APM), ESCs, motors, propellers, and battery management.\
Learn about LiPo, Li-ion, and NiMH batteries, their charge cycles, and safety.\
List all the components required to build a quadcopter with a minimum thrust-to-weight ratio of 3:1, each of the components should be compatible with each other.\
Perform manual pen-and-paper calculations for flight time and thrust-to-weight ratio using component datasheets
Use E-Calc to verify the results.\
**Learnings and Outcomes :**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/58998bf0dc17d50699086910c76bad7c8aa473e6/WhatsApp%20Image%202026-02-22%20at%206.24.00%20PM.jpeg)
### Inertial Measurement Unit (IMU)

The IMU is crucial, combining three important sensors:

* **Accelerometers**: These MEMS sensors measure linear acceleration and gravity along three axes (X, Y, Z). They contain a tiny proof-mass attached to springs; when the drone experiences force, the mass moves, changing the capacitance between it and fixed plates, which is converted into an electrical signal. This helps determine the drone's orientation and detect roll and pitch.
* **Gyroscopes**: These MEMS sensors measure angular velocity, or the rate of rotation, around the drone's axes (yaw, pitch, roll). They operate based on the Coriolis effect: a vibrating mass deflects when rotated, and this deflection indicates the angular rate via capacitance changes. Gyroscopes are essential for maintaining drone stability and compensating for disturbances.
* **Magnetometers**: Although not explicitly detailed, magnetometers are usually part of the IMU and detect magnetic fields, primarily Earth's magnetic field. They provide a compass function for navigation and maintaining heading.

### Barometer Sensor

A MEMS-based barometer sensor is used to determine the drone's altitude by measuring atmospheric pressure. It features a flexible membrane that deflects in response to pressure changes, which capacitance sensors then measure.

### Sensor Fusion for Accuracy

* **Challenge**: Sensor signals can be affected by noise due to defects, mechanical vibrations from propellers, and magnetic interference.
* **Solution**: Modern drones use **sensor fusion** to overcome these issues. This involves combining data from different sensors, like GPS and IMU, and integrating technologies like radar to produce more accurate measurements.

### Decision-Making: Control System and Algorithms

* **Control Logic**: Accurate sensor signals are fed into the drone's control system, which includes control logic and algorithms to reduce errors and make decisions.
* **Kalman Filter (KF) Algorithm**: One such algorithm is the Kalman Filter, which reads past and present data to understand the drone's state. It uses its logic for GPS navigation, returning home, and stabilizing the drone against external factors like wind.
* **Motor Control**: The KF algorithm, embedded in the processor, makes smart decisions to control the speeds of the Brushless DC (BLDC) motors, enabling the quadcopter to handle challenging environments.

### Leading Drone Companies

**DJI** is highlighted as a leading company in the consumer drone market, known for its advanced flight control algorithms, dual IMUs for reliability, and vibration dampening systems. Other companies like **Parrot**, **Autel**, and **Yuneec** are mentioned as alternatives in the market.

### Power and Communication

* **Power Source**: Lithium-ion batteries supply power to the BLDC motors, electronic circuits, antennas, and sensors.
* **Control Signal**: Drones receive control signals from the user via common radio frequency technology, with a communication range of one to two kilometers for consumer drones.

### Lost Drone Recovery: GPS and Internet Technology

* **Return Home Feature**: If a drone travels out of communication range, modern drones use GPS and tower-based internet technology to return to a pre-set home location.
### MOTOR NOMENCLATURE :
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/2227006de4f3c922920eff7009c30501d39788fe/Screenshot%202026-02-22%20184006.png)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/2bf863e27fc916a15cceef1f0a7cd1badc7efc0c/Screenshot%202026-02-22%20184301.png)\
**MATERIAL SELECTION :**\
For the drone frame, carbon fiber was selected due to its exceptional strength-to-weight ratio, rigidity, and resistance to deformation. It ensures the drone remains lightweight (frame weight: 400 grams) while being capable of withstanding mechanical stress during flight. Its non-corrosive properties make it ideal for long-term use in various environments.\
**COMPONENT SELECTION :**\
1.Motor\
Model: EMAX , Ecoll 2814_730(730)\
Justification: This motor provides a balance between efficiency and power, ensuring sufficient RPMs for stable hover and maneuverability.\
2.Propellers:\
Type: Generic 10-inch with a 4.7-inch pitch\
Justification: Optimized for high efficiency and compatibility with the motor, ensuring adequate thrust.\
3.Battery:\
Type: LiPo 2200mAh, 3S\
4.ESC (Electronic Speed Controller):\
Type: 20A max ESC\
Justification: Matches the current and voltage demands of the selected motor, providing reliable control without overheating.\
5.Frame:\
Material: Carbon fiber (weight: 760 grams)\
Justification: Lightweight and durable, enhancing stability and endurance.\
### RESULT FROM eCalc :
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/4cd817d06505841494d1729e225112c0dd7b047d/Screenshot%202026-02-22%20195959.png)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/9185c016158e905d631d17be4710fd8ed95bcb54/Screenshot%202026-02-22%20200031.png)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/f6b705bf45c68e2bb6d517a9b9c7e309831d7038/Screenshot%202026-02-22%20200050.png)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/9524d8c775c7191e68d5cd21259ee9019e732a87/Screenshot%202026-02-22%20200100.png)\
GOT THE THRUST TO WEIGHT RATIO - 3.1\
**MANUAL CALCULATION :**\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/cb474fdcf23a12851ceebe241b97925815fedbad/WhatsApp%20Image%202026-02-22%20at%2010.26.05%20PM.jpeg)
# TASK 4 PROPELLER BLADE DESIGN AND STIMULATOR :
**Objective :**\
 To understand propeller fundamentals and simulate its aerodynamic performance.\
**Learnings and Outcomes :**\
Propellers are essential components in drones, converting rotational motion into thrust to enable flight. For this task, the objective was to design a toroidal propeller capable of generating a lift of approximately 9 Newtons. Both clockwise (CW) and counterclockwise (CCW) propellers were designed to ensure stability and functionality. The propellers were modeled using the Autodesk Fusion 360 .\
**Drone Propellers Function and Working :**
* Purpose: Propellers generate thrust by creating a pressure differential between the top and bottom surfaces of the blade. This allows drones to ascend, descend, and maneuver.
* Mechanics: The rotation of the propeller blades causes airflow. The angle of attack and blade shape dictate how much thrust is produced.
CW and CCW Propellers: To counteract torque (rotational force), drones use pairs of propellers rotating in opposite directions.
* Labeling: Propellers are often marked with dimensions like 5045 (5-inch diameter, 4.5-inch pitch). The pitch refers to how far the propeller would travel in one rotation if it were moving through a solid medium.
* Orientation: CW propellers are mounted on motors rotating clockwise, while CCW propellers are for counterclockwise rotation.

**Step-by-Step Process in Fusion 360**\
**Design Workflow**\
1.Create the Base Profile:
* Open Fusion 360 and start a new design.
* Use the Sketch Tool to draw a 2D profile of the blade’s leading and trailing edges on the X-Y plane.
Ensure the blade's shape accounts for aerodynamic principles (e.g., a slight camber for lift generation).

2.Generate the Blade Shape:

* Use the Loft Tool to create a 3D blade by connecting the root and tip profiles of the blade.
* Apply a slight twist using the Form Tool to simulate the pitch angle, enhancing airflow efficiency.

3.Design the Hub:

* Create a cylindrical hub using the Revolve Tool. Ensure internal threading matches the motor shaft specifications.
* Include keyholes or flat sections to secure the propeller on the BLDC motor shaft.

4.Replicate for Multiple Blades:

* Use the Circular Pattern Tool to replicate the blade design around the hub, creating a toroidal configuration.

5.Final Adjustments:

* Smooth edges and surfaces using the Fillet Tool to reduce turbulence.
* Check dimensions against required specifications.

**Features Used in Fusion 360**\
1.Sketch Tool: For creating 2D profiles.\
2.Loft Tool: For transforming 2D sketches into 3D geometries.\
3.Revolve Tool: For creating symmetrical hub components.\
4.Circular Pattern Tool: For arranging multiple blades around a central axis.\
5.Fillet Tool: For smoothing sharp edges.\
6.Parameter Tool: To input and adjust specific dimensions dynamically.\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/7f81b3197eae345cbba9ee253019699744ff765b/WhatsApp%20Image%202026-02-12%20at%2010.12.33%20PM.jpeg)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/9fea0c8b075c5c982e4ba57601a15e2ef236dccf/WhatsApp%20Image%202026-02-12%20at%2010.12.33%20PM%20(1).jpeg)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/d3ec43ad508c36a8ec970d9f6fb8332af193c101/WhatsApp%20Image%202026-02-12%20at%2010.12.34%20PM.jpeg)\
# TASK 5 UNDERSTAND ABOUT ESC :
**Objective:** \
 To control the speed of a BLDC motor using Arduino UNO, ESC, and a potentiometer.\
 **Learnings and Outcomes :**
 1. Learnt about the BLDC motors.
 2. Learnt about the LiPo batteries.
 3. Learnt about ESC(electronic speed controller).

**Circuit design :**
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/d60b4f00acdfb317b211205cfe35d5c0ccdcba39/Screenshot%202026-01-18%20215642.png)\
**Overview :**
The circuit connections are made as shown about but while performing i used VRPS insted of LiPo battery.\
Lets us learn about the each and every complonets that we have used briefly!\
**BLDC MOTOR :**
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/ed5ea761f786d9da53e588cf22b5a0c4382846fc/WhatsApp%20Image%202026-01-18%20at%2010.33.10%20PM.jpeg)\
The motor i have used here is 1000KV. KV is nothing but RPM/V(no load).\
It works on the principle of magnetic attraction,repulsion and electronic commutation.\
These are power hungry and the most common method for powering them is using LiPo batteries.\
A Brushless Direct Current motor is an electric motor that uses electronic switching instead of brushes for rotation.The ESC supplies 3-phase AC to the stator, creating a rotating magnetic field that pulls the permanent-magnet rotor. Rotor (permanent magnets), stator (3-phase windings), and electronic controller (ESC).The motor needs AC to create a rotating magnetic field, so DC is converted into AC by the ESC.\
**LiPo Battery :**
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/ae23fc1b3c9c0d44558b6a7eb933227369f6425f/Screenshot%202026-01-18%20224938.png)\
By using LiPo battery we can give more power supply to BLDC motors.\
LiPo batteries are used in BLDC motors and drones because they are lightweight and compact.
They can deliver high current quickly, which BLDC motors require.
They have high energy density, giving longer run time.
They provide stable power output for smooth motor performance.\
**ESC :**
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/79150680ec234ea8b95a9784076cf72a4d694e32/Screenshot%202026-01-18%20230821.png)\
ESC (Electronic Speed Controller) is a device used to control the speed of BLDC motors.
It receives a low-power control signal (PWM) from a microcontroller like Arduino.
The ESC converts DC power from a battery into three-phase AC for the motor.
It controls motor speed by varying the switching frequency and duty cycle.
ESC also provides functions like motor arming, braking, and direction control.And even controles the motor.
Without an ESC, a BLDC motor cannot operate.\
**ARDUINO :**
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/d2dc9d01565c03439796ddcaa652ce57ee1c2418/Screenshot%202026-01-18%20231921.png)\
**POTENTIOMETER :**\
When a potentiometer is connected to an analog pin of a microcontroller (like Arduino or ESP32), it acts as a variable voltage divider. The ADC (Analog-to-Digital Converter) reads this voltage and converts it into a digital value between 0 and 1023 (for a 10-bit ADC). Now, The ADC value (0–1023) can be mapped to a PWM signal. This PWM signal is sent to an ESC to control speed.\
**IMAGE OF THE TASK PERFORMED IN  LAB :** 
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/002bb3c837cbea90c7ecd007ea78037b798c24d2/WhatsApp%20Image%202026-01-19%20at%2012.04.45%20AM.jpeg)\
**ARMING OF ESC :**\
When initially powering the motor, the signal value must be the same or lower than the minimum value of 1 millisecond. This is called arming of the ESC, and the motor makes a confirmation beeps so that we know that it’s properly armed.\
In case we have higher value when powering, which means we have a throttle up, the ESC won’t start the motor until we throttle down to the correct minimum value. This is very convenient in terms of safety, because the motor won’t start in case we have a throttle up when powering.\
Every ESC has its own high and low points, and they might slightly vary. For example, the low point might be 1.2 milliseconds and the high point might be 1.9 milliseconds. In such a case, our throttle won’t do anything in the first 20% until it reaches that low point value of 1.2 milliseconds. To solve this issue, we can calibrate the ESC or set the high and low points as we want.\
**ESC CALIBRATION :**\
ESC calibration is the process of teaching the ESC the minimum and maximum throttle values from your controller (Arduino, RC transmitter, etc.).
It ensures the ESC responds correctly to the full range of throttle signals\
**How to Calibrate an ESC:**\
1.Turn off the ESC and connect it to Arduino or transmitter.\
2.Set throttle to maximum (full 2000 µs PWM or full stick).\
3.Power on the ESC → you will hear some beeps .\
4.After beeps, move throttle to minimum (1000 µs PWM or stick down).\
5.ESC confirms calibration with another beep sequence.\
Now the calibration is done.\
**ESC Calibration = teaching ESC min & max throttle**\
[click here](https://youtu.be/tfgldrxWmf0) to check the video performed in the lab.
# TASK 6 RF COMMUNICATION IN UAVs
**Objective:**
* Learn about radio frequencies used in UAVs (2.4GHz, 5.8GHz, Lora).
* Understand the various security implications in the different wireless protocols used in drones, along with the emerging threats and ways of mitigation.
* Understand the procedure which goes behind the binding of an ELRS receiver.
* Bind the 2.4 GHz RP1 Rx with the TX 16S MK-ll.\
**Learnings and Outcomes:**\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/50370d921d2a90e306690b58990aac254bdef038/WhatsApp%20Image%202026-02-22%20at%2011.55.01%20PM.jpeg)
### RF Frequencies :
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/091ff36afe7a0a33ed6bd174c6702dd9627a7758/WhatsApp%20Image%202025-10-21%20at%204.26.04%20PM.jpeg)\
### LoRaWAN :
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/7cfec5aa63b90519296c5ef8f3b3f0a340cc3c56/WhatsApp%20Image%202026-02-23%20at%2012.03.42%20AM%20(2).jpeg)\
### PROTOCALS :
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/55b2f948449ac0c3619cc636f7528ab89b1f8346/WhatsApp%20Image%202026-02-23%20at%2012.03.42%20AM%20(1).jpeg)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/b4efc02ab96de81ebdbf23cad6ea8426b143e92d/WhatsApp%20Image%202026-02-23%20at%2012.03.42%20AM.jpeg)\
# TASK 7 BASICS OF PID :
**Objective :**
* Understand PID tuning for UAV stability.
* Learn how GPS Hold and Altitude Hold work, tabulate the differences between the two.
* Tabulate the differences between GPS Hold and Altitude Hold.

**Learnings and Outcomes :**\
Before going to the the PID system , lets 1st learn the basic control system of PID system.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/65e972bef962399039e3288c50635d949393e9bb/Screenshot%202026-01-25%20163558.png)\
**Control system :** Main job is to generate an apropriate actuating signal
so that the system produces the desired controlled variable.\
### BLOCK DIAGRAM OF PID SYSTEM:
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/7795f380c2bee59e50ca541c8dd4b1a8d3ea699d/Screenshot%202026-01-25%20180300.png)\
Explaination of PID is explained in my notes prepaired based on the resourse material provided\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/e69ad4d0c8ce4179f0eeaef826de74b5bfb70fa9/WhatsApp%20Image%202026-01-25%20at%206.25.24%20PM.jpeg)\
Here S.S.E is nothing but Steady State Error (SSE) in a PID controller refers to the difference between the desired output and the actual output after it has reached a steady state; it tells you how far the system is from the target after it has stabilized.\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/095e465d90b1f03ba4d11820915738e74d65ab58/WhatsApp%20Image%202026-01-25%20at%206.25.24%20PM%20(1).jpeg)\
![IMAGE](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/e16102852ac616726e8051a5173d5032c22b90d9/WhatsApp%20Image%202026-01-25%20at%206.33.52%20PM.jpeg)\
Below is the complete block diagram with formula\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/b1c4ddd9866facc0ca6f038a141d36ab17d2e95b/WhatsApp%20Image%202026-01-25%20at%205.56.18%20PM.jpeg)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/fc78446b7a7380bae917f3200065157e122796e3/Screenshot%202026-01-25%20184118.png)\
PID ANALOGY HAS BEEN STUDIED FORM THE RESOURSE MATERIAL PROVIDED\
### COMPARISION B/W GPS HOLD AND AltHold :
| Feature | GPS Hold (Loiter Mode) | Altitude Hold (AltHold) Mode |
| :--- | :--- | :--- |
| **Primary Function** | Maintains 3D position (Lat, Lon, and Alt). | Maintains vertical height only. |
| **Sticks Centered** | **Full Stop:** Locks in place even if wind pushes it. | **Drift:** Stays at height but moves with the wind. |
| **Sensors Used** | GPS + Barometer + IMU + Compass. | Barometer + IMU (No GPS needed). |
| **Wind Resistance** | **Automatic:** Actively fights wind to stay on point. | **Manual:** Pilot must counter-steer to stop drift. |
| **Safety Behavior** | "Panic" friendly; releasing sticks brakes the drone. | Maintains momentum; drone glides until manual braking. |
| **Environment** | Best for Outdoors with clear sky view. | Best for Indoors or GPS-denied areas (tunnels/forests). |
| **Drift Control** | Automatically stabilized via satellite data. | Requires constant manual correction for position. |
| **Precision** | **High:** Stays within a few centimeters. | **Moderate:** Only vertical precision is managed. |
| **Best Use Case** | Photography, Mapping, and "Parking" the drone. | Smooth cinematic shots and learning manual control. |

# TASK 8 DIFFERENT FIGHT MODES IN MISSION PLANNER :
**Objective :**\
To understand the various flight modes available in Mission Planner and their specific applications.\
**Stabilize Mode :**\
1.Does not require GPS.\
2.Offers total manual control over roll, pitch, and throttle.\
3.Uses values from level calibration to stabilize itself.\
4.Requires only a transmitter; no GPS or telemetry is used.\
5.Accurate level calibration is crucial for proper functioning.\
**Acro Mode :**\
Designed for advanced users, not beginners.
Provides manual control over roll, pitch, and throttle.\
If a stick is moved (e.g., pitch forward) and then released to the middle, the drone will maintain that angle and continue in that direction until an opposite input is given.\
Primarily for racing drones.\
High risk of crashes for beginners.\
Does not require GPS.\
**Altitude Hold Mode :**\
Popular for users without GPS or telemetry.\
Uses a barometer sensor to automatically control throttle and maintain altitude.\
Manual control over roll, pitch, and yaw is maintained.\
The drone will not gain height until the throttle is pushed above 50%; releasing it back to 50% maintains the current altitude.\
Offers good stability but can sometimes drift.\
Requires a transmitter and operates similarly to Stabilize mode, except for automatic throttle control.\
Can also use sonar for altitude sensing.\
**Auto Mode :**
Automatically controls everything based on a pre-defined mission.
Requires telemetry and GPS.\
Missions are programmed using Mission Planner (e.g., for aerial photography).\
The drone will follow a set altitude and speed to complete its mission.\
Can be set to land or return to launch (RTL) after mission completion.
The pilot can switch to another flight mode mid-mission; switching back to Auto will resume the mission from where it left off.\
Roll, pitch, and throttle inputs are ignored when in Auto mode; only yaw input is allowed for camera adjustment.\
**Guided Mode :**\
Requires radio telemetry.\
Enables the drone to fly to any dynamic target wirelessly via ground station applications.\
Maintains altitude using a barometer.\
To use, first switch to Stabilize mode, then fly to the desired location, then switch to Guided mode.\
**Loiter Mode :**\
The most popular GPS-enabled flight mode.\
Controls altitude similar to Altitude Hold, but allows lateral speed adjustment.\
Relies on GPS signal strength for better position holding and stabilization.
Uses the standard compass and GPS.\
**RTL (Return to Launch) Mode:**\
Returns the drone to its launch point and lands automatically.\
Requires GPS to record the home location.\
The drone gains a pre-set RTL altitude (e.g., 50 meters) before returning, even if it was flying at a lower altitude.\
Maintains altitude using barometer sensing.\
Can be configured to land or hover at a certain altitude upon return.\
**Circle Mode :**\
Good for videography and 360-degree views.\
Requires setting a circle radius and circling speed (degrees per second).\
If the radius is set to zero, the drone will spin in place.\
Can be set to circle clockwise or anti-clockwise.\
Does not use GPS.\
Altitude and yaw can be controlled, but roll and pitch inputs are ignored.\
The drone's nose always points towards the center of the circle unless manually adjusted with the yaw stick.\
**Land Mode :**\
Causes the drone to simply land at its current position.\
Landing speed can be adjusted.\
Automatically disarms and stops motors when it touches the ground, provided the throttle stick is at minimum.\
Useful for emergency landings when the battery is low or GPS is not being used.\
**Drift Mode :**\
An advanced flight mode, not for beginners.\
Provides direct control over roll and pitch.\
The autopilot controls roll and yaw to maintain heading.\
Altitude and roll cannot be directly controlled; the yaw stick becomes the roll control.\
Requires GPS.\
**Sport Mode :**\
In this mode, roll, pitch, and yaw stick inputs control the drone's rotation rate.\
When sticks are released, the drone maintains its extreme attitude.
Allows for maximum speed and aggressive flying.\
Altitude is controlled by Altitude Hold, and other controls by Stabilize mode.\
**Auto Tune Mode :**\
Automatically tunes the PID (Proportional, Integral, Derivative) values for the flight controller.\
Can also be done manually\.
**Position Hold Mode :**\
Similar to Loiter mode.\
Maintains a constant location.\
Can be armed in this mode.\
Requires GPS with a 3D fix (3D lock) and an HDOP (Horizontal Dilution of Precision) value less than 2.\
Automatically maintains altitude.\
**Brake Mode :**\
Requires GPS.\
Automatically stops the drone at its current position, ignoring pilot controls.\
Uses Loiter mode and GPS to hold position.\
To regain control, switch out of Brake mode.\
Distinguished from "Motor Emergency Stop," which completely cuts power and is dangerous.\
**Throw Mode :**\
A dangerous mode, not recommended for beginners due to injury risk.\
Used by advanced users to automatically start motors and maintain altitude when the drone is thrown.\
Uses Loiter mode and requires GPS.\
Ignores pilot controls until another flight mode is selected.\
Requires specific setup for throttle motor stop and next mode.\
**Avoid ADSB (Automatic Dependent Surveillance-Broadcast) Mode:**\
Requires additional components.\
An in-development technology for autonomous vehicle collision avoidance, specifically avoiding other aircraft like planes and helicopters.\
Useful for surveillance and mapping drones that fly in congested airspaces.
Still under development, so limited features are known.\
**Guided No GPS Mode :**\
Similar to Guided mode but does not use GPS.\
**Smart RTL Mode :**\
Different from standard RTL.\
Returns the drone to the launch point by re-tracing its exact flight path, including altitude and speed, rather than gaining a fixed RTL altitude.\
Records altitude at every position.\
Ideal for congested areas where a fixed RTL altitude might lead to obstacles.\
**Flow Hold Mode :**\
Uses an optical flow sensor to hold position without GPS.\
Often requires a downward-facing lidar (rangefinder) for better performance.\
Can sometimes exhibit instability or altitude fluctuations.\
**Follow Mode:**\
Enables the drone to follow another vehicle or object.\
Requires specifying the target's position offsets.\
Uses a rangefinder and telemetry system.\
Useful for capturing shots of moving objects like airplanes or cars.\
Uses GPS.\
**Zigzag Mode :**\
An autonomous flight mode that uses GPS.\
The vehicle moves forward, then backward, then slightly sideways, and then forward again, creating a zigzag pattern.\
Primarily designed for agricultural drones for tasks like pesticide spraying.\
**System ID Mode :**
Provides flight test data for creating highly accurate flight dynamic models.\
Uses flight test data.\
**Heli Auto Rotate Mode:**\
Specific to helicopters.\
Aids traditional helicopters in achieving good landings.\
**Air Mode :**\
Not a standalone flight mode but an integral part of Acro and Stabilize modes.\
Provides stabilization even at low throttle or when sticks are moved aggressively.\
Helps maintain stability and prevents the drone from drifting or wobbling.\
**Flip Mode :**\
Causes the drone to perform a direct flip (forward, backward, or sideways).\
Caution: Only use with carbon fiber propellers; plastic propellers are likely to break due to pressure.\
The drone flips once and then automatically reverts to its previous flight mode.\
Can be activated using channel 7 or 8 for safety, rather than directly on the flight mode switch.
# TASK 9 DGCA REGULATIONS:
**Objective :**
* Understand and follow the laws and regulations related to flying of drones in India. Specifically study about the, “Drone Rules 2021 by the Indian Govt”.
* Study BVLOS regulations and flight planning considerations.
* Make a detailed flowchart on both the above topics.

**Learnings and Outcomes :**\
Here is the flowchart \
can check the both flowcharts based on few of the rules & regulations set by the DGCA & MoCA under the New Drone Rules 2021;\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/2fc061262c63ff9a21ff22a402888e036c9cac23/mermaid-diagram-2026-01-27-001714.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/1f5849e262afe00db3a303519beda11cd1e2ae30/mermaid-diagram-2026-01-27-002356.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/7881bbad42295f646c4fb7e53bddd06e292d0748/Screenshot%202026-01-27%20003156.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/2a05c59774d08ce5a989ec6e7f0cb31e2cd6c004/Screenshot%202026-01-27%20003233.png)\
![image](https://raw.githubusercontent.com/tejashreehn610-blip/Level-1-report/fa7612dbce478227a575ee82657ae15cefb745a1/Screenshot%202026-01-27%20003326.png)\
**About BVLOS (Beyond Visual Line of Sight) regulations and how they impact flight planning, airspace management, and safety in India**\
# BVLOS Regulations and Operations in India

**BVLOS (Beyond Visual Line of Sight)** refers to drone operations where the pilot controls the aircraft without maintaining a direct eye-contact view, relying instead on onboard sensors and data links.


## 1. Regulatory Framework (DGCA)
In India, the **Directorate General of Civil Aviation (DGCA)** governs BVLOS under the **Drone Rules, 2021** and the **National UTM Policy**.

* **Digital Sky Platform:** The central IT system for drone registration and flight permissions.
* **NPNT (No Permission-No Takeoff):** A software-based "gatekeeper" that prevents the drone from arming its motors unless a valid permission artifact is present.
* **Airspace Zoning:** * **Green Zone:** Up to 400ft; generally open but requires notification for BVLOS.
    * **Yellow Zone:** Controlled airspace; requires ATC permission.
    * **Red Zone:** Prohibited; requires Central Government approval.


## 2. Impact on Flight Planning
Planning for BVLOS is significantly more complex than standard VLOS missions:

* **SORA (Specific Operations Risk Assessment):** Operators must evaluate the "Ground Risk" (people on the floor) and "Air Risk" (other aircraft) for the entire flight path.
* **Redundancy Planning:** Plans must include secondary communication links (e.g., switching from 4G to Satellite) if the primary link fails.
* **Weather Monitoring:** Real-time data is required for the *entire* route, as conditions 10km away may differ from the takeoff point.


## 3. Airspace Management & UTM
Because BVLOS drones are "invisible" to the pilot, **Unmanned Traffic Management (UTM)** acts as the digital air traffic control.

* **Strategic De-confliction:** The UTM system ensures no two drone flight plans overlap in time and space before they take off.
* **Real-time Tracking:** Drones must broadcast their location via **Remote ID**, allowing authorities to monitor the "invisible" traffic.
* **Dynamic Geofencing:** If an emergency (like a VIP movement) occurs, the UTM can push a "virtual fence" to drones in the air, forcing them to reroute or land.

## 4. Safety and Technical Requirements
Safety is the highest priority for the DGCA when granting BVLOS authorizations.

| Requirement | Description |
| :--- | :--- |
| **Detect & Avoid (DAA)** | Sensors (LiDAR/Radar) that allow the drone to autonomously steer clear of obstacles. |
| **Fail-Safe Systems** | Includes "Return to Home," "Independent Flight Termination," and "Parachute Recovery Systems." |
| **Encrypted C2 Link** | The Command and Control link must be encrypted to prevent hijacking or signal interference. |
| **Human-in-the-loop** | Even if autonomous, a certified Remote Pilot must be able to intervene at any moment. |

## 5. Summary of Impacts
* **Logistics:** Enables "Middle Mile" and "Last Mile" deliveries in rural India.
* **Infrastructure:** Allows for hundreds of kilometers of railway or pipeline inspection in a single flight.
* **Agriculture:** Permits large-scale pesticide spraying over massive hectares of farmland.
























