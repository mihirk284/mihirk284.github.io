+++
title = "Reinforcement Learning for Collision-free Flight"
description = "Exploiting Deep Collision Encoding for autonomous flight in dense environments."
weight = 4
draft = false

[taxonomies]
tags = ["Reinforcement Learning", "Autonomy", "Aerial Robotics", "Publications"]

[extra]
# local_image = "img/projects/collision-encoding.png"
+++

{{ youtube(id="gPrT21sbpTY") }}
{{ youtube(id="IpGAmW7ZevY") }}

**Authors**: M. Kulkarni and K. Alexis.

**Venue**: IEEE International Conference on Robotics and Automation (ICRA) 2024.

### Abstract
This work contributes a novel deep navigation policy that enables collision-free flight of aerial robots based on a modular approach exploiting deep collision encoding and reinforcement learning. The proposed solution builds upon a deep collision encoder that is trained on both simulated and real depth images using supervised learning such that it compresses the high-dimensional depth data to a low-dimensional latent space encoding collision information while accounting for the robot size. This compressed encoding is combined with an estimate of the robot's odometry and the desired target location to train a deep reinforcement learning navigation policy that offers low-latency computation and robust sim2real performance. A set of simulation and experimental studies in diverse environments are conducted and demonstrate the efficiency of the emerged behavior and its resilience in real-life deployments.

#### [Paper Link](https://doi.org/10.48550/arXiv.2402.03947) {.centered-text}
