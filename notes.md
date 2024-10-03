# About Me (5 minutes)

# Trends in SDV (Software-Defined Vehicles) and Embedded Systems
## Architecture Evolution
## Software-Defined Vehicles (SDV) as the New Norm
- **Shift from hardware-centric to software-driven vehicles**: Modern vehicles are becoming more defined by the software they run that the hardware they contain. This trend allows for **over-the-air (OTA) updates**, enabling automakers to enhance vehicle features, fix bugs, and improve functionality without requiring physical modifications.
- **Separation of hardware and software development**: In SDVs, the hardware platform (ECUs, sensors) is becoming increasingly abstracted from the software layer. This decoupling allows for **more rapid innovation** and adaptation, with manufacturers focusing on building flexible, modular software that can run on various hardware configurations.
Software-Defined Vehicle (SDV) is a vehicle whose operation focuses on software over hardware.

SDVs manage their operations, add functionality, and enable new features primarily or entirely through software.
SDVs prioritize software to enable vehicle functionality, unlike traditional cars built around a mechanical framework.

Software-Defined Vehicles are the next evolution of the automotive industry.
They are the foundation of many other advancements, including self-driving and connected cars.
## Growth in Embedded Systems Complexity
- **Increase in electronic control units (ECUs)**: As vehicles become more advanced, the number of ECUs managing different vehicle functions (engine control, braking, infotainment) grows. However, there is a move toward **centralized computing**, where fewer but more powerful ECUs (or domain controllers) Manage multiple functions, reducing complexity and weight.
- **Embedded systems as the backbone ADAS and autonomous features**: Embedded systems now handle vast amounts of sensor data, process inputs in real-time, and enable decision-making for ADAS and autonomous driving features. These systems require robust software solutions that can handle real-time data processing with minimal latency.
## Integration of AI and Machine Learning in Automotive Software
- **AI and ML in SDVs and ADAS**: AI is becoming essential for enabling higher levels of autonomy, including advanced driver assistance and predictive maintenance. Machine learning models in vehicles are being trained to recognize objects, predict behavior, and optimize the driving experience.
- **Data-driven development**: Vehicle software is increasingly **data-centric**, with in-vehicle sensors constantly generating data that manufacturers and service providers use to train AI algorithms, improve features, and optimize vehicle performance through cloud-based analytics.
## Adoption of AUTOSAR (AUTomotive Open System ARchitecture)
- **Standardization and interoperability**: AUTOSAR facilitates standardization in automotive software, allowing different suppliers and manufacturers to work with a common software framework. This trend is key in ensuring that software developed for one vehicle platform can easily be adapted or integrated into another.
- **Adaptive AUTOSAR**: While Classic AUTOSAR was designed for static real-time systems, Adaptive AUTOSAR is emerging to support more dynamic environments, essential for SDVs. It enables flexible updates, more computationally intensive tasks, and cloud connectivity, which are necessary for autonomous systems and connected vehicles.
AUTOSAR (AUTomotive Open System Architecture) is a global partnership of leading companies in the automotive and software industry to develop and establish the standardized software framework and open E/E system architecture for intelligent mobility.

It was established in 2003 by a consortium of major automotive manufacturers and suppliers, including companies like BMW, Bosch, and Audi.

The primary goal was to create standardized software architecture that would improve modularity, interoperability, and reusability across different automotive systems and suppliers.

The standardization allows for:
1. **Improved Integration**: Facilitates easier integration of software components from different suppliers.
2. **Increased Reusability**: Promotes the reuse of software modules across different vehicle models and manufacturers.
3. **Enhanced Flexibility**: Supports the development of complex systems by defining clear interfaces and abstractions.
4. **Efficient Development**: Streamlines the development process, reducing time and cost by using standardized components and tools.
## Vehicle Connectivity and V2X Communication
- **Vehicle-to-Everything (V2X) communication**: Connectivity between vehicles and their surroundings is becoming more important, especially in SDVs. This includes communication with other vehicles (V2V), infrastructure (V2I), and cloud services (V2C), allowing for improved safety, real-time updates, and predictive maintenance.
- **5G enabling connected vehicles**: The deployment of **5G networks** is enabling faster and more reliable communication between vehicles, infrastructure, and cloud services. This low-latency connectivity is essential for autonomous driving and the future of mobility.
## Cybersecurity in Automotive Systems
- **Security challenges in SDVs**: As vehicles become more connected, they become vulnerable to cyber-attacks The need for robust **cybersecurity solutions** to protect in-vehicle networks, prevent unauthorized access, and ensure the safety of OTA updates is a significant trend in automotive software development.
- **Regulations and standards**: New cybersecurity standards and regulations (like **ISO/SAE 21434** and **UNECE WP.29**) are emerging to address these risks, pushing automakers to implement strong security measures at the software level.
## Electrification and Software Convergence
- **Electric vehicles (EVs)**: The rise of EVs is driving the need for sophisticated software to manage energy use, battery life, and charging systems. Software is now central to optimizing vehicle efficiency, performance, and range.
- **Convergence of powertrain and infotainment systems**: Software in EVs and hybrid vehicles is integrating traditional powertrain management with infotainment and user experience features, enabling seamless driver interaction and smart energy use.

# The Car as a Mechatronics System (5 minutes)
## Definition and components of a mechatronics system
A Mechatronic System is defined as an integrated system comprising mechanical parts, electric devices, electronics components, and hardware, all controlled by programmed software, reflecting a multidisciplinary approach involving Mechanics, Electronics, Electric Engineering, Control, Measurement, and Computer Science.
## Integration of mechanical, electronic, and software systems
### Actuators and sensors
Actuators produce motion or cause some action
- pneumatic and hydraulic actuators
- electro-mechanical actuators,
- electrical motors (DC< AC, stepper, servo, piezoelectric)
Sensors detect the state of the system parameters, inputs, and outputs
- linear arid rotational sensors
- acceleration sensors
- force sensors
- torque sensors
- pressure sensors
- flow sensors
- temperature sensors
- proximity sensors
- light sensors
### Signals and conditioning
Two types of signals and conditioning: input and output
Input devices receive input signals from the mechatronic systems via interfacing devices and sensors, which is then sent to the control circuits for conditioning or processing
- discrete circuits
- amplifiers
- Analog-to-Digital (A/D) converters
- Digital-to-Digital (D/D) converters

Output signals from the system are sent to output/display devices through interfacing devices
- Digital-to-Analog (D/A) converters
- Display Decoders (DD) converters
- amplifiers
- power transistors
- power op-amps
### Digital logic Systems
Digital logic devices control overall system operation
- logic circuits
- microcontrollers
- programmable logic controllers
- sequencing and timing controls
- control algorithms
# Advanced Driver Assistance Systems (ADAS) (10 minutes)
## Importance of ADAS
Advanced Driver Assistance Systems is a catch-all term for any type of technological feature that makes driving safer, easier or more comfortable.
## Levels of Automation
### Leaders in Different Automation Levels
#### L1: Driver Assistance
- Toyota: Toyota Safety Sense suite
- Honda: Honda Sensing technology
- Ford: adaptive cruise control
- Nissan: Nissan's ProPILOT Assist
#### L2: Partial Automation
- Tesla: Autopilot system
- General Motors (Cadillac): super cruise system
- Mercedes-Benz: driver pilot
- BMW: Driving Assistant Plus system
- Audi: Traffic Jam Assist
#### L3: Conditional Automation
- Audi (A8): Traffic Jam Pilot
- Honda: Traffic Jam Pilot
- Mercedes-Benz: Drive Pilot
#### L4: High Automation
- Waymo: Waymo One service
- Navya: Shuttle service
#### L5: Full Automation

# Key ADAS Applications (10 minutes)
## Lane Keeping Assistance (LKA)
## Adaptive Cruise Control (ACC)
## Automatic Emergency Braking (AEB)

# Role of Computer Vision in ADAS (10 minutes)
## Neural Network

## Convolutional Neural Network
## Techniques
### Image Segmentation
Image segmentation divides an image into segments to isolate and identify objects of interest. In ADAS, this technique is vital for differentiating between the road, pedestrians, cars, and traffic signs.

- **Semantic Segmentation:** Each pixel is classified into a category (e.g., road, vehicle, pedestrian).
- **Instance Segmentation:** Identifies specific instances of objects (e.g., distinguishing between two pedestrians).

**Example:** Semantic segmentation helps Lane Keeping Assistance (LKA) systems identify lane boundaries, while instance segmentation is useful in detecting individual vehicles in congested traffic.
### Blob Detection
Blob detection is a technique used to detect regions in an image that differ in properties, such as brightness or color. This is useful for identifying objects like vehicles or pedestrians that stand out from their surroundings.

**Example:** Detecting large "blobs" corresponding to vehicles or pedestrians for collision avoidance systems or pedestrian detection.
### Optical Flow
This technique tracks the motion of objects in consecutive frames to estimate movement. Optical flow is essential in ADAS for detecting moving objects, such as other vehicles or pedestrians, and predicting their trajectories.

**Example:** Used in Adaptive Cruise Control (ACC) to estimate the distance and speed of cars ahead, ensuring the vehicle maintains a safe following distance.
### Object Detection and Tracking
Object detection identifies objects in the vehicle's surroundings (e.g., pedestrians, cyclists, traffic signs), while object racking follows these objects over time.
**Example:** ACC systems rely on this technique to track the speed and direction of vehicles in front, ensuring a safe distance is maintained.
## Application
### Face Recognition
Face recognition, typically used in **Driver Monitoring Systems (DMS)**, ensures the driver's identity and attentiveness. AI models analyze the driver’s facial features to confirm identity or detect distraction, fatigue, or inattention.

**Example:** Face recognition systems can detect if the driver is falling asleep, triggering alerts to prevent accidents.
### Eye Tracking
Eye tracking is another DMS technique, where the system monitors the driver’s gaze direction and eye movements. If the system detects that the driver is not paying attention to the road, it can sound an alert or even take corrective action, such as applying the brakes or guiding the car to a safe stop.

**Example:** Eye-tracking systems are crucial for detecting driver drowsiness, a leading cause of accidents.
### 3D Pose Estimation
This technique reconstructs a 3D model of the driver or passengers from 2D images to detect body posture and movement. It’s used in DMS to monitor driver behavior (e.g., slouching or awkward positions) and in some passenger safety systems (e.g., detecting children or objects in improper seating positions).

**Example:** By analyzing the driver's pose, the system can determine if the driver is sitting properly and whether seat belts are being used.
# Challenges and Future Trends (10 minutes)
## Technical and safety challenges
### Homologation Procedures
Homologation is the process of certifying that a vehicle meets regulatory standards, which differs by region (EU, USA, China).
One major challenge is the complexity of ADAS systems requiring compliance with safety regulations like ISO 26262 (functional safety) and UNECE WP.29 regulations (cybersecurity and software updates).
Each region may interpret and enforce these standards differently, making global deployment difficult.
### Sensor Interference from Other Vehicles
ADAS systems rely on sensors (cameras, radars, LIDAR, ultrasonic).
As the number of ADAS-equipped vehicles increases, sensors like radar can potentially interfere with each other, leading to false readings or degraded performance.
This challenge will grow as vehicles become more reliant on these technologies for critical decision-making.
See also: radar congestion.
### Edge Cases and Data Inconsistencies
While ADAS systems perform well in structured environments (e.g., highways), they struggle in complex, unpredictable urban scenarios.
Edge cases, such as unpredictable pedestrian behavior or unusual road conditions, can lead to system failures.
ADAS needs to handle real-world complexity reliably, which means better sensor fusion and decision-making algorithms.
### AI Black Box Problem
Most ADAS systems rely on machine learning (ML) models, particularly deep learning.
However, these models operate as "black boxes," meaning that engineers can't easily explain how decisions are made.
This is problematic for safety certification, as regulatory bodies require transparency and explainability to ensure systems act predictably.
### Cybersecurity and Data Privacy
As vehicles become more connected, cybersecurity risks increase.
ADAS systems need secure communication channels to prevent hacking or unauthorized access, especially for over-the-air updates.
Regulations like UNECE WP.29 on cybersecurity, already enforced in some regions, require manufacturers to ensure systems are secure from end to end.
### Cost and Scalability
High-quality ADAS technologies like LIDAR and radar are expensive, limiting their inclusion in mass-market vehicles.
For widespread adoption, ADAS needs to become more affordable while maintaining safety and performance, which is a significant technical and economic challenge.
## Future innovations and trends in AI for ADAS
### Improved Sensor Fusion
Current ADAS systems rely on individual sensor technologies like radar, camera, and LIDAR.
The next generation of AI will focus on better "sensor fusion"—combining inputs from multiple sensors to provide a more accurate, real-time view of the environment.
This will enhance object detection, distance measurement, and obstacle recognition under various conditions, including bad weather.
### Edge AI and Real-Time Processing
With the advancement of edge computing, future ADAS systems will process more data directly within the vehicle, reducing latency and improving decision-making.
This is crucial for real-time applications like collision avoidance.
AI models will run on embedded hardware, allowing for faster, more efficient performance.
### AI for Predictive Behavior Modeling
Current ADAS systems react to immediate inputs (e.g., a vehicle suddenly braking).
Future systems will predict behaviors—such as the likelihood of a pedestrian crossing the street or a car veering out of its lane—using AI.
This will involve analyzing patterns over time to anticipate actions, providing an extra layer of safety.
### Explainable AI (XAI)
Given the challenges of AI’s black box nature, there is a push toward Explainable AI (XAI), where the decision-making processes of AI models become more interpretable and transparent.
XAI will be essential to gaining regulatory approval and increasing trust in ADAS systems, particularly for semi-autonomous and autonomous vehicles.
### Autonomous Driving Levels
Although full automation (Level 5) is still a long-term goal, advancements in AI and computer vision will gradually push systems toward higher autonomy levels.
Level 3 (conditional automation) and Level 4 (high automation) systems will begin to see wider adoption in controlled environments like highways, with AI managing more driving tasks.
### Energy Efficiency in AI Models
ADAS systems are computationally heavy and require significant power.
To make AI-driven ADAS sustainable, future trends will include designing AI models that are not only more accurate but also energy-efficient, ensuring that systems can run without draining the vehicle’s power resources.
# 8. About FPT Automotive (5 minutes)
## Brief overview of your company's role in ADAS and computer vision
## Automotive Industry Growth
# 9. Conclusion (5 minutes)
## Summary of key points
- Vehicles are becoming increasingly complex​
- Software is powering more vehicle functions and components​
- There is a growing need to standardize automotive systems​
- Manufacturers are introducing features that enhance safety, comfort, and convenience​
- Global safety legislations are driving key development​
- The focus is on creating more connected and autonomous vehicles
# 10. Q&A (10 minutes)

# 11. Further Reading

 [Critical Reasons for Crashes Investigated in the National Motor Vehicle Crash Causation Survey](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjb0dfs1emIAxV7r1YBHWvOM9MQFnoECBQQAQ&url=https%3A%2F%2Fcrashstats.nhtsa.dot.gov%2FApi%2FPublic%2FPublication%2F812506&usg=AOvVaw2S4BHqxib6TLdLo20Eo6yN&opi=89978449)
## Open the floor for questions and discussion