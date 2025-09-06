## sridhar G (212223060271)
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
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/659f163a-e6c5-4c63-b1a1-19e02461c727" />


### 2. Transient Response Setup

<img width="406" height="479" alt="486145016-12e088ad-e873-42e5-b993-e75244603bf8" src="https://github.com/user-attachments/assets/97ca5771-79fd-465b-a2b9-ada494091730" />



<img width="1920" height="1080" alt="Screenshot 2025-09-06 130624" src="https://github.com/user-attachments/assets/fd9fff1c-6e93-4249-ad30-3e0d7dd093be" />


## Output

### 1. Transient Analysis Output
<img width="1920" height="1080" alt="Screenshot 2025-09-06 130652" src="https://github.com/user-attachments/assets/f29d948e-3188-4fa9-b59e-1324d8d087c8" />


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
