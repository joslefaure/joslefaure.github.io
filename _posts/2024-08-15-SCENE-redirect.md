---
# layout: distill
title: HERMES
date: 2024-07-15 11:06:00
description: A novel method that simulates episodic memory accumulation to capture action sequences and reinforces them with semantic knowledge dispersed throughout the video.
tags: video-understanding llm paper
categories: paper
thumbnail: assets/img/1719479888350.jpg
featured: false
related_posts: false
code: https://github.com/joslefaure/SCENE
paper: https://github.com/joslefaure/SCENE
redirect: /assets/html/hermes.html

authors:
  - name: First Author Name
    url: "https://joslefaure.github.io"
    affiliations:
      name: First Author Affiliation

  - name: Second Author Name
    url: "https://joslefaure.github.io"
    affiliations:
      name: Second Author Affiliation

  # - name: Gueter Josmy Faure
  #   url: "https://joslefaure.github.io"
  #   affiliations:
  #     name: National Taiwan University

  # - name: Jia-Fong Yeh
  #   url: "https://www.cmlab.csie.ntu.edu.tw/~jiafongyeh/"
  #   affiliations:
  #     name: National Taiwan University

  # - name: Min-Hung Chen
  #   url: "https://minhungchen.netlify.app/"
  #   affiliations:
  #     name: NVIDIA

  # - name: Hung-Ting Su
  #   url: ""
  #   affiliations:
  #     name: National Taiwan University

  # - name: Winston H. Hsu
  #   url: "https://winstonhsu.info/"
  #   affiliations:
  #     name: National Taiwan University

  # - name: Shang-Hong Lai
  #   url: "https://www.cs.nthu.edu.tw/~lai/"
  #   affiliations:
  #     name: National Tsing Hua University
---

### [Paper](https://github.com/joslefaure/SCENE) / [Code](https://github.com/joslefaure/SCENE)

## Abstract

While existing research often treats long-form videos as extended short videos, we propose a novel approach that more accurately reflects human cognition. This paper introduces **SCENE**: **S**emanti**C** and **E**pisodic **NE**twork for Long-Form Video Understanding, a model that simulates episodic memory accumulation to capture action sequences and reinforces them with semantic knowledge dispersed throughout the video. Our work makes two key contributions: First, we develop an Episodic Memory ComprEssor (EMCEE) module that efficiently aggregates crucial representations from micro to semi-macro levels. Second, we propose a Semantic Knowledge ExtrAcTor (SKEAT) that enhances these aggregated representations with semantic information by focusing on the broader context, dramatically reducing feature dimensionality while preserving relevant macro-level information. Extensive experiments demonstrate that **SCENE** achieves state-of-the-art performance across multiple long-video understanding benchmarks in both zero-shot and fully-supervised settings. Our code will be made public at [SCENE](https://github.com/joslefaure/SCENE).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/intuition.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

## Main Contributions

Our key contributions are as follows:

- We propose an Episodic Memory ComprEssor (EMCEE) to stream through the video and keep important episodes by aggregating similar scenes. EMCEE enables efficient processing of extended video sequences while preserving temporal coherence and narrative structure.
- We develop a Semantic Knowledge Extractor (SKEAT) that enhances the model's understanding of long videos by distilling high-level semantic cues, providing a cohesive framework for understanding the context and themes within long-form videos.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/method.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

## Results and Ablations

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/results.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

## Qualitative Results

## Citation
