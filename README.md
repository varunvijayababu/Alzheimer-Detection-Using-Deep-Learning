# 🧠 Alzheimer’s Disease Detection using Deep Learning

## 📌 Overview
This project focuses on early detection of Alzheimer’s Disease using MRI images with a deep learning approach.

The model combines **ResNet50 + Attention Mechanism + Grad-CAM** to achieve both high accuracy and interpretability.

---

## 🚀 Model Details
- Architecture: Attention-based ResNet50
- Transfer Learning: ImageNet pretrained
- Training Strategy:
  - Phase 1: Freeze base layers
  - Phase 2: Fine-tuning
- Explainability: Grad-CAM

---

## 📊 Results
- Validation Accuracy: **96.1%**
- Multi-class classification (4 stages)

---

## 🔍 Explainability
Grad-CAM is used to visualize important brain regions contributing to predictions.

---

## 🖼️ Outputs

### Model Architecture
![Architecture](images/architecture.png)

### Grad-CAM Visualization
![GradCAM](images/gradcam.png)

---

## 📂 Dataset
Kaggle Alzheimer MRI Dataset  
[(Dataset)](https://drive.google.com/file/d/1jVKENvRj5N7DLR3nR9tXACaNTOuz_uxl/view?usp=drive_link)

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib

---

## 🎯 Key Contributions
- Attention-enhanced ResNet50 model
- 96.1% classification accuracy
- Explainable AI using Grad-CAM
- Multi-class Alzheimer detection

---

## 👨‍💻 Author
Varun Vijaya Babu  
