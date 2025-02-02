# NeuroVision

**NeuroVision** is an innovative 3D brain tumor segmentation tool designed to aid radiologists and medical professionals in diagnosing and treating neuro-oncological conditions. Utilizing the power of 3D U-Net convolutional neural networks, the project provides accurate and efficient segmentation of brain tumors from MRI scans.

---

## Project Overview

### **Motivation**
Radiologists often face challenges in accurately identifying brain tumors using 2D MRI slices. NeuroVision addresses these limitations by providing 3D representations of brain tumors, enabling a more comprehensive and detailed analysis.

### **Scope**
The project focuses on brain tumor segmentation using MRI scans, providing 3D visualizations to assist medical professionals. It employs the BraTS 2020 dataset and 3D U-Net architecture to achieve high segmentation accuracy.

### **Limitations**
1. **Tumor Heterogeneity:** Challenges in segmenting tumors with varying sizes and shapes.
2. **Data Quality Dependency:** Performance heavily relies on high-quality MRI scans.
3. **Computational Resources:** Requires significant GPU memory and computational power.
4. **Complex Tumor Features:** Struggles with necrotic cores, edema, and other intricate tumor characteristics.
5. **Clinical Validation:** Limited availability of precise ground truth annotations for benchmarking.
6. **User Training:** Medical professionals may require training to interpret results effectively.

### **Future Work**
1. **Training Techniques:** Incorporate more efficient methods to improve model accuracy without increasing computational demands.
2. **Enhanced GUI Design:** Simplify and optimize the user interface for ease of use by medical professionals of varying expertise.
3. **Workflow Integration:** Develop seamless integration with hospital and clinic information systems.
4. **Predictive Analytics:** Extend functionality to predict tumor growth and progression.
5. **Hardware Optimization:** Improve the system’s performance on devices with limited computational capabilities.

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
