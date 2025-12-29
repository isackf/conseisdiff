# ConSeisDiff: Conditional Seismic Diffusion

[![Paper](https://img.shields.io/badge/Journal-Applied_Geophysics-blue)](https://doi.org/10.1016/j.jappgeo.2025.105956)
[![License: Academic](https://img.shields.io/badge/License-Academic-green.svg)](#licensing)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](INSERT_YOUR_COLAB_LINK_HERE)

**ConSeisDiff** is a conditional denoising diffusion probabilistic model (DDPM) designed for the generation of high-fidelity synthetic seismic data. By conditioning the generative process on structural priors such as **fault attributes** and **edge maps**, the model produces realistic 2D seismic images that maintain geological consistency.

This repository contains the official implementation, training scripts, and an inference notebook as presented in our research published in the *Journal of Applied Geophysics*.

---

## 🌟 Overview

Generating labeled seismic data is a significant challenge in geophysics. **ConSeisDiff** addresses this by:
* **Structural Conditioning:** Utilizing edge maps and fault attributes to guide the diffusion process.
* **High-Resolution Synthesis:** Generating detailed 2D seismic textures that mimic real-world acquisition.
* **Metric Evaluation:** Providing tools to calculate FID, SSIM, and other relevant geophysical metrics.

## 📄 Publication

The methodology and results are detailed in our peer-reviewed paper:
> **"Conditional Diffusion Model for Generating Synthetic Seismic Data"** > *Journal of Applied Geophysics*, 2025.  
> **DOI:** [10.1016/j.jappgeo.2025.105956](https://doi.org/10.1016/j.jappgeo.2025.105956)

---

## 🛠 Installation

To set up the environment locally, ensure you have Python 3.8+ and install the required dependencies:

```bash
# Clone the repository
git clone [https://github.com/YourUsername/ConSeisDiff.git](https://github.com/YourUsername/ConSeisDiff.git)
cd ConSeisDiff

# Install dependencies
pip install -r requirements.txt
