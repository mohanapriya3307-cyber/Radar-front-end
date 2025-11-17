Solutions of Problems Using Smith Chart in Radar Front-End Systems (SWR, Reflection Coefficient, Impedance Matching)
---
Introduction to Radar Front-End Problem
---

In a 77 GHz automotive radar, the PA output must deliver maximum power to the transmit antenna.
But the antenna impedance is rarely exactly 50 Ω at all frequencies. Even a small mismatch leads to:
Reduced transmitted power
Increased reflected wave → overheating of PA
Distortion in radar chirps
Reduced detection range
Typical mismatch example:
Power Amplifier Output Impedance: 50 Ω
Radar Patch Antenna Impedance at 77 GHz: 38 + j12 Ω
This mismatch must be solved using a Smith Chart.

<img width="685" height="417" alt="image" src="https://github.com/user-attachments/assets/91fe79a4-2828-4ae1-9484-0600e366d4a7" />

Real-Time Application Example (ADAS Radar)
--
Scenario

A car's radar system must detect obstacles at 200–250 meters.
A mismatch occurs between the PA and the patch antenna due to:

Manufacturing tolerance,
Temperature drift,
Frequency shift,
PCB dielectric variation,

The car begins to lose detection range by 20–25 meters.

Engineering Task
---

Use the Smith Chart to calculate:

Reflection Coefficient (Γ),
SWR,
Normalize impedance,
Shift impedance using microstrip line,
Design matching network,
And restore the radar’s maximum performance.

Problem Statement
---
Given:
Load impedance of radar antenna:

<img width="284" height="48" alt="image" src="https://github.com/user-attachments/assets/e3e302a5-4c82-406a-91ae-eb98b418d64f" />

Transmission line impedance:

<img width="139" height="36" alt="image" src="https://github.com/user-attachments/assets/d6ed7698-0fe3-4e1c-92a9-d3c837e5a8af" />

Find using the Smith Chart:

Normalized Impedance

Reflection Coefficient (Γ)

VSWR

Return Loss

Matching network solution
