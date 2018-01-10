---
layout: post
title:  "Baxter as a Laundry Assistant"
color:  blue
width:   4 
height:  1
date:   2016-03-30 11:31:49 +0200
categories: jekyll update
---

I was part of a five member group that worked with the Baxter robot from Rethink Robotics for the ME 495: Embedded Systems in Robotics final project.

Our goal was to get Baxter to thread and unthread the lid of a Tide bottle. We wrote custom ROS services, subscribers, publishers, and nodes as part of this project. 

AR tags were used for identification of the Tide bottle lid. The AR tags provided very accurate information about the pose and orientation of the lid, and then we used the IK Solver Service to obtain the joint angles for Baxter's arm. The Github repository for the group project, along with the code, can be found [here](https://github.com/am2512/baxter_final_project).