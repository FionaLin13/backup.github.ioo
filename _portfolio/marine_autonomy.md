---
title: "Search and Rescue Algorithm"
excerpt: "2.680 Final Project
<br/><img src='/images/marine_vehicles.jpg'>"
collection: portfolio
---
credit to Mike Benjamin for pictures
## 🛟 Cooperative Marine Search & Rescue  

<img title="a title" alt="Alt text" src="/images/marine_lookin.jpg">
<img title="a title" alt="Alt text" src="/images/marine_briefing.jpg">

**Class Project · MIT 2.680: Unmanned Marine Vehicle Autonomy · Spring 2023**  
**Languages/Tools:** C++, MOOS-IvP, iMarineSim, GitLab

![Mission Briefing](assets/marine_autonomy_briefing.jpg)  
*Mission briefing before live deployment*

![Mission Control Room](assets/marine_autonomy_controlroom.jpg)  
*Monitoring the deployment from the control room*

![Vehicles on the Charles River](assets/marine_autonomy_vehicles.jpg)  
*Scout and rescue vehicles on the Charles River*

### Summary  
This project involved programming a team of autonomous marine vehicles to perform a coordinated search and rescue operation for simulated overboard swimmers on the Charles River. The goal was to detect swimmers and relay their position to a rescue vessel, using real-time inter-robot communication and behavior-based autonomy.

### My Role  
I collaborated with a teammate to develop the behavior for our scout vehicle, while they focused on the rescue vehicle. The scout’s primary task was to search the area efficiently and communicate detections to the responder. I implemented a zigzag search behavior that prioritized robustness and simplicity — a deliberate choice given the limited time for testing and the high variability of real-world deployment conditions.

My responsibilities included:
- Designing and coding the `zigzag` search behavior module in C++
- Handling signal coordination between autonomy modules and vehicles
- Tuning state transitions based on swimmer detection and team signals
- Simulating and testing behaviors in MOOS-IvP before river deployment

### Technical Challenges  
- Getting up to speed with MOOS-IvP and behavior-based autonomy
- Designing a search strategy that balanced reliability and performance
- Debugging behavior transitions and real-time communication issues
- Planning for edge cases and minimizing failure points

### Outcome  
The scout vehicle's simple yet reliable search pattern allowed our team to perform consistently well during the live challenge. While many other systems encountered last-minute bugs, our approach held up under pressure. The project emphasized the importance of robust design, iterative testing, and clear inter-agent communication in autonomous robotics.
