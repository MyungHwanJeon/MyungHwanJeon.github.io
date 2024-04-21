---
layout: distill
title: PrimA6D
description: Rotational Primitive Reconstruction for Enhanced and Robust 6D Pose Estimation
img: assets/img/prima6d.png
importance: 5
date: 2020-06-23
category: Projects


authors:
  - name: Myung-Hwan Jeon
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
    <a target="_blank" href="https://github.com/MyungHwanJeon/PrimA6D" class="button button--sacnite button--round-l">
      <i class="fab fa-github fa-3x" title="Github link"></i>
    </a>
  </div>
  <div class="col-10">
    <a target="_blank" href="https://arxiv.org/abs/2006.07789" class="button button--sacnite button--round-l">
      <i class="fas fa-file-pdf fa-3x" title="pdf link"></i>
    </a>
  </div>
</div>

## Intro

In this paper, we introduce a rotational primitive prediction based 6D object pose estimation using a single image as an input. We solve for the 6D object pose of a known object relative to the camera using a single image with occlusion. Many recent state-of-the-art (SOTA) two-step approaches have exploited image keypoints extraction followed by PnP regression for pose estimation. Instead of relying on bounding box or keypoints on the object, we propose to learn orientation-induced primitive so as to achieve the pose estimation accuracy regardless of the object size. We leverage a Variational AutoEncoder (VAE) to learn this underlying primitive and its associated keypoints. The keypoints inferred from the reconstructed primitive image are then used to regress the rotation using PnP. Lastly, we compute the translation in a separate localization module to complete the entire 6D pose estimation. When evaluated over public datasets, the proposed method yields a notable improvement over the LINEMOD, the Occlusion LINEMOD, and the YCB-Video dataset. We further provide a synthetic-only trained case presenting comparable performance to the existing methods which require real images in the training phase.


## Video 

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/HbNmsmTLRmk?si=THuDk5Ao4ZwB6CZQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
        






