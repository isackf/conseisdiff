# ConSeisDiff: Conditional Seismic Diffusion

[![Journal](https://img.shields.io/badge/Journal-Applied_Geophysics-blue)](https://doi.org/10.1016/j.jappgeo.2025.105956)
[![License: Academic](https://img.shields.io/badge/License-Academic-green.svg)](#license)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](INSERT_YOUR_COLAB_LINK_HERE)

**ConSeisDiff** is a conditional denoising diffusion probabilistic model (DDPM) for high-fidelity synthetic seismic data generation. The framework explicitly conditions the diffusion process on geological structural priors—such as **fault attributes** and **edge-based structural maps**—to reduce the domain gap between synthetic and real seismic data while preserving reflector continuity and fault geometry.

This repository provides the official implementation accompanying our peer-reviewed publication in the *Journal of Applied Geophysics*, including training scripts, inference pipelines, and evaluation utilities.

---

## Overview

Generating realistic and structurally consistent seismic data remains a major bottleneck for data-driven geophysical interpretation, particularly in fault detection and structural analysis. **ConSeisDiff** addresses this challenge through:

- **Structure-Aware Conditioning**  
  Incorporation of fault attributes and edge maps to guide the diffusion trajectory toward geologically plausible solutions.

- **High-Fidelity Seismic Synthesis**  
  Generation of realistic 2D seismic sections with preserved large-scale structure and fine-scale texture.

- **Quantitative Evaluation**  
  Built-in tools for evaluating synthetic quality using metrics such as FID, SSIM, and task-oriented fault detection performance.

---

## Publication

If you use this work, please cite the following paper:

> **ConSeisDiff: A Conditional Diffusion Approach to Mitigate Synthetic–Real Disparities in Seismic Fault Detection**  
> *Journal of Applied Geophysics*, 243, 105956, 2025.  
> DOI: https://doi.org/10.1016/j.jappgeo.2025.105956

### BibTeX
```bibtex
@article{FARADY2025105956,
  title   = {ConSeisDiff: A conditional diffusion approach to mitigate synthetic-real disparities in seismic fault detection},
  journal = {Journal of Applied Geophysics},
  volume  = {243},
  pages   = {105956},
  year    = {2025},
  issn    = {0926-9851},
  doi     = {https://doi.org/10.1016/j.jappgeo.2025.105956},
  url     = {https://www.sciencedirect.com/science/article/pii/S0926985125003374},
  author  = {Farady, Isack and Kuo, Chia-Chen and Sellami, Soufiene and Lin, Chih-Yang}
}
