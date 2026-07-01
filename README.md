# 🚀 Intelligent Object Detection using YOLOR - Precision Agriculture (Needle in a haystack approach for weed detection in farms)
### Final Year Project – The University of Adelaide

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-1.7-red.svg)]()
[![YOLOR](https://img.shields.io/badge/Model-YOLOR-success.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

## 📖 Overview

This repository contains my Final Year Project completed at **The University of Adelaide**.

The project focuses on **deep learning-based object detection** using the **YOLOR (You Only Learn One Representation)** architecture. A custom image dataset was collected, annotated, and trained to build an accurate object detection model capable of identifying objects in real-world environments.

The project demonstrates the complete machine learning workflow including:

- Data collection
- Image annotation
- Dataset preparation
- Model training
- Model evaluation
- Object detection inference
- Performance analysis

---

## 🎯 Project Objectives

- Build a high-performance object detection model.
- Train a custom YOLOR model on a domain-specific dataset.
- Evaluate detection accuracy using modern computer vision metrics.
- Demonstrate real-time object detection capability.

---

## 🧠 Model

The project uses:

- **YOLOR (You Only Look Once Representation)**
- PyTorch
- CUDA GPU acceleration
- Mish CUDA
- PyTorch Wavelets

YOLOR combines both explicit and implicit knowledge during training, providing excellent performance for object detection tasks.

---

## 📂 Dataset

The model was trained on a **custom annotated dataset** created using **Roboflow**.

Dataset preparation included:

- Image collection
- Bounding box annotation
- Train / Validation / Test split
- YOLO format conversion

---

## 🛠 Technologies Used

- Python
- PyTorch
- OpenCV
- NumPy
- Google Colab
- CUDA
- Roboflow
- YOLOR

---

## 📁 Repository Structure

```
.
├── Precision-Agriculture.ipynb
├── README.md
├── train/
├── test/
├── data.yaml
└── model weights
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/project-name.git

cd project-name
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Training

Launch the notebook:

```
Precision-Agriculture.ipynb
```

or train using YOLOR:

```bash
python train.py
```

---

## 📈 Results

The project successfully demonstrates:

- Accurate object localization
- Robust detection on unseen images
- End-to-end deep learning pipeline
- Custom dataset training using YOLOR

---

## 🎓 Academic Information

**Project:** Final Year Project

**University:** The University of Adelaide

**Degree:** Masters in Machine Learning

---

## 👨‍💻 Author

**Nimish Pathak**

---

## 📜 Acknowledgements

Special thanks to:

- The University of Adelaide
- The YOLOR Research Team
- PyTorch
- Roboflow
- The Open Source Computer Vision Community

---

