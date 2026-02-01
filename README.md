**8-bit Linear Feedback Shift Register (LFSR) using CMOS**


**📌 Project Overview**

This project implements an 8-bit Linear Feedback Shift Register (LFSR) using CMOS logic at the transistor level in Cadence Virtuoso. The design generates pseudo-random binary sequences using XOR-based feedback derived from a primitive polynomial, producing a maximal-length sequence of 255 non-zero states.

**🧠 Design Description**

The LFSR consists of eight cascaded D flip-flops arranged in a Fibonacci configuration. Selected tap outputs are combined using an XOR gate to generate the feedback bit, which is fed into the first flip-flop on every rising clock edge. The entire circuit is designed using CMOS transistors and verified through transient simulation.

**🔧 Tools & Technologies**

- Cadence Virtuoso

- Spectre Simulator

- CMOS Logic Design

- Sequential Circuits

**📊 Verification & Analysis**

- Transient waveform simulation

- Timing analysis (propagation delay, clock-to-Q delay)

- Power and power–delay product (PDP) evaluation

**📁 Repository Contents**

- Project report (PDF)

- Schematic screenshots

- Waveform and simulation results

**⚠️ Disclaimer**

This project is developed for academic purposes only.
Foundry PDK files and licensed Cadence libraries are not included.

**🎯 Applications**

- Pseudo-random number generation

- Built-In Self-Test (BIST)

- Communication systems

- Digital and VLSI testing
