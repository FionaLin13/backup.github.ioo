---
title: "DRAM on PCB"
excerpt: "2.679 Final Project
<br/><img src='/images/dram_pcb.jpg'>"
collection: portfolio
---
# 🐱 Hana DRAM – Discrete Memory on a Custom PCB

## Tools & Skills Used 
KiCad, SMD soldering, PCB design, Raspberry Pi GPIO interface, electronics fundamentals

<img title="a title" alt="Alt text" src="/images/dram_schematic.jpg">
<img title="a title" alt="Alt text" src="/images/dram_final_top.jpg">
<img title="a title" alt="Alt text" src="/images/dram_final_back.jpg">

## Goal
As part of MIT’s 2.679 (Electronics for Mechanical Systems II), the goal was to design, send to manufacture, and hand-solder a custom PCB that interfaces with a Raspberry Pi. The project was open-ended, with only two constraints: Pi compatibility and board size.

## Outcome 
The circuit worked and interfaced with the Pi as expected, but I could not calculate the appropriate resistor values for LEDs since I had no datasheets for the LEDs. With insufficent resistance, after the first run all LEDs burnt out. This is an easy fix - I could use different resistors or LEDs. 

The final board was clean, readable, and adorable — about 25% of it was a cute cat. This board would make a great education tool for an intro computer systems class.

## My Role & Contributions  
I designed a fully custom DRAM circuit using discrete transistors and capacitors, where each capacitor represents one bit. I wanted the bit state to also be visible to the eye, so I added LEDs for each capacitor. For each bit that is on, there will be a corresponding LED that turns on.

Key tasks included:
- Designing the schematic and PCB in KiCad
- Picking the appropriate resistors, capacitors, and LEDs based on current and voltage limits
- Learning and applying PCB routing best practices (trace width, spacing, organization)
- Creating custom art in layers — including a line-traced drawing of my cat Hana

## What I Learned  
Beyond the technical skills of schematic design and PCB layout, this project taught me the improtance of compartmentization and identifying the "must-haves" vs. "nice-to-haves" in a system. For example, making sure to isolate the LED system with the memory circuit such that in case the LEDs failed, the memory circuit still worked.
