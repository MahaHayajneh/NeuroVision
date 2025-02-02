# NeuroVision

**NeuroVision** is an innovative 3D brain tumor segmentation tool designed to aid radiologists and medical professionals in diagnosing and treating neuro-oncological conditions. Utilizing the power of 3D U-Net convolutional neural networks, the project provides accurate and efficient segmentation of brain tumors from MRI scans.

---

## Project Overview

### **Motivation**
Radiologists often face challenges in accurately identifying brain tumors using 2D MRI slices. NeuroVision addresses these limitations by providing 3D representations of brain tumors, enabling a more comprehensive and detailed analysis.

### **Objective**
To enhance the precision of brain tumor diagnosis and treatment planning by leveraging AI-powered 3D segmentation and visualization techniques.

---

## Key Features

- **3D Tumor Segmentation:** Uses a 3D U-Net architecture to accurately segment brain tumors.
- **Interactive Visualization:** Offers real-time 3D tumor visualization through a user-friendly GUI.
- **High Accuracy:** Achieved an average Cohen's Kappa score of 0.99 on the BraTS 2020 dataset.
- **Customizable Views:** Allows users to modify visual parameters for improved diagnostic clarity.

---

## Technologies Used

- **Programming Language:** Python
- **Frameworks:** TensorFlow, PyTorch
- **Libraries:** PyQt5, Mayavi, NumPy
- **Dataset:** BraTS 2020 (Brain Tumor Segmentation Challenge Dataset)
- **Visualization Tools:** Mayavi for 3D rendering

---

## Installation Guide

### **Prerequisites**
- Python 3.7 or higher
- A system with GPU acceleration (recommended)

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/NeuroVision.git
   cd NeuroVision
