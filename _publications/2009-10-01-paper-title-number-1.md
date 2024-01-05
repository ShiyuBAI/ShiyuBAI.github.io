---
title: "A Curvature and Trajectory Optimization-based 3D Surface Reconstruction Pipeline for Ultrasound Trajectory Generation"
collection: publications_conference
permalink: /publication/2023-icra-surface-reconstruction
excerpt: 'This work introduces a Novel 3D surface reconstruction pipeline which feeds into automated ultrasound scanning trajectory
generation and comprehensive evaluation score for quantifying the quality of reconstructed point clouds.'
date: 2023-07-04
venue: 'IEEE International Conference on Robotics and Automation (ICRA) 2023'
citation: 'A. Bal, A. Gupta, F. Abhimanyu, J. Galeotti and H. Choset, ”A Curvature and Trajectory Optimization-based 3D Surface Reconstruction Pipeline for Ultrasound Trajectory Generation,” IEEE International Conference on Robotics and Automation (ICRA), London, UK, 2023, pp. 2724-2730'
---

In this paper, we present a novel pipeline for 3D Surface Reconstruction with an RGB-D sensor trajectory optimization module for automatic generation of ultrasound scanning trajectories. We eliminate human inputs by automatically finding the start and end scanning points for our RGB-D sensor. Then, we optimize the height of the sensor to produce the highest fidelity point cloud reconstruction of the subject. Lastly, we use the identified RoI and surface normals of the best 3D point cloud reconstruction from our optimization to generate an ultrasound scanning trajectory. This work is done in the context of scanning femoral vessels and we have designed the pipeline focusing on scanning the leg region. Our pipeline has been tested on a medical phantom and we have achieved near automation in optimized RGB-D and ultrasound scanning.

Our main contributions are:

- A novel 3D surface reconstruction pipeline which feeds into automated ultrasound scanning trajectory generation.
- A comprehensive evaluation score for quantifying the quality of reconstructed point clouds.
- An evolutionary algorithm-based real-time optimization module that determines the best trajectory for any RGB-D sensor for surface reconstruction.

[Link to the paper](https://ieeexplore.ieee.org/document/10161513)
