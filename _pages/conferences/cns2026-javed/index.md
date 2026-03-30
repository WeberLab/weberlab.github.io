---
layout: page
title: CNS 2026 – Javed & Weber
permalink: /conferences/cns2026-javed/
---

## Developing a Rigorous Method for Detecting Power-Law Scaling and Critical Dynamics in fMRI Brain Signals

**Erhan Asad Javed**, University of British Columbia, Vancouver, Canada; BC Children's Hospital Research Institute, Vancouver, Canada; **Alexander Weber**, University of British Columbia, Vancouver, Canada

### Presentation Info

**Conference:** Cognitive Neuroscience Society (CNS) 2026  
**Poster:** F97  
**Series:** Sketchpad Series  
**Poster Session:** F  
**Date:** Tuesday, March 10, 2026  
**Time:** 8:00 – 10:00 am PDT  
**Location:** Fairview/Kitsilano Ballrooms  
**Topic Area:** METHODS: Neuroimaging

### Abstract

The Critical Brain Theory suggests the brain evolved to operate in a critical state, balanced between order and disorder. Critical systems show scale-invariance and long-range temporal correlations. Accurately measuring these scale-free dynamics can deepen our understanding of brain function and health; however, current estimation methods are often inconsistent, sensitive to preprocessing choices, and insufficiently rigorous. This project aimed to create a Python-based signal-processing tool to (1) test for power-law distributions (scale-invariance), (2) classify signals as fractional Gaussian noise (fGn) or fractional Brownian motion (fBm), and (3) estimate the Hurst exponent (H), which quantifies long-range temporal correlations, in both simulated and fMRI brain signals. Simulated time series with known H values were used to benchmark and validate estimation accuracy, preprocessing strategies, and classification performance. Power spectral density (PSD) analysis and log-log regression extracted scaling exponents, while automated frequency-window selection and Monte Carlo testing validated power-law fits and robustness. Results show that preprocessing has a substantial impact on power-law detection and parameter estimation. In particular, “Bridge Window Detrend” preprocessing combined with PSD-based slope estimation most accurately classified fGn versus fBm, achieving over 90% classification accuracy and stable H estimates across signal lengths. Application of the validated pipeline to voxel-wise resting-state fMRI data revealed reproducible detection of region-specific temporal dynamics consistent with scale-free behavior. Future work will extend this framework to study spatial correlations, brain-state transitions, and their links to neural criticality. Together, these results establish a robust and validated framework for detecting power-law scaling and long-range temporal correlations in fMRI brain signals.

[Back to Conferences](/conferences/)