# Autonomous Maze Navigation Robot

## Project Overview
This project involved the development of a sophisticated navigation and guidance system for an **eebot mobile robot**. Working as a collaborative team, we engineered a robust software architecture using HCS12 Assembly language to enable the robot to autonomously navigate complex environments. The robot is capable of following designated paths, detecting and avoiding physical obstacles, and making real-time decisions at intersections to successfully find the exit of a maze.

The core of the system is a state-machine dispatcher that processes continuous sensor data to execute precise motor control and directional adjustments.

## Project Environment
The development and testing of this autonomous system took place in a dedicated robotics laboratory equipped with specialized maze tracks and hardware debugging tools.



## Key Features
* **Intelligent Line Following:** High-precision sensor integration allows the robot to track and stay aligned with maze paths autonomously.
* **Reactive Obstacle Avoidance:** Real-time processing of obstacle sensor data triggers immediate rerouting maneuvers to prevent collisions.
* **Complex Intersection Logic:** A custom decision-making algorithm evaluates maze junctions to determine the most efficient path toward the goal.
* **State-Machine Dispatcher:** A modular "Dispatcher" architecture manages transitions between operational states such as Forward, Reverse, and Turning.
* **Live Telemetry Output:** The system provides real-time status updates and operational data to a user interface during the run for performance monitoring.

## System Architecture
The software is structured into several high-level functional modules:
* **Central Dispatcher:** The "brain" of the program that evaluates inputs and branches to specific subroutines based on the current environment.
* **Sensor Fusion:** Dedicated logic for interpreting data from both the line-guider and proximity sensors simultaneously.
* **Low-Level Motor Control:** Optimized Assembly routines that handle the hardware-level timing and power distribution for the robot's movement.

## Video Demonstration
The following video showcases the robot's performance during a full-scale maze run, demonstrating its ability to handle sharp turns, dead ends, and obstacle detection without manual intervention.

[Link to Video Demonstration - Replace with your URL]

