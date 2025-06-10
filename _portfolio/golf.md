---
title: "GOLF: Game Of Life on the FPGA"
excerpt: "6.111 Final Project
<br/><img src='/images/golf.png'>"
collection: portfolio
---

For my digital system laboratory class final project, my teammate and I wanted to implement Conway’s Game of Life on the FPGA. We wanted to make the project challenging by proposing deliverables that would test the limits of our resources (e.g., project time, FPGA memory capacity, clock speed, number of arithmetic units, etc.). In the end, we aimed to implement these features:
A 480 by 480 grid @ 31fps. This is large enough to require non-trivial implementation, but feasible given our clock speed.
The user can load pre-loaded seeds into the game board. The seeds are initial patterns that produce exciting effects.
GOLF plays sound effects triggered by user input during the game.
The user can also interact with the board using a USB mouse.
We came up with a “chasing the pixel” style architecture. After finalizing the architecture, I worked on the XVGA signal generator,  the renderer, and the audio module.

In the end, we delivered all of our promised deliverables on time.
Link to video demonstration [here](https://youtu.be/uhNHr-jpB5s). 

# 🎮 Game of Life on FPGA

## Tools & Skills Used
Verilog, FPGA development, VGA interfacing, memory management, pipelining, embedded systems, modular design

## Goal
As a class project, my teammate and I implemented Conway’s Game of Life on an FPGA. Our objective was to create an interactive, real-time simulation with live graphics, user input, and audio output — all within the hardware constraints of the board.

## My Role & Contributions
I co-led the architecture design and contributed significantly to both hardware and creative aspects:
- Designed and implemented modules for **display output**, **audio output**, **mouse and keyboard input**, and **seed kernel selection**
- Created all **graphic and audio assets**, giving the game a unique aesthetic
- Helped write the **final report** and present the project

## Challenges & Solutions 
The biggest hurdle was the **memory limitation** — we could only store one frame at a time, but needed to compute and display frames concurrently. I designed a **pipelined pixel system**, inspired by another project, where each pixel “snaked” across the screen, pushing data as it went. This let us simulate the next frame with just one additional pixel buffer.

## Outcome
The result was a fully functional and visually rich Game of Life with:
- 12+ starter patterns selectable via keyboard
- Live pixel editing via mouse input
- Real-time cell tracking and graphing
- A delightfully demonic soundscape

The project ran flawlessly and impressed our instructors so much they had no follow-up questions.

## What I Learned  
This project deepened my understanding of pipelined memory systems, module-based hardware design, and creative problem-solving under hardware constraints — all while building something that looked and sounded cooler than it had any right to.

