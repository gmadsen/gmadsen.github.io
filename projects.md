---
layout: page
title: Projects
---

# Pick and Place Robot                                                   
-	Built a fully functional 6 DOF robotic arm to autonomously stack blocks in various patterns
-	Developed perception algorithms with OpenCV and Kinect
-	Gripper design with Solidworks and 3D printing
-	hardware communication with LCM and ROS
# Car Detection and Trajectory Planning                                                   


![alt text](/assets/img/bounding_box.png "Car Bounding Boxes")
-	Trained convolution neural nets on unique data set of camera images and LIDAR  to detect number of cars in a scene and estimate 3D enclosing blocks 
-	Fully modeled car dynamics and implemented model predictive control  for trajectories created from non linear optimization of a predefined course
-	Implemented random obstacle avoidance in real time with trajectory libraries
# Robot Simulation web client                                                   
[Kinematic Evaluator](/kinematic_evaluator)
-	Implemented a robotics simulation in threejs for use on all modern web browsers  
-	Created  IK and FK algorithms for general urdf input files
-	Created Path planning and obstacle avoidance algorithms in high DOF system (potential fields,PRM,RRT)
-	Gripper design with Solidworks and 3D printing
-	Implemented a ROSBridge to directly communicate and command a fetch research robot through web interface
# Pendulum Arm Simulator
[Pendulum Simulator](/pendulum_simulator)
A three.js web app to simulate single and double pendulums. Various integration methods are implemented and PID gains and setpoints can be interactively set
