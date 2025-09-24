# CMOS Inverter Design and Optimization

## Overview

This project presents the design, simulation, and layout implementation of a CMOS inverter using Cadence Virtuoso. The inverter is analyzed for its DC, AC, and transient performance, followed by layout optimization to ensure manufacturability and correctness via DRC (Design Rule Check) and LVS (Layout Versus Schematic) verification.

## Features

- **Schematic Design:** CMOS inverter designed in Cadence Virtuoso.
- **Simulation Analysis:**
  - **DC Analysis:** Transfer characteristics and noise margins.
  - **AC Analysis:** Frequency response and gain bandwidth.
  - **Transient Analysis:** Dynamic response, delay, and rise/fall times.
- **Layout Implementation:**
  - Custom inverter layout designed and optimized for minimal area and parasitics.
  - DRC (Design Rule Check) performed to verify layout rules compliance.
  - LVS (Layout Versus Schematic) performed to ensure layout matches the schematic.

## Workflow

1. **Schematic Design**
   - Create the inverter schematic using PMOS and NMOS transistors.
   - Parameterize transistor sizes for optimization.

2. **Simulation**
   - Run DC analysis to extract VTC (Voltage Transfer Characteristics).
   - Run AC analysis to examine frequency response.
   - Run transient analysis to evaluate switching behavior.

3. **Layout Implementation**
   - Design custom layout for the inverter.
   - Optimize layout for area, matching, and minimal parasitic effects.
   - Perform DRC to ensure the layout adheres to foundry design rules.
   - Perform LVS to confirm the layout electrically matches the schematic.

