---
layout: page
title: "Heuclid"
description: Lightweight C++ geometry and vector math library for robotics — 2D/3D primitives, convex polygons, and spatial queries
img: assets/img/project_heuclid.jpg
importance: 7
category: opensource
related_publications: false
links:
  - name: GitHub
    url: https://github.com/bitroboticslab/Heuclid
    icon: fa-brands fa-github
---

**Language:** C++ | **Stars:** 3 | **Organization:** [bitroboticslab](https://github.com/bitroboticslab)

## Overview

A lightweight, header-friendly C++ geometry library providing essential 2D/3D primitives, convex polygon operations, and spatial queries for robotics applications. Designed as a foundational building block for motion planning and collision detection pipelines.

## Key Features

- **2D/3D geometric primitives**: points, vectors, lines, segments, polygons
- **Convex polygon operations**: intersection, containment, intersection area calculation
- **Spatial queries**: distance computation, point-in-polygon, polygon-polygon collision
- **Minimal dependencies**: Eigen-based, easy to integrate into existing robotics projects
- **CMake INTERFACE library**: header-only integration via `FetchContent`

## Technical Highlights

- Robust polygon intersection with convex decomposition support
- Numerical stability for edge cases in geometric computations
- Used as a dependency in AStarFootstepPlanner for terrain polygon operations

## My Role

Creator and core developer — designed the API, implemented all geometric algorithms, and maintained the library as a shared utility for the bitroboticslab project ecosystem.
