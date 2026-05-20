---
title: "SASTRA University"
track: "education"
role: "Bachelor's in CSE"
location: "India"
date: 2017-07-01
start: "2017-07"
end: "2021-07"
period: 1
periodLabel: "Jul 2017 – Jul 2021"
description: "Computer Vision research on video captioning for assistive devices."
logo: "sastra.svg"
tags:
  - "Computer Science"
  - "Computer Vision"
  - "Video Captioning"
  - "Assistive Technology"
  - "Deep Learning"
  - "Image Processing"
  - "NLP"
  - "Multimodal AI"
  - "Python"
  - "Machine Learning"
  - "Research"
---

## Context
During my undergraduate research at SASTRA University, I worked on computer vision and multimodal AI problems across two research directions: semantic segmentation of aerial imagery and dense video captioning for assistive vision.

The common thread across both projects was visual understanding: how can deep learning systems interpret complex visual inputs and convert them into useful structured outputs, whether pixel-level land-cover labels or natural-language descriptions of video content?

## What I Built
For my B.Tech thesis, I worked on semantic segmentation of high-resolution aerial imagery using the ISPRS Vaihingen and Potsdam benchmark datasets. The goal was to classify every pixel in urban aerial images into land-cover categories such as buildings, impervious surfaces, vegetation, trees, cars, and clutter.

I implemented and compared multimodal fusion strategies using SegNet and ResNet encoder-decoder architectures. Early fusion combined IRRG multispectral imagery with DSM/NDSM/NDVI data at the input level, while late fusion used separate encoder branches for each modality before combining predictions. I also implemented DeepLab as a baseline and compared results against published methods.

In parallel, I explored dense video captioning for assistive vision. This work studied how computer vision and NLP techniques could generate natural-language descriptions from video. I experimented with object detection, autoencoders, 2D CNNs, 3D CNNs, GANs, and Transformer-based approaches to understand how different architectures handle spatial features, temporal patterns, and caption generation.

## Challenges
A major challenge in the segmentation work was fusing fundamentally different data modalities. Multispectral imagery captures spectral information, while LiDAR-derived surface models capture elevation and structure. The project required understanding how each modality contributed to segmentation accuracy and how different fusion strategies affected model performance.

For dense video captioning, the challenge was bridging visual scene understanding and language generation. The system needed to capture not only objects in individual frames, but also actions, temporal context, and coherent natural-language descriptions.

Across both projects, evaluation was central. I had to compare architectures, understand model tradeoffs, and reason about limitations in benchmark labels, modality quality, and output metrics.

## Impact & Takeaways
The semantic segmentation work achieved 91.1% overall accuracy on Vaihingen and 90.6% on Potsdam, with multimodal fusion outperforming single-modality baselines. Early fusion learned stronger joint representations, while late fusion helped recover difficult pixels that other models missed.

Together, these projects gave me my first end-to-end research experience in deep learning, computer vision, multimodal learning, preprocessing, benchmarking, and model evaluation. They shaped how I approach applied AI today: define the problem clearly, compare methods rigorously, understand failure modes, and evaluate whether the model output is useful for the task.
