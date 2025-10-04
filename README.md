## Sridhar G(212223060271)
# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. Schematic of Full Custom 2:1 MUX
<img width="1920" height="1080" alt="Screenshot 2025-09-30 111653" src="https://github.com/user-attachments/assets/04b468b7-e0c9-42b7-98f0-7c56f23c99c2" />



### 2. Transient Response Setup
<img width="613" height="730" alt="image" src="https://github.com/user-attachments/assets/aae3e847-8487-446e-acba-57b68492c43b" />




<img width="1920" height="1080" alt="Screenshot 2025-09-30 114709" src="https://github.com/user-attachments/assets/0f5c3a93-6488-49ae-8d86-c468533b6a72" />


## Output

### 1. Transient Analysis Output
<img width="1920" height="1080" alt="ex02 4" src="https://github.com/user-attachments/assets/df1c9fca-92d8-4f38-a792-ac98c65bbdcc" />


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
