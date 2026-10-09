---
title: "Edge Perception & Temporal Consistency"
summary: Lightweight TinyML perception for resource-constrained edge platforms, including temporally consistent obstacle detection and energy-aware sensing.

date: 2026-07-01

authors:
  - me

tags:
  - TinyML
  - Edge AI
  - Embedded AI
  - Object Detection
  - Computer Vision

featured: true

links:
  - name: GitHub
    url: https://github.com/UIC-SIRIUS-Lab/Grid-Based-Obstacle-Detection-in-Edge-Devices
---

## Overview

This project develops lightweight perception for resource-constrained edge platforms, from Raspberry Pi to microcontrollers. Images are converted into a compact grid-based obstacle representation, and a lightweight temporal smoothing mechanism improves detection consistency under motion blur, occlusion, and lighting changes with virtually no computational overhead.

## Key Features

- Temporally consistent, grid-based obstacle detection
- Embedded inference with YOLOv8n, SSD-MobileNet v2, and FOMO
- BLE communication and energy-aware sensing
- Deployment across desktop GPUs, Raspberry Pi, and MCUs

## Related Publication

- *Lightweight Temporal Consistency for Grid-Based Obstacle Detection in Edge Devices.* O. Kurkutlu and A. Roohi. IEEE ACSOS-C, 2025.
