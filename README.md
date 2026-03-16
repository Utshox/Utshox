<div align="center">

# Istiaque (Utshox)
**Machine Learning / Computer Vision — Medical Image Segmentation**

I build experiment-driven ML systems with a focus on **high-resolution segmentation**, **semi-supervised learning**, and **reproducible pipelines**.

**CV / Portfolio:** https://istiaque.cv

</div>

---

## Current focus
- **Medical image segmentation (CT)** — patch-based learning to preserve native resolution
- **Semi-supervised learning (SSL)** — strong performance with fewer labels (Mean Teacher)
- **Reliable experimentation** — preprocessing → training → inference → verification

---

## Featured work (high-signal projects)

### High-Resolution Patch-Based Pancreas Segmentation (v2)
**Repo:** https://github.com/Utshox/pancreas-segmentation-resolution-study-v2  

A patch-based framework that avoids aggressive downsampling by training on **256×256 patches extracted from 512×512 CT slices**.

- Reported **Dice up to ~0.85** (supervised patch baseline) and **verified avg ≈ 0.815** on a small test subset
- SSL result: **Mean Teacher ~0.83 Dice with 50% labeled data** (near full-supervision performance)
- Research direction: conference-level study → **journal roadmap** (resolution/FOV trade-offs, ablations, validation)

### Pancreas Segmentation Resolution Study (v1)
**Repo:** https://github.com/Utshox/pancreas-segmentation-resolution-study  

A resolution study showing that **preserving native resolution via patching** improves segmentation quality.

- Key finding: **Dice 0.73 → 0.85** by avoiding resize-heavy pipelines
- Mean Teacher SSL with **50% labels: ~0.83 Dice**, outperforming FixMatch in this setting
- Implementation highlights:
  - HU windowing **[-125, 275]** + normalization
  - balanced foreground/background patch sampling from NIfTI volumes
  - sliding-window inference to reconstruct full-resolution predictions

---

## What I’m comfortable building end-to-end
- **Data & preprocessing:** NIfTI pipelines, CT windowing/normalization, patch extraction strategies
- **Modeling:** U-Net style segmentation, SSL (Mean Teacher / consistency), evaluation (Dice/IoU)
- **Inference:** sliding-window / patch reconstruction, qualitative visualization & verification
- **Engineering:** reproducible scripts, organized experiment outputs, readable code

---

## Selected other projects
- Scientific article similarity (ML research): https://github.com/Utshox/Machine-Learning-based-Scientific-Article-Similarity-Checking-Research
- Portfolio site repo: https://github.com/Utshox/Istiaque-Portfolio
- React + TS e-commerce pilot: https://github.com/Utshox/symfony-ecommerce-pilot

---

## Quick numbers (from my recent segmentation research)
- **512×512 native resolution preserved** via patching  
- **256×256 patch-based training + sliding-window inference**
- **Dice up to ~0.85** reported on NIH Pancreas-CT (project README results)
- **~0.83 Dice with 50% labels** using Mean Teacher SSL

<sub>Last updated: 2026-03-16</sub>
