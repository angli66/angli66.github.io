---
title: 'Sparp: Fast 3d object reconstruction and pose estimation from sparse views'
authors:
- Chao Xu
- admin
- Linghao Chen
- Yulin Liu
- Ruoxi Shi
- Hao Su
- Minghua Liu
date: '2024-10-01'
publishDate: '2025-04-08T08:42:04.235121Z'
publication_types:
- paper-conference
publication: '*European Conference on Computer Vision*'
publication_short: '*ECCV 2024*'

abstract: Open-world 3D generation has recently attracted considerable attention. While many single-image-to-3D methods have yielded visually appealing outcomes, they often lack sufficient controllability and tend to produce hallucinated regions that may not align with users' expectations. In this paper, we explore an important scenario in which the input consists of one or a few unposed 2D images of a single object, with little or no overlap. We propose a novel method, SpaRP, to reconstruct a 3D textured mesh and estimate the relative camera poses for these sparse-view images. SpaRP distills knowledge from 2D diffusion models and finetunes them to implicitly deduce the 3D spatial relationships between the sparse views. The diffusion model is trained to jointly predict surrogate representations for camera poses and multi-view images of the object under known poses, integrating all information from the input sparse views. These predictions are then leveraged to accomplish 3D reconstruction and pose estimation, and the reconstructed 3D model can be used to further refine the camera poses of input views. Through extensive experiments on three datasets, we demonstrate that our method not only significantly outperforms baseline methods in terms of 3D reconstruction quality and pose prediction accuracy but also exhibits strong efficiency. It requires only about 20 seconds to produce a textured mesh and camera poses for the input views.

summary: Given sparse unposed views, we leverage rich priors embedded in multiview diffusion models to predict their poses and reconstruct the 3D shape.

links:
- name: DEMO
  url: 'https://huggingface.co/spaces/sudo-ai/SpaRP'
- name: PROJECT
  url: 'https://chaoxu.xyz/sparp'
url_pdf: 'https://arxiv.org/pdf/2408.10195'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
