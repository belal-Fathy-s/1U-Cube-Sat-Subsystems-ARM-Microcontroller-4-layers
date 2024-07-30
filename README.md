# 1U CubeSat Subsystems ARM Microcontroller Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Hardware](#hardware)
   - [PCB Designs](#pcb-designs)
   - [Subsystems](#subsystems)
3. [Software](#software)
   - [Subsystems](#subsystems-1)
4. [Getting Started](#getting-started)
5. [Contact](#contact)

## Project Overview

This project was my graduation project, done in cooperation with the Egyptian Space Agency. It aims to develop a 1U CubeSat with ARM microcontrollers managing its five primary subsystems. The repository contains both the hardware PCB designs and the software needed for each subsystem, providing a comprehensive guide for anyone interested in CubeSat technology. This project serves as a prototype using materials suitable for Earth-based testing.

## Hardware

### PCB Designs

The hardware section contains the PCB designs for each of the five subsystems. These designs are created using Altium Designer and each subsystem is a four-layer board.

### Subsystems

1. **Electrical Power System (EPS)**
    - **Description**: Manages the power distribution and energy storage for the CubeSat.
    - **PCB Design**: [EPS PCB Design](path/to/EPS_PCB_Design)

2. **Communication Subsystem (COMM)**
    - **Description**: Handles the transmission and reception of data between the CubeSat and ground stations.
    - **PCB Design**: [COMM PCB Design](path/to/COMM_PCB_Design)

3. **Attitude Determination and Control Subsystem (ADCS)**
    - **Description**: Maintains the orientation and stability of the CubeSat in orbit.
    - **PCB Design**: [ADCS PCB Design](path/to/ADCS_PCB_Design)

4. **Payload Subsystem (PLD)**
    - **Description**: Contains the scientific instruments and sensors for the mission-specific objectives.
    - **PCB Design**: [PLD PCB Design](path/to/PLD_PCB_Design)

5. **On-Board Computer Subsystem (OBC)**
    - **Description**: The central processing unit that coordinates the operations of all subsystems.
    - **PCB Design**: [OBC PCB Design](path/to/OBC_PCB_Design)

## Software

### Subsystems

Each subsystem has dedicated software to manage its operations. The software is written primarily in C/C++ for ARM microcontrollers, ensuring efficient and real-time performance. CubeMX was used to auto-generate much of the functionality, facilitating the development process.

1. **Electrical Power System (EPS)**
    - **Software**: [EPS Software](path/to/EPS_Software)

2. **Communication Subsystem (COMM)**
    - **Software**: [COMM Software](path/to/COMM_Software)

3. **Attitude Determination and Control Subsystem (ADCS)**
    - **Software**: [ADCS Software](path/to/ADCS_Software)

4. **Payload Subsystem (PLD)**
    - **Software**: [PLD Software](path/to/PLD_Software)

5. **On-Board Computer Subsystem (OBC)**
    - **Software**: [OBC Software](path/to/OBC_Software)

## Getting Started

To view and understand this project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/CubeSat-Subsystems-ARM.git
    cd CubeSat-Subsystems-ARM
    ```

2. **Review the PCB Designs**:
    - The PCB design files are located in the `hardware` directory.

3. **Review the Software**:
    - The software files are located in the `software` directory.

## Contact

For any questions or inquiries, please contact:

- **Name**: [Your Name]
- **Email**: [your.email@example.com]
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)
