---
title: "Open-Source Resources"
date: 2026-05-16
weight: 5
description: "URT-SimReal: A multi-modal hybrid dataset for 6G intelligent urban rail transit research"
---

## URT-SimReal Dataset

**URT-SimReal** is a multi-modal hybrid dataset of real and simulated 3D spatial environments and multi-band wireless channels, designed for **6G intelligent Urban Rail Transit (URT)** system research.

![Dataset Methodology](/images/dataset-method.jpg)

### Dataset Highlights

| Metric | Value |
|--------|-------|
| **CSI Records** | 316,026 |
| **Covered Environments** | 11 typical URT scenarios (enclosed tunnels, viaducts, station hubs, etc.) |
| **Frequency Coverage** | Sub-6 GHz (1.8 / 3.5 / 5.6 GHz) up to mmWave (28 / 39.5 / 60 GHz) |
| **Data Types** | 3D Point Cloud (.ply) · RGB Images (.png) · Semantic Labels (.json) · CSI (.h5) |
| **License** | CC BY 4.0 |
| **DOI** | [10.5281/zenodo.19920829](https://doi.org/10.5281/zenodo.19920829) |
| **Version** | 1.0.0 |

![Dataset Structure](/images/dataset-structure.png)

### Channel Parameters

Each CSI record contains comprehensive wireless channel parameters:
- Path Loss
- RMS Delay Spread
- Mean / Maximum Excess Delay
- Rician K-factor
- Coherence Bandwidth
- Multipath Components (TOA, amplitude, phase)

### Applications

- **ISAC (Integrated Sensing and Communication)** algorithm benchmarking
- Environment-aware channel prediction
- Training data for foundation models
- Urban rail transit wireless communication system design and optimization

### Access the Dataset

The dataset is maintained by **Ye Jiang** (姜烨) and available via Zenodo. Data formats include .h5 (channel data), .ply (point clouds), .png (RGB images), and .json (semantic annotations), making it ready for direct use by researchers.

<a href="https://doi.org/10.5281/zenodo.19920829" class="btn btn-primary" target="_blank">
  <i class="fa-solid fa-download me-2"></i>Access Dataset (Zenodo)
</a>

![Scene Showcase](/images/scen-intro.png)
