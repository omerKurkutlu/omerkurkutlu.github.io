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
        My research focuses on autonomous robotic systems, with an emphasis on vision-based navigation, tiny drones, deep reinforcement learning, TinyML, and embedded AI. I work on building perception-to-action pipelines that allow resource-constrained robots to sense their environment, avoid obstacles, and navigate safely in dynamic environments.

        I am particularly interested in autonomous tiny drones, edge AI, vision-language-action models, and learning-based control methods that can move from simulation to real-world deployment.
    design:
      columns: '1'
---