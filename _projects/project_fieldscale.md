---
layout: distill
title: Fieldscale
description: Locality-Aware Field-based Adaptive Rescaling for Thermal Infrared Image
img: assets/img/fieldscale.png
importance: 1
date: 2024-05-27
category: Projects

authors:
  - name: Hyeonjae Gil
    url: "https://hyeonjaegil.github.io/"
    affiliations: 
      name: SNU, South Korea     
  - name:  Myung-Hwan Jeon
    url: "https://myunghwanjeon.github.io/"
    affiliations: 
      name: SNU, South Korea
  - name: Ayoung Kim
    url: "https://ayoungk.github.io/"
    affiliations: 
      name: SNU, South Korea

---

<div class="row">
  <div class="col">
    <a target="_blank" href="https://github.com/HyeonJaeGil/fieldscale" class="button button--sacnite button--round-l">
      <i class="fab fa-github fa-3x" title="Github link"></i>
    </a>
  </div>
  <div class="col-10">
    <a target="_blank" href="https://arxiv.org/pdf/2405.15395" class="button button--sacnite button--round-l">
      <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
    </a>
  </div>
</div>

## Intro

Thermal infrared (TIR) cameras are emerging as promising sensors in safety-related fields due to their robustness against external illumination. However, RAW TIR image has 14 bits of pixel depth and needs to be rescaled into 8 bits for general applications. Previous works utilize a global 1D look-up table to compute pixel-wise gain solely based on its intensity, which degrades image quality by failing to consider the local nature of the heat. We propose Fieldscale, a rescaling based on locality-aware 2D fields where both the intensity value and spatial context of each pixel within an image are embedded. It can adaptively determine the pixel gain for each region and produce spatially consistent 8-bit rescaled images with minimal information loss and high visibility. Consistent performance improvement on image quality assessment and two other downstream tasks support the effectiveness and usability of Fieldscale. All the codes are publicly opened to facilitate research advancements in this field.

## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/xe7sFsw655c?si=tt_-EqtlMDL2i-Dm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


