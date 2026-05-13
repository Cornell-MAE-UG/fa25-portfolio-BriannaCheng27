---
layout: project
title: Robot Competiton 
description: Built a Robot for Mechatronics class
technologies: [Arduino Uno, Embedded C/Arduino programming, DC motors, Micro Servos, laser-cut gears, 3D-printed mounts, CAD modeling, Prototyping, Mechanical Assembly.]
image: /assets/images/Robo.jpg
---


For this MAE 3780 final project, our team designed and built an Arduino-powered competition robot focused on speed, early block collection, and defensive positioning. Instead of relying on sensors, we prioritized a simple and reliable mechanical strategy: reach the center of the arena quickly, collect as many blocks as possible at the start of the match, and then hold a strong position while the opposing robot continued searching for blocks. To improve speed, we implemented a 3:1 gear train and used larger wheels to cover more distance in less time. The robot also included servo-deployed cardboard arms that expanded outward after the match began, increasing the collection area while staying within the required starting dimensions.

The robot’s control system was hard-coded using an Arduino Uno and direct motor commands. Its programmed path sent the robot forward, deployed the arms, randomly turned left or right, drove across the board, and then repositioned toward our side of the arena. Mechanically, the project involved laser-cut gears, custom 3D-printed gear mounts, servo-actuated arms, and a cardboard collection structure. Although the robot faced challenges with gear alignment, adhesive strength, and arm attachment, the final design successfully executed the intended strategy during competition. The robot finished with a record of 4 wins, 2 losses, and 1 tie, advancing to the round of 16

Click <a href="{{ "/assets/MAE3780FinalReport.pdf" | relative_url }}">here</a> for my final project write-up.
