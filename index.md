# DSC 180A Methodology Assignment 4

## About Me

**Name:** Haoshuo Bi

**UCSD Email:** hbi@ucsd.edu

**Domain:** D17 - Physical Intelligence for Intelligent Manufacturing

**Section:** Group A

**Mentor:** Tauhidur Rahman

## Project Background

This quarter, I am working on Embodied AI for Drones using NVIDIA Isaac Lab. My work focuses on drone hovering, navigation, sensor data collection, and wind disturbances. I use the Lee Position Controller to test how drones behave under different conditions.

## Reflection Questions

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic for me is drone navigation and stability. I used the Lee Position Controller in Isaac Lab to test drone hovering and navigation. I successfully tested 2 m, 10 m, and 50 m navigation, and the drone was able to reach the target position accurately. I also tested how a 0.1 N horizontal force affected the drone's position. I found it interesting to see how the drone could maintain stable flight and respond to external forces.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For Quarter 2, I would like to study how different wind conditions affect drone navigation. So far, I have tested a constant 0.1 N force in one direction. I want to try different wind strengths and directions during longer flights, such as 50 m or 100 m. I would compare the drone's actual path with its target path to see how wind affects navigation accuracy and stability.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change I would make is to test more than one controller. Currently, I am using the Lee Position Controller for my experiments. I would like to add a PID Controller and compare their performance under the same conditions. I could compare position errors, flight stability, and how well each controller handles wind disturbances. This would help me understand which controller works better in different situations.

**4. What other techniques would you be interested in using in your project?**

I would be interested in trying Reinforcement Learning (RL) for drone control. Instead of only using a traditional controller, I want to explore whether a drone can learn to improve its flight performance through training. I am also interested in combining IMU, camera, and LiDAR data to help the drone better understand its environment. These techniques could be useful for more complex navigation tasks.
