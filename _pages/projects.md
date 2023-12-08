---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

- **Learning-based informative path planning** (Jan. 2022 - Oct. 2023)

  Utilize information theory and machine learning techniques to guide the robots to explore unknown and unstructured environments autonomously under the constraints of the real world. Our work mainly focuses on introducing more advanced learning techniques to handle the challenge of exploration and exploitation in robotic active sensing, as well as computational efficiency. (*Accepted by IEEE RA-L 2023, submitted to MSSP & IEEE TCAS-II*)

- **Information-based robot exploration with pose uncertainty** (Jul. 2021 - Dec. 2021)

  Previous works concerned more about active mapping/exploration with known poses or utilize inaccurate information metrics, resulting in imbalanced exploration. We propose a Rao-Blackwellized particle filter-based confidence-rich localization and mapping (RBPF-CRLM) scheme with a new closed-form weighting method. We further compute the uncertain CRMI (UCRMI) with the weighted particles by a more accurate approximation. The localization accuracy and exploration performance of the proposed methods are shown in the unstructured environments. (*Accepted by IEEE IROS 2022 and conditionally accepted by IEEE T-ASE*)

- **Information-theoretic mapping for range sensing robots** (Sept. 2020 - June 2021)

  Traditional works based on hand-engineered inverse sensor model (ISM) mapping or kernel inference methods lead to imbalanced accuracy and efficiency. We propose a new approach to compute mutual information more accurately, based on the continuous belief distribution over the occupancy map and called confidence-rich mutual information (CRMI). Extensive simulations and experiments show the desired exploratory behavior to unexplored and obscured regions for CRMI-based robot controllers in the unstructured and cluttered scene, even in large scale environment. (*Accepted by both IEEE RA-L and IEEE IROS 2021*) [[Code for CRMI]](https://github.com/Shepherd-Gregory/CRMI), [[Code for CRM]](https://github.com/Shepherd-Gregory/confidence_rich_mapping)

- **Imaging sonar-based underwater SLAM** (Jul. 2019 - Aug. 2020)

  The sparsity of underwater acoustic features and the loss of elevation angle in sonar images impose degeneracy cases in feature-based SLAM. We proposes a robust imaging sonar SLAM approach based on sonar keyframes (SKFs) and an elastic sliding window optimization framework to handle these degeneracy cases. (*Accepted by IEEE/MTS OCEANS 2020 and IEEE Trans. on Instrumentation & Measurement 2022*)

- **ROS simulator for underwater robotics** (Jul. 2019 - Apr. 2020)

  A simulator for underwater vehicles mounted with different sensors, such as sonar, camera and IMU.
