**CMOS Logic & Sequential Circuit Design (Ltspice Simulation)**

Overview
This project focuses on the design and timing analysis of CMOS-based digital circuits, from basic logic gates to a Master-Slave D-FlipFlop. The research analyzed how MOSFET parasitic capacitance impacts switching performance and maximum operating frequency.

Key Technical Highlights
Circuit Design: Implemented CMOS NOT, NAND, AND, D-Latch, and D-FlipFlop architectures.
Performance Analysis: Compared high-current (BSB012N03LX3) vs. high-speed (BSP89) MOSFET models.
Optimization: Identified that high gate capacitance C_iss in models like BSB012N03LX3 (12,700pF) drastically reduces switching speed compared to models like BSP89 (80pF).
Timing Results: Successfully achieved a maximum frequency F_max of 14.7 MHz for the D-Latch and 16.1 MHz for the D-FlipFlop.
Tools UsedLTspice: Schematic design and timing simulations.

Author Shlomo Abrams.
