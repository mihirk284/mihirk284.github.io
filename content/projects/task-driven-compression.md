+++
title = "Task-driven Compression for Collision Encoding"
description = "Task-driven compression method for collision encoding based on depth images."
weight = 55
draft = false

[taxonomies]
tags = ["Compression", "Collision Encoding", "Depth Images", "Publications"]

[extra]
# local_image = "img/projects/task-driven-compression.png"
+++

**Authors**: M. Kulkarni and K. Alexis.

**Venue**: International Symposium on Visual Computing (ISVC) 2023.

### Abstract
This paper contributes a novel learning-based method for aggressive task-driven compression of depth images and their encoding as images tailored to collision prediction for robotic systems. A novel 3D image processing methodology is proposed that accounts for the robot's size in order to appropriately "inflate" the obstacles represented in the depth image and thus obtain the distance that can be traversed by the robot in a collision-free manner along any given ray within the camera frustum. Such depth-and-collision image pairs are used to train a neural network that follows the architecture of Variational Autoencoders to compress-and-transform the information in the original depth image to derive a latent representation that encodes the collision information for the given depth image. We compare our proposed task-driven encoding method with classical task-agnostic methods and demonstrate superior performance for the task of collision image prediction from extremely low-dimensional latent spaces. A set of comparative studies show that the proposed approach is capable of encoding depth image-and-collision image tuples from complex scenes with thin obstacles at long distances better than the classical methods at compression ratios as high as 4050:1.

#### [Paper Link](https://doi.org/10.48550/arXiv.2309.05289) {.centered-text}
