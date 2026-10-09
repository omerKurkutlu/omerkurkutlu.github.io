---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true

      name:
        size: md

      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '📚 My research'
      subtitle: ''
      text: |-
        I work on robot learning and Physical AI for autonomous systems. My research focuses on deep reinforcement learning, vision-language-action (VLA) models, vision-based navigation, and sim-to-real transfer for resource-constrained robots — from fully onboard navigation on palm-sized Crazyflie drones to multimodal policies for embodied robotics.

        I build simulation-to-deployment pipelines with NVIDIA Isaac Sim/Isaac Lab, ROS/ROS2, and embedded AI, and I am the developer of the open-source [Crazyflie Isaac Framework (CIF)](https://github.com/omerKurkutlu/Crazyflie-Isaac-Framework).
    design:
      columns: '1'

  - block: markdown
    content:
      title: '🎤 Research presentations'
      subtitle: ''
      text: |-
        - **IROS 2026 Late-Breaking Results** — *Lightweight 3D-Aware Navigation for Tiny Drones in Dynamic Mapless Environments*, poster presentation, Sep. 2026.
        - **DAC 2026 Young Fellows Program** — *Tiny Brain, Big World: Autonomous MCU-Friendly Navigation for Mapless Dynamic Environments*, poster presentation, Design Automation Conference, 2026.
        - **IROS 2023 Late-Breaking Results** — *Investigating the Impact of Spinal Joint Dynamics on a Sprawling Robot Using Deep Reinforcement Learning*, poster presentation, 2023.
    design:
      columns: '1'
---
