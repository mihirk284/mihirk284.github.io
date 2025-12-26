+++
title = "MIMOSA: A Multi-Modal SLAM Framework for Resilient Autonomy against Sensor Degradation"
description = "A Multi-Modal SLAM Framework for resilience against sensor degradation."
weight = 70
draft = false

[taxonomies]
tags = ["Autonomy", "Publications"]

[extra]
# local_image = "img/projects/mimosa.png"
+++
{{ youtube(id="S91GzCWBt2I") }}
{{ youtube(id="QDaqS7rL7kA") }}

**Authors**: N. Khedekar, M. Kulkarni and K. Alexis.

**Venue**: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2022.

### Abstract
This paper presents a framework for Multi-Modal SLAM (MIMOSA) that utilizes a nonlinear factor graph as the underlying representation to provide loosely-coupled fusion of any number of sensing modalities. Tailored to the goal of enabling resilient robotic autonomy in GPS-denied and perceptually-degraded environments, MIMOSA currently contains modules for pointcloud registration, fusion of multiple odometry estimates relying on visible-light and thermal vision, as well as inertial measurement propagation. A flexible back-end utilizes the estimates from various modalities as relative transformation factors. The method is designed to be robust to degeneracy through the maintenance and tracking of modality-specific health metrics, while also being inherently tolerant to sensor failure. We detail this framework alongside our implementation for handling high-rate asynchronous sensor measurements and evaluate its performance on data from autonomous subterranean robotic exploration missions using legged and aerial robots.

#### [Paper Link](https://doi.org/10.1109/IROS47612.2022.9981108) • [Code](https://github.com/ntnu-arl/mimosa) {.centered-text}
