# code
readme_content = """
# DR-Detection-MVKSELM-IEHO

### A Cybernetic Approach to Diabetic Retinopathy Detection Using MVKSELM-IEHO Algorithm on SD-OCT Images

![Python](https://img.shields.io/badge/Python-3.11-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![Platform](https://img.shields.io/badge/Platform-Windows%2011%2064bit-lightgrey)

---

## 📌 Overview

This repository provides the complete implementation of a hybrid framework for Diabetic Retinopathy (DR) detection using Spectral Domain Optical Coherence Tomography (SD-OCT) images. The model combines:

- **SAVN (Spatially Adaptive VGG Network)** for multi-scale feature extraction using Spatial Pyramid Pooling (SPP).
- **KSELM (Kernel-based Softplus Extreme Learning Machine)** for effective non-linear classification.
- **IEHO (Improved Elephant Herding Optimization)** enhanced with **Sine Cosine Algorithm (SCA)** for optimal hyperparameter tuning.

> 🔍 Achieved 98.75% accuracy on the OCTID dataset and 98.6% on the Retinal OCT dataset.

---

## 🧠 Key Features

- Multi-scale SPP-enhanced VGG16 network.
- Gabor-based denoising, CLAHE contrast enhancement, and wavelet-based artifact removal.
- RBF Kernel and Softplus activation for advanced classification.
- Sine Cosine + IEHO optimization.
- Full training and evaluation scripts.

---

## 📂 Directory Structure


---

## 📊 Datasets

### 1. OCTID Dataset
- SD-OCT images categorized into DR, MH, CSR, AMD, and NO.
- 📦 Total: 474 images.
- 📎 Download Link: [OCTID Dataset on Kaggle](https://www.kaggle.com/datasets/saifurrahmanshatil/retinal-oct-dataset)

### 2. Retinal OCT Images Dataset (Kermany 2018)
- Large-scale OCT image dataset with DME, CNV, DRUSEN, and NORMAL classes.
- 📦 Total: 84,495 images.
- 📎 Download Link: [Retinal OCT Images on Kaggle](https://www.kaggle.com/datasets/paultimothymooney/kermany2018)

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/DR-Detection-MVKSELM-IEHO.git
cd DR-Detection-MVKSELM-IEHO
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate
pip install -r requirements.txt

