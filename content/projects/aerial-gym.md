+++
title = "Aerial Gym Simulator"
description = "A framework for highly parallelized simulation of aerial robots based on NVIDIA Isaac Gym."
weight = 1
draft = false

[taxonomies]
tags = ["Simulation and Rendering", "Reinforcement Learning", "Autonomy", "Aerial Robotics", "Publications"]

[extra]
local_image = "img/projects/aerial-gym.jpg"
+++

{{ youtube(id="VBVBQNtHZoc") }}

**Authors**: M. Kulkarni, W. Rehberg and K. Alexis.

**Venue**: IEEE Robotics and Automation Letters (RA-L) 2025.

### Abstract
This paper contributes the Aerial Gym Simulator, a highly parallelized, modular framework for simulation and rendering of arbitrary multirotor platforms based on NVIDIA Isaac Gym. Aerial Gym supports the simulation of under-, fully- and over-actuated multirotors offering parallelized geometric controllers, alongside a custom GPU-accelerated rendering framework for ray-casting capable of capturing depth, segmentation and vertex-level annotations from the environment. Multiple examples for key tasks, such as depth-based navigation through reinforcement learning are provided. The comprehensive set of tools developed within the framework makes it a powerful resource for research on learning for control, planning, and navigation using state information as well as exteroceptive sensor observations. Extensive simulation studies are conducted and successful sim2real transfer of trained policies is demonstrated.

#### [GitHub Repository](https://github.com/ntnu-arl/aerial_gym_simulator) • [Paper Link](https://doi.org/10.1109/LRA.2025.3548507) {.centered-text}
