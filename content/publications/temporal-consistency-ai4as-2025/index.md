---
title: "Lightweight Temporal Consistency for Grid-Based Obstacle Detection in Edge Devices"

publication_types:
  - paper-conference

authors:
  - Ömer Kurkutlu
  - Arman Roohi

date: 2025-09-01

publication: "IEEE International Conference on Autonomic Computing and Self-Organizing Systems Companion (ACSOS-C 2025)"

featured: true

summary: A lightweight obstacle detection framework that converts images into compact grid representations and introduces temporal smoothing for robust real-time perception on resource-constrained edge devices.

links:
  - name: PDF
    url: conference-paper.pdf
  - name: GitHub
    url: https://github.com/UIC-SIRIUS-Lab/Grid-Based-Obstacle-Detection-in-Edge-Devices
---

## Abstract

We present a lightweight obstacle detection framework designed for deployment on resource-constrained edge devices, ranging from desktop GPUs to Raspberry Pi and microcontrollers. Instead of relying on conventional object detection outputs, our method converts images into a compact **6 × 8 binary obstacle matrix** that enables efficient spatial reasoning for autonomous systems. To improve robustness against motion blur, occlusion, and lighting variations, we introduce a lightweight temporal smoothing mechanism that significantly enhances detection consistency while adding virtually no computational overhead. The framework is evaluated using YOLOv8n, SSD-MobileNet v2, and FOMO across multiple hardware platforms, demonstrating up to a **13.38 percentage point improvement in detection accuracy**, while matrix projection and smoothing together require **less than 0.1 ms** of additional processing time. The proposed approach provides an efficient perception module for edge AI, TinyML, autonomous robots, and micro-drones.