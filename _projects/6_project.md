---
layout: page
title: "AStarFootstepPlanner"
description: A* footstep planner for humanoid robots — optimal footstep sequences on complex terrain with kinematic constraints
img: assets/img/project_astar.jpg
importance: 6
category: opensource
related_publications: false
links:
  - name: GitHub
    url: https://github.com/bitroboticslab/AStarFootstepPlanner
    icon: fa-brands fa-github
---

**Language:** C++ | **Stars:** 6 | **Organization:** [bitroboticslab](https://github.com/bitroboticslab)

## Overview

An A*-based footstep planner for humanoid robots that finds optimal footstep sequences on complex terrain while respecting kinematic constraints. Designed for real-time planning in unstructured environments.

## Key Features

- **A* search** with kinematic feasibility constraints for humanoid footstep planning
- **Complex terrain support**: stairs, slopes, gaps, and mixed terrain types
- **Configurable cost maps** with terrain-aware obstacle handling
- **Real-time performance** optimized for on-board deployment
- **Modular architecture**: clean separation between search, heuristic, and constraint modules

## Technical Highlights

- C++ with CMake build system, cross-platform support
- Kinematic reachability modeling for leg constraint validation
- Multi-resolution search for efficiency on large-scale terrain maps
- Comprehensive test suite and demo visualizations (Python/matplotlib)

## My Role

Core developer — designed the search algorithm, kinematic constraint module, and integration with the robot's perception pipeline.
