---
layout: page
title: "BitbotDeploy"
description: Sim-to-real deployment framework for legged robots — bridging simulation-trained policies to real hardware
img: assets/img/project_bitbotdeploy.jpg
importance: 9
category: opensource
related_publications: false
links:
  - name: GitHub
    url: https://github.com/bitroboticslab/BitbotDeploy
    icon: fa-brands fa-github
---

**Language:** C++ / Python | **Organization:** [bitroboticslab](https://github.com/bitroboticslab)

## Overview

A sim-to-real deployment framework designed to bridge the gap between simulation-trained locomotion policies and real-world legged robot hardware. Provides a unified pipeline for policy export, real-time inference, and hardware interface abstraction.

## Key Features

- **Unified deployment pipeline**: from Isaac Gym/Sim trained policies to real hardware execution
- **Hardware abstraction layer**: support for multiple robot platforms (custom humanoids, Unitree, etc.)
- **Real-time control loop**: deterministic timing with RTOS integration
- **Safety layer**: joint limit enforcement, emergency stop, and graceful degradation

## Technical Highlights

- C++ core for real-time performance, Python interface for configuration and monitoring
- EtherCAT communication protocol support for high-frequency motor control
- Modular architecture for easy adaptation to new robot platforms
- Extensive experience from deploying on 10+ robot hardware platforms

## My Role

Creator and lead developer — designed the architecture based on real-world deployment experience across multiple humanoid and legged robot platforms.
