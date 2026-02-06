---
title: "Research"
layout: single
sitemap: true
permalink: /research/
author_profile: true
toc: true
toc_label: "Research"
toc_icon: "gear"
toc_sticky: true
---

My research lies at the intersection of deep learning, object detection, informative path planning, drones, search and rescue. Current and past research projects include:
- Navigation Systems for Search and Rescue with Drones (2022-26)
- Multi-Object Tracking using Multispectral Images in Forestry Environments - SEMFIRE - 2022
- Multiple Robots for Controlling and Observing Dynamical Phenomenon - MuRoPhen - 2020
- Autonomous Navigation and Tag Detection for IoT Applications - 2019
- Performance Evaluation of Various QRS Detection Algorithms - 2016

## Navigation Systems for Search and Rescue with Drones (2022-26)

<figure>
  <img src="/assets/images/nsfsrd.PNG" width="1000px" alt="">
  <figcaption>Person Detection in Drone-based Search and Rescue in Forest Environments
</figure>

- Goal is to develop and integrate the novel informative planning and detection system for drone‑based missing person searches in the wilderness.
- Proposed hybrid YOLO‑Transformers and Retention, achieved the robustness over 30% for tiny and small aerial person detection.
- Working on UAV informative path planning approaches for effective search, deployment on ROS + NVIDIA Jetson with field experiments.

[Video-1](https://youtu.be/wa7ZPiVeVA8)

## Multi-Object Tracking using Multispectral Images in Forestry Environments - SEMFIRE - 2022

<figure>
  <img src="/assets/images/hybrid_climate_modeling.png" width="1000px" alt="">
  <figcaption>A hybrid climate model combines a traditional dynamical core with machine-learned parameterizations.
</figcaption>
</figure>

<figure>
  <img src="/assets/images/semfire.png" width="1000px" alt="">
  <figcaption>Tracking Persons in the Forests using Multispectral Images
</figcaption>
</figure>

- Goal was to develop artificial perception mechanisms supporting forestry ground robotic operations for land maintenance and clearance.
- Extended work to 2D Dynamic Entity Tracking with Multispectral Images to dockers, dataset labelling, and Stereo‑3D‑Reconstruction in ROS.
- Project: Safety, Exploration and Maintenance of Forests with the Integration of Ecological Robotics (SemFire)

[Video-2](https://youtu.be/IQaL3qS-bVM)

## Multiple Robots for Controlling and Observing Dynamical Phenomenon - MuRoPhen - 2020

<figure>
  <img src="/assets/images/oadltracking.jpeg" width="1000px" alt="">
  <figcaption> Mathematical Modelling for Occlusion Avoidance
</figcaption>
</figure>

<figure>
  <img src="/assets/images/detection.jpg" width="1000px" alt="">
  <figcaption>Deep Learning-based Object Detection
</figcaption>
</figure>

- Goal was to integrate a vision‑based system on a pair of quadrotor and a rover, and develop algorithms to track another moving quadrotor outdoors.
- Designed a novel approach for Occlusion Avoidance by Mathematical Modelling, surveyed literature for learning approaches in tracking, and benchmarked Convolutional Neural Networks with two PC configurations, CPU and GPUs.
- Project: Control of Multi‑Robot Systems for Observing Dynamical Phenomena (MuRoPhen)

[Video-3](https://youtu.be/o_03c37iEzY)

## Autonomous Navigation and Tag Detection for IoT Applications - 2019

<figure>
  <img src="/assets/images/ros2.png" alt="">
  <figcaption>  Turtlebot with mounted Kinect does Tag Detection and as connected to NodeMCU(Wifi Module) turns LED for ON/OFF 
</figcaption>
</figure>

- Requirements: Turtlebot with mounted Kinect connected to Workstation, NodeMCU(Wifi Module), LED for ON/OFF mounted on NodeMCU. 

- Tasks: Navigate the Turtlebot and Building Map in the real world environment. Use Saved Map for navigating to set positions. On launching from the workstation, turtlebot starts from a pre-defined initial position. Move to Points P1. Read Augmented Reality (AR) Tag1. Then move to point P2 and read AR Tag2. Move to Point P3. Read QR code qr1 which lights LED ON through a popup Webserver (IoT Application). Move to Point P4. Read QR code qr0 which lights OFF LED through another popup Webserver (IoT Application). Return Turtlebot to initial position after all the tasks are done.

- Software Tools: ROS, Python, Ubuntu 16.04, Kinetic Kame

[Video-4](https://youtu.be/rtxCUmQBTSE)

## Performance Evaluation of Various QRS Detection Algorithms - 2016

<figure>
  <img src="/assets/images/peovqda.PNG" alt="">
  <figcaption> Extraction of QRS for applying Detection Algorithms
</figcaption>
</figure>

Biomedical signals encode physiological events, and effective diagnosis relies on detecting and analyzing signal epochs associated with these events. The electrocardiogram (ECG), a non-stationary bioelectrical signal representing the heart’s electrical activity over time, is a critical tool for assessing cardiac function and identifying arrhythmias—irregular heart rhythms that may be benign or life-threatening, potentially leading to stroke or sudden cardiac death. Because arrhythmias occur unpredictably and intermittently, automatic detection and classification are essential, particularly in intensive care settings. In this work, ECG signals from the MIT-BIH Arrhythmia Database are preprocessed using established algorithms for noise removal and feature extraction, enabling the analysis of waveform characteristics such as amplitude, morphology, timing, and frequency content. A MATLAB-based simulation tool is developed to detect ECG abnormalities, demonstrating how computerized signal processing facilitates accurate and efficient analysis, with future scope extending to real-time transmission and processing using DSP hardware or wireless communication technologies.

[Video-5](https://youtu.be/9EPpOsKq2hE)
