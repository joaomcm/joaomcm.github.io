---
title: "On the Overconfidence Problem in Semantic 3D Mapping"
collection: publications
permalink: /publication/2024-05-15-overconfidence-problem-3d-mapping
excerpt: 'Semantic 3D mapping, the process of fusing depth and image segmentation information between multiple views to build 3D maps annotated with object classes in real-time, is a recent topic of interest. This paper highlights the fusion overconfidence problem, in which conventional mapping methods assign high confidence to the entire map even when they are incorrect, leading to miscalibrated outputs. Several methods to improve uncertainty calibration at different stages in the fusion pipeline are presented and compared on the ScanNet dataset.  We show that the most widely used Bayesian fusion strategy is among the worst calibrated, and propose a learned pipeline that combines fusion and calibration, GLFS, which achieves simultaneously higher accuracy and 3D map calibration while retaining real-time capability and adding only 525 learned parameters to the pipeline. We further illustrate the importance of map calibration on a downstream task by showing that incorporating proper semantic fusion to an indoor object search agent improves its success rates.'
date: 2024-05-15
venue: 'International Conference on Robotics and Automation (ICRA) 2024'
paperurl: 'https://arxiv.org/abs/2311.10018'
citation: 'Marques, J.M.C., Zhai, A., Wang, S. and Hauser, K., (2024). On the Overconfidence Problem in Semantic 3D Mapping”, 2024 IEEE International Conference on Robotics and Automation (ICRA)'

---
Semantic 3D mapping, the process of fusing depth and image segmentation information between multiple views to build 3D maps annotated with object classes in real-time, is a recent topic of interest. This paper highlights the fusion overconfidence problem, in which conventional mapping methods assign high confidence to the entire map even when they are incorrect, leading to miscalibrated outputs. Several methods to improve uncertainty calibration at different stages in the fusion pipeline are presented and compared on the ScanNet dataset.  We show that the most widely used Bayesian fusion strategy is among the worst calibrated, and propose a learned pipeline that combines fusion and calibration, GLFS, which achieves simultaneously higher accuracy and 3D map calibration while retaining real-time capability and adding only 525 learned parameters to the pipeline. We further illustrate the importance of map calibration on a downstream task by showing that incorporating proper semantic fusion to an indoor object search agent improves its success rates.

[Download paper here](https://joaomcm.github.io/files/ICRA2024_Overconfidence_Problem.pdf)
