---
permalink: /about/
title: "About the Project"
layout: single
author_profile: true
---

## Background

Remote sensing imagery analysis is crucial for urban planning, disaster management, environmental monitoring, and defense applications. However, creating accurate segmentation models requires extensive labeled datasets, which are expensive and time-consuming to produce.

## The Challenge

Traditional supervised learning approaches face several limitations:

1. **High Annotation Cost**: Expert annotators spend 5-10 minutes per image
2. **Scalability Issues**: Large-scale applications need millions of labeled pixels
3. **Domain Shift**: Models trained on one region often fail on others
4. **Boundary Inaccuracy**: Standard methods struggle with precise edge detection

## Our Solution

We developed a **semi-supervised adversarial learning framework** that:

### 1. Leverages Unlabeled Data
- Uses abundant satellite imagery without annotations
- Applies FixMatch-style consistency regularization
- Generates high-quality pseudo-labels with dynamic thresholds

### 2. Ensures Boundary Accuracy
- Dedicated boundary detection head
- Morphological edge extraction (radius-based)
- Dual-loss optimization (segmentation + boundary)

### 3. Validates Pseudo-Labels
- PatchGAN discriminator assesses label quality
- Confidence-weighted unsupervised loss
- Adversarial training stabilizes learning

## Technical Architecture

