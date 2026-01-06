+++
title = "Neural Control Barrier Functions for Safe Navigation"
description = "Safe navigation using Neural Control Barrier Functions (NCBFs) for aerial robots."
weight = 40
draft = false

[taxonomies]
tags = ["Autonomy", "Aerial Robotics", "Publications"]

[extra]
local_image = "img/projects/ncbf.jpg"
+++

{{ youtube(id="1id0C6jiFEg") }}

**Authors**: M. Harms, M. Kulkarni, N. Khedekar, M. Jacquet, K. Alexis.

**Venue**: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2024.

### Abstract
Autonomous robot navigation can be particularly demanding, especially when the surrounding environment is not known and safety of the robot is crucial. This work relates to the synthesis of Control Barrier Functions (CBFs) through data for safe navigation in unknown environments. A novel methodology to jointly learn CBFs and corresponding safe controllers, in simulation, inspired by the State Dependent Riccati Equation (SDRE) is proposed. The CBF is used to obtain admissible commands from any nominal, possibly unsafe controller. An approach to apply the CBF inside a safety filter without the need for a consistent map or position estimate is developed. Subsequently, the resulting reactive safety filter is deployed on a multirotor platform integrating a LiDAR sensor both in simulation and real-world experiments.

#### [Paper Link](https://doi.org/10.1109/IROS58592.2024.10802694) {.centered-text}
