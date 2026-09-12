---
title: "PID Control Optimization and Trajectory Tracking for Autonomous Differential Drive Robots"
group: "research"
period: "IEEE MIT Undergraduate Research Technology Conference | Presented October 2025"
summary: "Co-authored research on non-linear PID control, path planning, ROS GazeboSim obstacle avoidance, and Vicon-validated tracking."
paper_url: "https://ieeexplore.ieee.org/document/11533106"
extended_url: "https://drive.google.com/file/d/18ED5a_aI4rQM_JSxM_MhHVoMt1Xh2ltn/view"
video_url: "https://youtu.be/6KWDjNa425o"
---

## Problem

Low-cost differential-drive robots need to follow planned paths while their dynamics change with speed, surface resistance, and obstacles. We asked whether a more adaptive PID controller could improve tracking without expensive hardware.

## Experiments

We built a non-linear PID controller with moving integral windows, velocity-dependent target yaws, and anti-windup limits. We compared A* and Dijkstra path generation and modeled LiDAR obstacle avoidance in ROS GazeboSim. We then tested the controller on a TurtleBot with Vicon motion capture at the Emil Buehler Aerospace Lab.

## Innovation

The controller adjusted its integral behavior and target heading as robot velocity changed. This reduced the limits of a fixed-gain controller while keeping the design practical for low-cost hardware.

## Results and conclusion

We validated the controller with matched-pairs tests at p &lt; 0.01. The results supported the use of low-cost autonomous differential-drive hardware and showed that the controller could improve path tracking under changing conditions.