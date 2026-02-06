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

* **Goal** is to develop and integrate the novel informative planning and detection system for drone‑based missing person searches in the wilderness.
* **Proposed** hybrid YOLO‑Transformers and Retention, achieved the robustness over 30% for tiny and small aerial person detection.
* **Working** on UAV informative path planning approaches for effective search, deployment on ROS + NVIDIA Jetson with field experiments.


[Video-1](https://youtu.be/wa7ZPiVeVA8)

## Multi-Object Tracking using Multispectral Images in Forestry Environments - SEMFIRE - 2022

<figure>
  <img src="/assets/images/semfire.png" width="1000px" alt="">
  <figcaption>Tracking Persons in the Forests using Multispectral Images
</figcaption>
</figure>

* **Goal** was to integrate a vision‑based system on a pair of quadrotor and a rover, and develop algorithms to track another moving quadrotor outdoors.
* **Designed** a novel approach for Occlusion Avoidance by Mathematical Modelling, surveyed literature for learning approaches in tracking, and benchmarked Convolutional Neural Networks with two PC configurations, CPU and GPUs.
* **Project:** Control of Multi‑Robot Systems for Observing Dynamical Phenomena (MuRoPhen)

[Video-3](https://youtu.be/o_03c37iEzY)

## Ocean Mesoscale Eddies and their Parameterizations

<figure>
  <img src="/assets/images/KE.png" width="1000px" alt="">
  <figcaption>Left: The kinetic energy field in NeverWorld2: a high-resolution idealized model that I used for studying the ocean energy cycle.
Right: A schematic of the ocean energy cycle.
</figcaption>
</figure>

Ocean mesoscale eddies are energetic motions that have horizontal scales of tens to hundreds of kilometers.
Despite their relatively small scale, these eddies play an important role in transporting momentum, heat, salt, carbon, and nutrients throughout the world's oceans.

My research focused on the energy cycle of the ocean mesoscale eddy field: its generation, its interaction with the large-scale flow, and its dissipation. 
To investigate this cycle, I used high-resolution ocean models, aiming to improve the representation of mesoscale processes in global ocean models.

Additionally, I studied, implemented, and compared different mesoscale eddy parameterizations—specifically, Gent & Williams (1990) and Greatbatch & Lamb (1990)—from both theoretical and numerical modeling perspectives. 
My research explored how these parameterizations interact with the ocean model's vertical coordinate system, providing insights into the consistency between theoretical frameworks and numerical implementations.

Related publications: [Loose et al.](https://doi.org/10.1175/JPO-D-22-0083.1), JPO (2022);
[Loose et al.](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2022MS003518), JAMES (2023);
[Marques, Loose et al.](https://gmd.copernicus.org/articles/15/6567/2022/), GMD (2022). 

## Adjoint Modeling in the North Atlantic

<figure>
  <img src="/assets/images/sensitivity_teleconnections.png" alt="">
  <figcaption> 
Left: Near-surface currents that are the mediator of oceanic teleconnections in the North Atlantic.
Right: An adjoint-derived sensitivity map that highglights ''sensitive spots'' where wind anomalies can trigger heat transport anomalies across the Iceland-Scotland ridge (yellow-black line) months or years later.  
</figcaption>
</figure>

The seas around Greenland, Iceland, and Norway transport heat from the North Atlantic toward the Arctic.
I used adjoint-derived sensitivities in the [ECCO](https://ecco-group.org/) state estimate to identify drivers and locations that affect ocean heat transport in this region. Due to oceanic teleconnections, high-latitude heat transport is sensitive to local and remote(!) wind forcing.

Related publications:
[StoryMap](https://www.ecco-group.org/storymaps.htm?id=43);
 [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020);
Loose, [PhD Dissertation](http://bora.uib.no/handle/1956/24456), 2019.


## Uncertainty Quantification & Observing System Design

<figure>
  <img src="/assets/images/QND.png" alt="">
  <figcaption> 
The Global Ocean Observing System (GOOS) consists of an eclectic mix of satellite and in-situ platforms. Designing optimal observing strategies that account for complementarity and redundancy of observational assets is an unsolved scientific and computational challenge.
</figcaption>
</figure>

Ocean observing systems are expensive to build and maintain, and therefore have to be designed carefully. Important questions to consider include:
- What dynamical information is contained in already existing observation networks? 
- What is the optimal instrument configuration, which is both cost-efficient and capable to monitor key processes and ocean variability?

To tackle these questions, I performed quantitative observing system design, through a combination of Bayesian inverse methods and uncertainty quantification in a data assimilation framework. By means of these computational tools, quantitative observing system design suggests an optimal observing strategy and supports effective instrument placements in the future.

Related publications: [Loose et al.](https://doi.org/10.1029/2020JC016112), J. Geophys. Res (2020); 
[Loose and Heimbach](https://doi.org/10.1029/2020MS002386), JAMES (2021);
[Fujii et al.](https://www.frontiersin.org/articles/10.3389/fmars.2019.00417/full), Front. Mar. Sci. (2019).
[v. Schuckman et al.](https://doi.org/10.1016/j.marpol.2025.106922), Marine Policy (2025).

## Development of Open Source Software Tools

I am engaged with developing open-source software tools in Python and Julia to enable our Earth Science community to perform data analysis and modeling in an efficient and reproducible way. 
I have led the development of two open-source Python packages: [GCM-Filters](https://gcm-filters.readthedocs.io/en/latest/) and [ROMS-Tools](https://roms-tools.readthedocs.io/en/latest/).

<figure>
  <img src="/assets/images/roms_grid.png" alt="">
  <figcaption> 
A ROMS grid created with the open-source Python package ROMS-Tools.
</figcaption>
</figure>
`ROMS-Tools` is a Python package for creating the input files that are necessary to run a ROMS simulation. This includes creating a grid, tidal, boundary, and atmospheric forcings, initial conditions, and more! 

<figure>
  <img src="/assets/images/filter_intro.png" alt="">
  <figcaption> 
Filtering surface relative vorticity from a global 0.1 degree MOM6 simulation with the open-source Python package GCM-Filters.
</figcaption>
</figure>
`GCM-Filters` is a Python package that allows scientists to perform spatial filtering analysis in an easy, flexible, efficient, and reproducible way. `GCM-Filters` is designed to work with gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. 
Check out [this presentation](https://noraloose.github.io/ams2022-talk) on GCM-Filters!

Related publications: [Loose et al.](https://doi.org/10.21105/joss.03947), JOSS (2022); 
[Grooms, Loose et al.](https://doi.org/10.1029/2021MS002552), JAMES (2021).

