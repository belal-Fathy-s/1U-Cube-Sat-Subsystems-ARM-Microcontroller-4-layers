1U CubeSat Subsystems ARM Microcontroller Project
Table of Contents
Project Overview
Hardware
PCB Designs
Subsystems
Software
Subsystems
Getting Started
Contact
Project Overview
This project was my graduation project, done in cooperation with the Egyptian Space Agency. It aims to develop a 1U CubeSat with ARM microcontrollers managing its five primary subsystems. The repository contains both the hardware PCB designs and the software needed for each subsystem, providing a comprehensive guide for anyone interested in CubeSat technology. This project serves as a prototype using materials suitable for Earth-based testing.

Hardware
PCB Designs
The hardware section contains the PCB designs for each of the five subsystems. These designs are created using Altium Designer and each subsystem is a four-layer board.

Subsystems
Electrical Power System (EPS)

Description: Manages the power distribution and energy storage for the CubeSat.
PCB Design: EPS PCB Design
Communication Subsystem (COMM)

Description: Handles the transmission and reception of data between the CubeSat and ground stations.
PCB Design: COMM PCB Design
Attitude Determination and Control Subsystem (ADCS)

Description: Maintains the orientation and stability of the CubeSat in orbit.
PCB Design: ADCS PCB Design
Payload Subsystem (PLD)

Description: Contains the scientific instruments and sensors for the mission-specific objectives.
PCB Design: PLD PCB Design
On-Board Computer Subsystem (OBC)

Description: The central processing unit that coordinates the operations of all subsystems.
PCB Design: OBC PCB Design
Software
Subsystems
Each subsystem has dedicated software to manage its operations. The software is written primarily in C/C++ for ARM microcontrollers, ensuring efficient and real-time performance. CubeMX was used to auto-generate much of the functionality, facilitating the development process.

Electrical Power System (EPS)

Software: EPS Software
Communication Subsystem (COMM)

Software: COMM Software
Attitude Determination and Control Subsystem (ADCS)

Software: ADCS Software
Payload Subsystem (PLD)

Software: PLD Software
On-Board Computer Subsystem (OBC)

Software: OBC Software
Getting Started
To view and understand this project, follow these steps:

Clone the Repository:

sh
Copy code
git clone https://github.com/yourusername/CubeSat-Subsystems-ARM.git
cd CubeSat-Subsystems-ARM
Review the PCB Designs:

The PCB design files are located in the hardware directory.
Review the Software:

The software files are located in the software directory.
Contact
For any questions or inquiries, please contact:

Name: [Your Name]
Email: [your.email@example.com]
GitHub: Your GitHub Profile
