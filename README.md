WaferNet: Learning Wafer Map Defects with Channel-Attentive DenseNet and Dual Pooling

Overview

WaferNet is a deep learning based wafer defect classification project developed for semiconductor manufacturing analysis.

This work focuses on robust wafer-map classification using a DenseNet-based architecture combined with attention mechanisms and mask-aware pooling.

This repository contains:

* Implementation notebook
* Published research paper
* Supporting result screenshots

⸻

Features

* Wafer defect classification
* DenseNet-121 backbone
* Efficient Channel Attention (ECA)
* Mask-Aware Global Average and Max Pooling
* Class imbalance handling
* Explainability using Grad-CAM
* Reproducible experimental workflow

⸻

Dataset

Dataset Used:

WM-811K / LSWMD

Dataset characteristics:

* Multi-class wafer defect classification
* Large-scale semiconductor wafer maps
* Imbalanced class distribution
* Variable wafer dimensions

Preprocessing:

* Standardized input size: 96 × 96
* Two-channel tensor representation
* Binary wafer mask generation

⸻

Methodology

Pipeline:

Data Collection
→ Data Preprocessing
→ Tensor Generation
→ DenseNet-121
→ Channel Attention
→ Mask-Aware Pooling
→ Classification
→ Explainability

⸻

Repository Structure

wafernet-wafer-defect-classification/

README.md

requirements.txt

notebook/

paper/

images/

⸻

Results

Included:

* Validation Metrics
* Test Metrics
* Training Curves
* Grad-CAM Outputs
* Research Screenshots

⸻

Installation

Install dependencies:

pip install -r requirements.txt

Run notebook:

jupyter notebook

Open:

wafernet_research_implementation_clean.ipynb

⸻

Included Files

Notebook:
wafernet_research_implementation_clean.ipynb

Research Paper:
WaferNet - Research paper.pdf

⸻

Publication

Published research work based on wafer defect classification using deep learning.

⸻

Future Improvements

* Improved minority defect recall
* Segmentation extension
* Self-supervised learning
* Deployment optimization
