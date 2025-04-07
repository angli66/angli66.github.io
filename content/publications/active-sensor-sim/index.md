---
title: Close the Optical Sensing Domain Gap by Physics-Grounded Active Stereo Sensor
  Simulation
authors:
- Xiaoshuai Zhang
- Rui Chen
- admin
- Fanbo Xiang
- Yuzhe Qin
- Jiayuan Gu
- Zhan Ling
- Minghua Liu
- Peiyu Zeng
- Songfang Han
- Zhiao Huang
- Tongzhou Mu
- Jing Xu
- Hao Su
date: '2023-01-27'
publishDate: '2025-04-08T08:42:04.230285Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Robotics*'
publication_short: '*T-RO 2023*'

abstract: In this paper, we focus on the simulation of active stereovision depth sensors, which are popular in both academic and industry communities. Inspired by the underlying mechanism of the sensors, we designed a fully physics-grounded simulation pipeline that includes material acquisition, ray-tracing-based infrared (IR) image rendering, IR noise simulation, and depth estimation. The pipeline is able to generate depth maps with material-dependent error patterns similar to a real depth sensor in real time. We conduct real experiments to show that perception algorithms and reinforcement learning policies trained in our simulation platform could transfer well to the real-world test cases without any fine-tuning. Furthermore, due to the high degree of realism of this simulation, our depth sensor simulator can be used as a convenient testbed to evaluate the algorithm performance in the real world, which will largely reduce the human effort in developing robotic algorithms. The entire pipeline has been integrated into the SAPIEN simulator and is open-sourced to promote the research of vision and robotics communities.

summary: SAPIEN Realistic depth lowers the sim-to-real gap of simulated depth and real active stereovision depth sensors, by designing a fully physics-grounded pipeline. Perception and RL methods trained in simulation can transfer well to the real world without any fine-tuning. It can also estimate the algorithm performance in the real world, largely reducing human effort of algorithm evaluation.

links:
- name: TUTORIAL
  url: 'https://github.com/haosulab/SAPIEN-tutorial/blob/master/rendering/3_sapien_realistic_depth.ipynb'
- name: PROJECT
  url: 'https://angli66.github.io/active-sensor-sim'
url_pdf: 'https://arxiv.org/pdf/2201.11924'
url_code: 'https://github.com/haosulab/SAPIEN'
url_dataset: ''
url_poster: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=4tKRG1Do6HI'
---
