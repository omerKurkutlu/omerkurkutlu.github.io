---
title: "LiMPNet: Lightweight Multi-sensor Perception and DRL Navigation for Tiny Drones in Mapless Environments"

publication_types:
  - paper-conference

authors:
  - Ömer Kurkutlu
  - Arman Roohi

date: 2025-11-01

publication: "AAAI Fall Symposium Series (FSS 2025)"

featured: true

summary: Lightweight multi-sensor perception and deep reinforcement learning framework for autonomous mapless navigation of resource-constrained tiny drones.

links:
  - name: PDF
    url: conference-paper.pdf
---

## Abstract

Autonomous tiny drones are severely constrained by size, weight, power, and onboard computation, making reliable autonomous navigation particularly challenging. This work presents **LiMPNet**, a lightweight navigation framework that combines monocular vision, laser range sensing, and deep reinforcement learning to enable safe mapless navigation in cluttered environments. The system integrates a YOLOv8n-based obstacle detector, multi-ranger distance sensing, IMU-based state estimation, and a PPO navigation policy within a ROS and Gazebo simulation framework. Experimental results demonstrate reliable autonomous obstacle avoidance using only lightweight sensors, achieving a **100% success rate (112/112)** in a simple environment and **35% success (7/20)** in a densely cluttered environment. These results demonstrate that efficient autonomous navigation is feasible on highly resource-constrained aerial robots while maintaining low computational complexity.