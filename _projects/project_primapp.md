---
layout: distill
title: PrimA6D++
description: Ambiguity-Aware Multi-Object Pose Optimization for Visually-Assisted Robot Manipulation
img: assets/img/prima6dpp.png
importance: 1
date: 2022-11-17
category: Projects

authors:
  - name: Myung-Hwan Jeon
    url: "https://myunghwanjeon.github.io/"
    affiliations: 
      name: SNU, South Korea
  - name:  Jeongyun Kim
    url: "https://scholar.google.co.kr/citations?user=vW2JtFAAAAAJ"
    affiliations: 
      name: SNU, South Korea
  - name: Jee-Hwan Ryu
    url: "https://scholar.google.com/citations?hl=en&user=zLOoWCUAAAAJ"
    affiliations: 
      name: KAIST, South Korea
  - name: Ayoung Kim
    url: "https://ayoungk.github.io/"
    affiliations: 
      name: SNU, South Korea

---

<div class="row">
  <div class="col">
    <a target="_blank" href="https://github.com/MyungHwanJeon/PrimA6D" class="button button--sacnite button--round-l">
      <i class="fab fa-github fa-3x" title="Github link"></i>
    </a>
  </div>
  <div class="col-10">
    <a target="_blank" href="https://arxiv.org/abs/2211.00960" class="button button--sacnite button--round-l">
      <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
    </a>
  </div>
</div>

## Intro

6D object pose estimation aims to infer the relative pose between the object and the camera using a single image or multiple images. Most works have focused on predicting the object pose without associated uncertainty under occlusion and structural ambiguity (symmetricity). However, these works demand prior information about shape attributes, and this condition is hardly satisfied in reality; even asymmetric objects may be symmetric under the viewpoint change. In addition, acquiring and fusing diverse sensor data is challenging when extending them to robotics applications. Tackling these limitations, we present an ambiguity-aware 6D object pose estimation network, PrimA6D++, as a generic uncertainty prediction method. The major challenges in pose estimation, such as occlusion and symmetry, can be handled in a generic manner based on the measured ambiguity of the prediction. Specifically, we devise a network to reconstruct the three rotation axis primitive images of a target object and predict the underlying uncertainty along each primitive axis. Leveraging the estimated uncertainty, we then optimize multi-object poses using visual measurements and camera poses by treating it as an object SLAM problem. The proposed method shows a significant performance improvement in T-LESS and YCB-Video datasets. We further demonstrate real-time scene recognition capability for visually-assisted robot manipulation.

## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/akbI61jUJgY?si=Zfobhd-3NnMGgeJp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>