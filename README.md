# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![WhatsApp Image 2025-09-01 at 11 31 46_2f5c60d7](https://github.com/user-attachments/assets/a20b1e74-5ba2-479d-92a2-14437595ee2b)




#### 2. Schematic of CMOS Inverter:

   ![WhatsApp Image 2025-09-01 at 11 22 24_f28eb313](https://github.com/user-attachments/assets/3e77fe17-dc56-4a5a-bfbe-ff18bdaf2e9f)


#### 3. Transient Response Setup:

![image](https://github.com/user-attachments/assets/ecdf8ecc-5dfe-404d-ba08-85b1982881cf)


![WhatsApp Image 2025-09-01 at 11 28 23_49e2cbb1](https://github.com/user-attachments/assets/5021fb81-424f-48e2-8aa1-d1d37a29cae4)




## Output
#### 1.Transient Analysis Output

![WhatsApp Image 2025-09-01 at 11 20 21_4e02dd03](https://github.com/user-attachments/assets/5bfaa732-6b4b-4c06-afad-e5f515859296)



## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











