# 🧠 CWGAN Brain MRI Project

This project implements a **Conditional Wasserstein GAN (CWGAN)** to generate synthetic Brain MRI images for privacy-preserving medical research.

## 🚀 Overview
- Generates realistic brain MRI images using deep generative modeling.
- Helps maintain patient privacy while enabling AI training on synthetic data.
- Evaluated with **FID** and **SSIM** scores for quality and similarity checks.

## 📂 Contents
- `generator_final.pth` – Trained generator model.
- `discriminator_final.pth` – Trained discriminator model.
- `generated/` – Sample generated MRI images.
- `gen_eval/` – Images used for FID/SSIM evaluation.
- `checkpoints/` – Intermediate training checkpoints.

## 🧮 Metrics
- **FID Score:** 343.38  
- **SSIM Score:** 0.0244

## 🧑‍💻 Tools & Libraries
- Python, PyTorch, NumPy, Matplotlib
- Google Colab (T4 GPU)
- pytorch-fid, skimage

## 📊 How to Run
1. Upload files to Google Colab.
2. Mount Google Drive.
3. Load generator & discriminator weights.
4. Generate and evaluate images.

---

### 📧 Author
**Harshita Kumari**  
B.Tech Student, Amity University Jharkhand  
🎯 Goal: Using AI for social good through privacy-preserving deep learning.
