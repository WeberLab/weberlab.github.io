---
layout: page
title: BB&D Research Day 2025 – Javed & Weber
permalink: /conferences/bbd2025-javed/
---

## Developing a Rigorous Method for Detecting Power-Law Scaling and Critical Dynamics in fMRI Brain Signals

**E. A. Javed**, BC Children’s Hospital Research Institute; **A. M. Weber**, BC Children’s Hospital Research Institute

### Presentation Info

**Event:** Brain, Behaviour & Development Theme Research Day  
**Institution:** BC Children’s Hospital Research Institute  
**Location:** Vancouver, BC  
**Date:** Monday, November 24, 2025  

### Abstract

The "Critical Brain Theory" suggests the brain evolved to operate in a critical state, balanced between order and disorder. Critical systems show scale-invariance and long-range temporal correlations. Accurately measuring these scale-free dynamics can deepen our understanding of brain function and health.

This project aimed to create a Python-based signal-processing tool to (1) test for power-law distributions (scale-invariance), (2) classify signals as fractional Gaussian noise (fGn) or fractional Brownian motion (fBm), and (3) estimate the Hurst exponent (H), which quantifies long-range temporal correlations.

Simulated time series with known H values were used to benchmark and validate estimation and preprocessing methods. Power spectral density (PSD) analysis and log-log regression extracted scaling exponents, while Monte Carlo testing validated power-law fits and robustness. Preliminary results show that "Bridge Window Detrend" preprocessing combined with PSD-based slope estimation most accurately classified fGn versus fBm and estimated H.

Future work will apply this pipeline to voxel-wise fMRI data to investigate scale-free behaviour in spontaneous brain activity and assess how preprocessing affects power-law detection and reproducibility.

[Back to Conferences](/conferences/)