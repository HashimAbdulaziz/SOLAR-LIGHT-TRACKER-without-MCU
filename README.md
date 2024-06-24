# SOLAR-LIGHT-TRACKER-without-MCU
# 2-D Analog Solar Tracker Project
![image](https://github.com/HashimAbdulaziz/SOLAR-LIGHT-TRACKER-without-MCU/assets/88584784/d5b53e64-afd5-4ef4-8e7b-29d492fb83c4)

#Project Report:https://drive.google.com/file/d/1iZGZQRWUv7bklW1GqmcaXznetYtyQftW/view?usp=sharing


## Overview
The 2-D Analog Solar Tracker project aims to create a solar tracking system without the use of microcontrollers. This tracker utilizes Light Dependent Resistors (LDRs) to detect light intensity. The output signals from the LDRs are processed by op-amp comparators, which in turn control the movement of two DC motors via an L293D driver. A 555-timer circuit regulates the enable pin of the L293D, providing precise control over the tracker mechanism. This analog approach simplifies the design process by eliminating the need for complex programming.

![2-D Analog Solar Tracker](images/solar_tracker.jpg)

## Project Objectives
The primary goal of the 2-D Analog Solar Tracker is to enhance the efficiency of solar panels by continuously aligning them with the sunlight in both horizontal and vertical directions. This optimization maximizes the absorption of solar energy, leading to increased energy generation.

## Features and Advantages
- **Analog Nature:** No microcontrollers are used, simplifying design and reducing complexity.
- **Cost-Effective:** Uses inexpensive components such as LDRs, op-amps, and a 555-timer.
- **Ease of Implementation:** Offers a straightforward alternative to digital solar trackers, ideal for environments with limited programming expertise.

## Components Used
- **Light Dependent Resistors (LDRs):** Detect light intensity for solar tracking.
- **Op-Amp Comparators (LM358):** Process LDR signals to control motor direction.
- **555-Timer:** Provides a stable signal for controlling the L293D driver's enable pin.
- **L293D H-Bridge:** Controls the movement of DC motors based on comparator outputs.

## Simulation and Design Tools
- **LTspice:** Used for schematic simulation of the analog circuit.
- **KiCad:** Used to design the full PCB layout for the project.

## Project Setup
1. **Simulation:** Use LTspice to simulate the analog circuit design to ensure proper functionality.
2. **PCB Design:** Utilize KiCad to translate the schematic into a printed circuit board layout.
3. **Component Integration:** Assemble the hardware components based on the finalized PCB design.

## Testing and Calibration
Rigorous testing and calibration are essential to ensure the accurate functionality of the LDRs, op-amps, and DC motors under varying light conditions. Fine-tuning may be required to optimize performance.

## License
This project is licensed under the [License Name]. See the LICENSE.md file for details.
