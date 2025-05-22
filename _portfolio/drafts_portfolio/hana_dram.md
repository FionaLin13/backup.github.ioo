---
title: "DRAM on PCB"
excerpt: "2.679 Final Project
<br/><img src='/images/dram.png'>"
collection: portfolio
---
### 🐱 Hana DRAM – Discrete Memory on a Custom PCB

**Goal:**  
As part of MIT’s 2.679 (Electronics for Mechanical Engineers), the goal was to design, manufacture, and hand-solder a custom PCB that interfaces with a Raspberry Pi. The project was open-ended, with only two constraints: Pi compatibility and board size.

**My Role & Contributions:**  
I designed a fully custom DRAM circuit using **discrete transistors and capacitors**, where each bit is stored as charge. I wanted the bit state to be both **electronically functional and visually represented**, so I added LEDs to indicate charge states.

Key tasks included:
- Designing the schematic and component selection in **KiCad**
- Calculating appropriate values for resistors, capacitors, and LED current-limiting
- Learning and applying **PCB routing best practices** (trace width, spacing, ground planes)
- Creating custom art in copper layers — including a line-traced drawing of my cat, **Hana**

**Tools & Skills Used:**  
KiCad, SMD soldering, PCB design rules, Raspberry Pi GPIO interface, electronics fundamentals

**Challenges & Solutions:**  
- LED current limits were miscalculated due to incomplete datasheets; the first test burned them out, though the memory circuit itself still functioned  
- Choosing proper trsace sizes and layout was a challenge due to lack of prior experience, but I learned a lot about **power routing and spacing standards**
- Balancing function and fun — incorporating art without compromising routing — helped me learn KiCad’s layer system in depth

**Outcome:**  
The circuit worked and interfaced with the Pi as expected, though the **visual LED indicators failed** due to low resistor values. I could fix this by swapping the resistors and LEDs. The final board was clean, readable, and uniquely personal — about 25% of it was dedicated to a graphic of my cat.

**What I Learned:**  
Beyond the technical skills of schematic design and PCB layout, this project taught me to prioritize **what really matters in a system** — identifying critical specs and testing assumptions before committing to fabrication. It also reminded me that even technical projects can have space for **humor, art, and personal expression.**
