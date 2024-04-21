---
layout: distill
title: DiscoCal
description: Unbiased Estimator for Distorted Conics in Camera Calibration
img: assets/img/discocal.png
importance: 1
date: 2024-04-10
category: Projects

authors:
  - name: Chaehyeon Song
    url: "https://chaehyeonsong.github.io/"
    affiliations: 
      name: SNU, South Korea
  - name: Jaeho Shin
    url: "https://scholar.google.com/citations?user=jwq-rwMAAAAJ&hl=ko/"
    affiliations: 
      name: SNU, South Korea      
  - name:  Myung-Hwan Jeon
    url: "https://myunghwanjeon.github.io/"
    affiliations: 
      name: SNU, South Korea
  - name: Jongwoo Lim
    url: "https://sites.google.com/view/snu-rvlab/people/jwlim?authuser=0/"
    affiliations: 
      name: SNU, South Korea
  - name: Ayoung Kim
    url: "https://ayoungk.github.io/"
    affiliations: 
      name: SNU, South Korea

---

<div class="row">
  <div class="col">
    <a target="_blank" href="https://github.com/chaehyeonsong/discocal" class="button button--sacnite button--round-l">
      <i class="fab fa-github fa-3x" title="Github link"></i>
    </a>
  </div>
  <div class="col-10">
    <a target="_blank" href="https://arxiv.org/pdf/2403.04583.pdf" class="button button--sacnite button--round-l">
      <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
    </a>
  </div>
</div>

## Intro

In the project, points and conics have been major features for camera geometric calibration. Although conics are more informative features than points, the loss of the conic property under distortion has critically limited the utility of conic features in camera calibration. Many existing approaches addressed conic-based calibration by ignoring distortion or introducing 3D spherical targets to circumvent this limitation. In this paper, we present a novel formulation for conic-based calibration using moments. Our derivation is based on the mathematical finding that the first moment can be estimated without bias even under distortion. This allows us to track moment changes during projection and distortion, ensuring the preservation of the first moment of the distorted conic. With an unbiased estimator, the circular patterns can be accurately detected at the sub-pixel level and can now be fully exploited for an entire calibration pipeline, resulting in significantly improved calibration.

## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/87_R7Qkpczo?si=11msdiIqa2bJ8DVc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>