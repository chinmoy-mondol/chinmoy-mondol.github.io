---
title: "Real-Time Human Pose Estimation for Collaborative Robotics Using ROS 2 and Edge-Optimized Transformers"
collection: publications
category: submitted
permalink: /publication/2026-pose-estimation-collaborative-robotics
excerpt: ''
date: 2026-10-01
venue: '2027 7th International Conference on Electrical Engineering and Information &amp; Communication Technology (ICEEICT)'
location: 'Dhaka, Bangladesh'
citation: '<b>C. Mondol</b> et al., &quot;Real-Time Human Pose Estimation for Collaborative Robotics Using ROS 2 and Edge-Optimized Transformers,&quot; submitted to <i>2027 7th International Conference on Electrical Engineering and Information &amp; Communication Technology (ICEEICT)</i>, Dhaka, Bangladesh.'
---

**Abstract**

Safe and fluent human–robot collaboration hinges on the robot's ability to perceive the human body accurately and with low latency. We present a real-time human pose estimation pipeline for collaborative robotics built on ROS 2 and deployed on embedded edge accelerators. We compare five two-dimensional pose estimators—MediaPipe Pose (BlazePose GHUM), MoveNet Lightning, MoveNet Thunder, ViTPose-Tiny, and our edge-optimized ViTPose-Tiny-INT8—across three hardware platforms spanning the NVIDIA Jetson Nano, the Jetson Orin NX, and an Intel NUC with an RTX 3060. Our central contribution is a TensorRT INT8 quantization of the ViTPose-Tiny transformer, calibrated on 500 frames drawn from a real collaborative workspace, which attains an Object Keypoint Similarity (OKS@0.5) of 0.724 against the FP32 baseline of 0.741—a loss of only 1.7 points—while delivering a 2.8× inference speedup and 34.2 fps on the Jetson Orin NX. Around this perception front end we design a ROS 2 safety subsystem that lifts skeleton keypoints into three dimensions using aligned depth, evaluates intrusion against 3D safety volumes surrounding the robot workspace, and publishes violations as action goals that command slow-down and stop behaviors. On a custom dataset of 4,800 annotated frames from 8 participants performing 12 interaction scenarios, our system reaches a 97.3% zone-violation detection rate with 2.1% false positives and 1.4% false negatives, and an end-to-end reaction latency of 41.2 ± 5.3 ms. A study with 8 participants confirms that the transformer-based skeletons yield fewer spurious stops than a MediaPipe baseline (2.1% vs. 4.8% false positives) while being perceived as more responsive. Our results show that edge-optimized transformers are a practical foundation for vision-based safety in collaborative robotics.
