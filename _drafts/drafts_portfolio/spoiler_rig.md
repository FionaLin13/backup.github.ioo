---
title: "Spoiler Rig"
excerpt: "industry project De-Ice
<br/><img src='/images/spoiler_rig.png'>"
#collection: portfolio
---


For my digital system laboratory class final project, my teammate and I wanted to implement Conway’s Game of Life on the FPGA. We wanted to make the project challenging by proposing deliverables that would test the limits of our resources (e.g., project time, FPGA memory capacity, clock speed, number of arithmetic units, etc.). In the end, we aimed to implement these features:
A 480 by 480 grid @ 31fps. This is large enough to require non-trivial implementation, but feasible given our clock speed.
The user can load pre-loaded seeds into the game board. The seeds are initial patterns that produce exciting effects.
GOLF plays sound effects triggered by user input during the game.
The user can also interact with the board using a USB mouse.
We came up with a “chasing the pixel” style architecture. After finalizing the architecture, I worked on the XVGA signal generator,  the renderer, and the audio module.

In the end, we delivered all of our promised deliverables on time.
Link to video demonstration here.
