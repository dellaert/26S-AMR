---
layout: default
title: Projects
---

# Projects
## P1: Underwater Robot Localization
Implement an Invariant Extended Kalman Filter (IEKF) to localize a simulated underwater robot using IMU (prediction) and Range Sensor measurements (correction). Implement simple trajectory tracking control.

## P2: Legged Robot Kinematic Estimation & MPC
Estimate legged robot state (kinematic only) using joint encoders + IMU via factor graphs (with IMU preintegration). Implement predictive sampling MPC for motion control (e.g., similar to Mujoco).

## P3: Single Robot Pose SLAM & Maze Exploration
Implement Factor Graph-based Pose SLAM for a differential drive robot using scan matching from rectified camera images (simulated 2D scans). Implement frontier-based exploration for planning. (No IMU in this assignment).

## P4: LiDAR-Inertial Odometry (LIO)
Process drone data (IMU+LiDAR) to implement a tightly-coupled LIO system using factor graphs, including IMU preintegration, 3D ICP, and handling motion distortion (deskewing/CT-SLAM concepts).

## P5: Multi-Robot Pose SLAM with IMU
Extend Pose SLAM factor graph to include IMU factors (using preintegration from Assign 2) and factors representing range measurements between robots. Explore basic multi-robot coordination for exploration/rendezvous.


