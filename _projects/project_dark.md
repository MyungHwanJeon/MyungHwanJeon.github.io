---
layout: distill
title: Dark Synthetic Vision
description: Lightweight Active Vision to Navigate in the Dark
img: assets/img/dark.png
importance: 5
date: 2020-10-30
category: Projects

authors:
  - name: Joowan Kim
    url: "https://scholar.google.com/citations?user=87nuF54AAAAJ&hl=ko"
    affiliations: 
      name: Samsung Heavy Industry, South Korea
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

<a target="_blank" href="https://rpm.snu.ac.kr/publications/jwkim-2020-ral.pdf" class="button button--sacnite button--round-l">
    <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
</a>

## Intro

Overcoming illumination variance is a critical factor in vision-based navigation. Existing methods tackled this radical illumination variance issue by proposing camera control or high dynamic range (HDR) image fusion. Despite these efforts, we have found that the vision-based approaches still suffer from overcoming darkness. This paper presents real-time image synthesizing from carefully controlled seed low dynamic range (LDR) image, to enable visual simultaneous localization and mapping (SLAM) in an extremely dark environment (less than 10 lux). Unlike existing methods, we elaborately select the seed LDR image for HDR fusion to secure interframe consistency, which is important in visual navigation. After selecting the seed image by camera control, we exploit camera response function (CRF) to synthesize HDR images in realtime without requiring GPU. We validate the algorithm via two extremely dark environments, an indoor environment without light and an outdoor night. In both test scenarios, the proposed method enabled reliable visual SLAM even when the light was limited.

## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/XmmJBgy5PbQ?si=v4p66ZoWk8eTk_TJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>