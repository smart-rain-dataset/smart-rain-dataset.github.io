---
layout: archive
title: "Datasets"
permalink: /datasets/
author_profile: true
#redirect_from:
#  - /resume
---

SMART-Rain Dataset
======
Our dataset is created in Singapore, where the rainfall is abundant all year round. We drove a full-sized vehicle equipped with a 3D LiDAR, cameras, and a rainfall measurement sensor to collect data in various rainy conditions. In total, we have collected 31.8 hours of rainy data (light rain: 13.2 hours, moderate rain: 15.0 hours, heavy rain: 3.6 hours) from 29 data collection trips and 8.8 hours of data in clear weather from 8 trips. Further, we selected and annotated 5 K images for 2D object detection evaluation in light rain, moderate rain, heavy rain, and mixed weather conditions. Our dataset has three unique features compared to other datasets: 1, containing a significant amount of representative data from various rainy conditions; 2, collecting rainfall intensity measurements accompanied with sensor data. 3, categorizing data based on rainfall levels to study the rain influence on algorithm performance. More information can be found in the paper. 

SMART-Degradation Dataset
======
SMART-Degradation is another dataset for studying autonomous driving in rainy weather. Unlike the SMART-Rain dataset which only contains raw sensor measurements, this new dataset consists of post-processed LiDAR scans specifically for studying LiDAR sensor degradation. This dataset was also collected by driving a full-size vehicle equipped with a 32-channel 3D LiDAR under various rainy situations in an urban environment. The post-processed LiDAR scans are called LiDAR pairs: each pair includes one LiDAR scan from clear weather and one scan from rainy weather at the same location. These LiDAR scan pairs can be used to study the degradation process of rain on laser measurements. More information can be found in the paper. 
