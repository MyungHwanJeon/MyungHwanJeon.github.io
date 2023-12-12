---
layout: distill
title: RGB2TIR Translation
description: Edge-guided Multi-domain RGB-to-TIR image Translation for Training Vision Tasks with Challenging Labels
img: assets/img/RGB2TIR.png
importance: 1
date: 2023-05-31
category: Projects

authors:
  - name: Dong-Guw Lee
    url: "https://scholar.google.com/citations?user=u6VDnlgAAAAJ&hl=ko&oi=ao"
    affiliations: 
      name: SNU, South Korea
  - name: Myung-Hwan Jeon
    url: "https://myunghwanjeon.github.io/"
    affiliations: 
      name: SNU, South Korea
  - name:  Younggun Cho
    url: "https://scholar.google.com/citations?user=W5MOKWIAAAAJ&hl=ko&oi=ao"
    affiliations: 
      name: Inha Univ, South Korea
  - name: Ayoung Kim
    url: "https://ayoungk.github.io/"
    affiliations: 
      name: SNU, South Korea

---

<div class="row">
  <div class="col">
    <a target="_blank" href="https://github.com/RPM-Robotics-Lab/sRGB-TIR" class="button button--sacnite button--round-l">
      <i class="fab fa-github fa-3x" title="Github link"></i>
    </a>
  </div>
  <div class="col-10">
    <a target="_blank" href="https://arxiv.org/abs/2301.12689" class="button button--sacnite button--round-l">
      <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
    </a>
  </div>
</div>

## Intro

The insufficient number of annotated thermal infrared (TIR) image datasets not only hinders TIR image-based deep learning networks to have comparable performances to that of RGB but it also limits the supervised learning of TIR image-based tasks with challenging labels. As a remedy, we propose a modified multidomain RGB to TIR image translation model focused on edge preservation to employ annotated RGB images with challenging labels. Our proposed method not only preserves key details in the original image but also leverages the optimal TIR style code to portray accurate TIR characteristics in the translated image, when applied on both synthetic and real world RGB images. Using our translation model, we have enabled the supervised learning of deep TIR image-based optical flow estimation and object detection that ameliorated in deep TIR optical flow estimation by reduction in end point error by 56.5\% on average and the best object detection mAP of 23.9\% respectively.

## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/zq8Qh9ygm6w?si=SEfVB3FJZ1EVLgbU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>