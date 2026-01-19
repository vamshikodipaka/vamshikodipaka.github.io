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

My research lies at the intersection of deep learning, person detection, informative path planning, drones, search and rescue. Current and past research projects include:
- Navigation Systems for Search and Rescue with Drones 
- Safety, Exploration and Maintenance of Forests with Ecological Robotics (SEMFIRE)
- Control of Multi‑Robot Systems for Observing Dynamical Phenomena (MuRoPhen)
- Vision‑based Multi‑robot Target Tracking with Aerial and Ground Robots
- Performance evaluation of Various QRS Detection Algorithms


## Navigation Systems for Search and Rescue with Drones - (2022-26)

<figure>
  <img src="/assets/images/nsfsrd.PNG" width="1000px" alt="">
  <figcaption> Navigation Systems for Search and Rescue with Drones
</figcaption>
</figure>

• Goal is to develop and integrate the novel informative planning and detection system for drone‑based missing person searches in the wilderness.

• Proposed hybrid YOLO‑Transformers and Retention, achieved the robustness over 30% for tiny and small aerial person detection.

• Working on UAV informative path planning approaches for effective search, deployment on ROS + NVIDIA Jetson with field experiments. 

[Video1](https://youtu.be/wa7ZPiVeVA8)


## Safety, Exploration and Maintenance of Forests with Ecological Robotics (SEMFIRE) - 2022

<figure>
  <img src="/assets/images/semfire.png" width="1000px" alt="">
  <figcaption>Dynamic Entity Tracking with Multispectral Images in Forestry Environments
</figcaption>
</figure>

• Goal was to develop artificial perception mechanisms supporting forestry ground robotic operations for land maintenance and clearance.

• Extended work to 2D Dynamic Entity Tracking with Multispectral Images to dockers, dataset labelling, and Stereo‑3D‑Reconstruction in ROS. 

[Video2](https://youtu.be/IQaL3qS-bVM)


## Control of Multi‑Robot Systems for Observing Dynamical Phenomena (MuRoPhen) - 2020

<figure>
  <img src="/assets/images/oadltracking.jpeg" width="1000px" alt="">
  <figcaption> Vision‑based Multi‑robot Target Tracking with Aerial and Ground Robots - 1
</figcaption>
</figure>

<figure>
  <img src="/assets/images/detection.jpg" width="1000px" alt="">
  <figcaption> Vision‑based Multi‑robot Target Tracking with Aerial and Ground Robots - 2
</figcaption>
</figure>

• Goal was to integrate a vision‑based system on a quadrotor and a rover, and develop algorithms to track another moving quadrotor outdoors.

• Designed a novel approach for Occlusion Avoidance by Mathematical Modelling, surveyed literature for learning approaches in tracking, and
benchmarked Convolutional Neural Networks with PC configurations, CPU and GPUs.

[Video3](https://youtu.be/o_03c37iEzY)


## ROS Project: Autonomous Navigation and Tag Detection for IoT Applications - 2019

<figure>
  <img src="/assets/images/ros2.png" width="1000px" alt="">
  <figcaption> Autonomous Navigation and Tag Detection for IoT Applications
</figcaption>
</figure>

Requirements: Turtlebot with mounted Kinect connected to Workstation, NodeMCU(Wifi Module), LED for ON/OFF mounted on NodeMCU.  

Tasks:
1. Navigate the Turtlebot and Building Map in the real world environment
2. Use Saved Map for navigating to set positions. On launching from the workstation, turtlebot starts from a pre-defined initial position
3. Move to Points P1. Read Augmented Reality (AR) Tag1. Then move to point P2 and read AR Tag2
4. Move to Point P3. Read QR code qr1 which lights LED ON through a popup Webserver (IoT Application)
5. Move to Point P4. Read QR code qr0 which lights OFF LED through another popup Webserver (IoT Application)
6. Return Turtlebot to initial position after all the tasks are done.

Software Tools: ROS, Python, Ubuntu 16.04, Kinetic Kame
[Video4](https://www.youtube.com/watch?v=rtxCUmQBTSE)


## Performance evaluation of Various QRS Detection Algorithms - 2016

<figure>
  <img src="/assets/images/peovqda.PNG" width="1000px" alt="">
  <figcaption> Performance evaluation of Various QRS Detection Algorithms
</figcaption>
</figure>

Biomedical signals contain characteristic patterns associated with physiological events, known as epochs, whose identification and analysis are essential for monitoring and diagnosis. In electrocardiography (ECG), a non-stationary bioelectrical signal that records the heart’s electrical activity over time, detecting such events is crucial for identifying arrhythmias—irregular heart rhythms that may be benign or indicate serious conditions such as stroke or sudden cardiac death. Because arrhythmias can occur unpredictably, automatic ECG-based arrhythmia classification is especially important in clinical cardiology and intensive care. In this work, ECG signals from the MIT-BIH Arrhythmia Database are preprocessed using established algorithms for noise removal and feature extraction, and a MATLAB-based simulation tool is implemented to detect ECG abnormalities. Efficient computerized signal-processing techniques enable accurate analysis and characterization of ECG signals, with future research extending to real-time transmission and reception of ECG data using DSP processors or wireless technologies such as Bluetooth or ZigBee to improve accessibility and reliability.
[Video5](https://www.youtube.com/watch?v=9EPpOsKq2hE)
