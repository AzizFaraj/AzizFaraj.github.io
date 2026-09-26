---
title: "WaveFlow-UIE: A Single-Pipeline Wavelet-Domain Flow Model for Efficient Underwater Image Restoration"
collection: publications
category: preprints
permalink: /publication/waveflow-uie
date: 2026-09-10
authors: 'Mohammed Al Naser, <b>Abdulaziz Alfaraj</b>, Hassan Al Nasser, Muzammil Behzad'
status: 'Preprint, arXiv link coming soon'
excerpt: 'A single-pipeline wavelet-domain flow model for underwater image restoration, about 4× faster at inference than a two-stage diffusion baseline.'
---

Underwater images suffer from color distortion, scattering, and loss of detail, which affect low- and high-frequency image content differently. WaveFlow-UIE restores them with a single flow-matching model that works directly in the wavelet domain, conditioned on a lightweight physics-prior branch that estimates transmission and ambient light.

Compared with the two-stage WF-Diff diffusion baseline, WaveFlow-UIE cuts inference time by about 4× at 256 × 256 resolution while remaining especially competitive on perceptual metrics (LPIPS, FID). Reducing inference from five flow steps to one keeps nearly all of the restoration quality and gives a further 4× speedup. We benchmark against five published methods on six underwater datasets.

This work was done with Dr. Muzammil Behzad at KFUPM.
