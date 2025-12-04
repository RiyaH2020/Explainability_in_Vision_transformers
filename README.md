# 🔍 Explainability in Vision Transformers

This repository contains an interpretability pipeline for Vision Transformers (ViTs) using a pretrained **DeiT-Tiny** model. It implements both **Attention Rollout** and **Gradient Attention Rollout**, and introduces a quantitative metric — **Foreground–Background Attention Fraction (FAF/BAF)** — using **Mask R-CNN** to measure how well ViTs focus on meaningful object regions.

The project also compares explanation behaviour between **CNNs 🧠** and **Vision Transformers 🤖**, highlighting how transformers rely on global patch interactions rather than localized feature extraction. Experiments show that **gradient-based rollout achieves ~25% higher foreground alignment**, producing more precise and class-specific attribution maps.

---

## ✨ Features
- 🔄 Attention Rollout & Gradient Attention Rollout implementations  
- 🧩 Patch-level attention visualization on the 14×14 ViT grid  
- 🎯 FAF/BAF metric using Mask R-CNN for quantitative semantic focus evaluation  
- ⚖️ Comparison of interpretability behaviour between CNNs and ViTs  
- 📈 Reproducible experiments with visualizations  

---



