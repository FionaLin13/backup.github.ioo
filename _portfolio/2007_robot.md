---
title: "Mega-bot"
excerpt: "2.007 Final Project
<br/><img src='/images/2007_1.png'>"
collection: portfolio
---


<img src='/images/2007_2.png'>"
This project aims to create a robot that can traverse an obstacle course and complete tasks to win points. Given limited time resources, I decided to focus on dropping a peg into a hole and pushing around balls. The final robot has these components:
An Acme-rod driven mechanism to accurately drop the peg into a hole
A metal arm attached to the above mechanism pushes balls around

It’s interesting to note that the arm cannot hold on to the peg securely, given the stall torque of the servo. My solution is to add rubber bands to the end of the arm to increase the coefficient of friction. With the rubber bands in place, the arms hold the peg securely every time with less torque requirement.

Not that it mattered in the end. My robot fell on its butt after dropping the peg and attempted to go up a ramp. I tested the robot extensively, but forgot to test it on an incline. The robot is back-heavy after dropping the peg. It wasn’t enough to tip it on level ground, but enough on an incline.

The lesson learned here is that I need to allocate more time to test projects and consider every state the system could have in the field.
