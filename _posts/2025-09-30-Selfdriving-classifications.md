---
layout: post
title: "Self-Driving Classifications — Explained"
tags: [self-driving]
---
**Levels of Autonomous Driving:**  
The levels of autonomy that are used to decide how autonomous a system is.

**Level 0:** In this level, there is no assisted driving, the human driver must operate all driving tasks.  
**Level 1:** The vehicle can control either longitudinal motion (Adaptive Cruise Control) or lateral motion (Lane Keeping) but NOT both.  
**Level 2:** the vehicle can control both longitudinal and lateral motion   
**Level 3:** The vehicle can perform both driving actions from level 2, but in addition can do Object and Event Detection and Response (OEDR) to do things like applying brakes to avoid hitting an obstacle. The biggest difference between Level 3 and the previous levels is that, OEDR will classify the obstacle and always stop to avoid it, whereas Adaptive Cruise Control might flag it as a false positive and drive straight into it.  
**Level 4:** The system can drive fully autonomously in its designed environment with no human supervision. In this level, the human driver does not have to pay full attention as the system is capable of alerting the driver in time to take over.  
**Level 5:** Same as Level 4, but is not limited to a pre-determined operational area and is able to drive anywhere. At the time of this being written, there is no current Level 5 system.
