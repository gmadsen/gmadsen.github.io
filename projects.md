---
layout: page
title: Projects
---

# Pick and Place Robot

- Built a fully functional 6 DOF robotic arm to autonomously stack blocks in various patterns
- Developed perception algorithms with OpenCV and Kinect
- Designed a gripper with Solidworks and 3D printing
- Used LCM and ROS for middleware communication of hardware and sensors

# Car Detection and Trajectory Planning

![alt text](/assets/img/bounding_box.png "Car Bounding Boxes")

- Trained convolution neural nets on unique data set of camera images and LIDAR  to detect number of cars in a scene and estimate 3D enclosing blocks
- Modeled various levels of car dynamics and implemented model predictive control reference tracking and obstacle avoidance for trajectories created from non linear optimization of a predefined course

# Robot Simulation Web Client

[Kinematic Evaluator](/kinematic_evaluator)
![alt text](/assets/img/pathfind_kineval.png "Car Bounding Boxes")

- Created a 3D interactive robotics simulation in threejs
- Implemented IK and FK algorithms for general urdf input files
- Implemented Path planning and obstacle avoidance algorithms(A*,PRM,RRT,RRT-connect, RRT*, potential fields, wavefront)
- Implemented  ROSBridge to directly communicate and command a fetch research robot through web interface

# Pendulum Arm Simulator

[Pendulum Simulator](/pendulum_simulator)

A three.js web app to simulate single and double pendulums. Various integration methods are implemented and PID gains and setpoints can be interactively set
