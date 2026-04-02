# 👁️ Explainable AI for Retinal Disease Detection using OCT Images

## 📌 Overview
This project focuses on detecting retinal diseases from Optical Coherence Tomography (OCT) images using deep learning. It classifies retinal scans into four categories and provides visual explanations using Grad-CAM.

---

## 🧠 Problem Statement
Early detection of retinal diseases like CNV and DME is crucial for preventing vision loss. Manual diagnosis is time-consuming and requires expertise. This project aims to assist in automated and explainable diagnosis using AI.

---

## 📊 Dataset
- Source: Kaggle (Kermany2018 OCT Dataset)
- Classes:
  - CNV (Choroidal Neovascularization)
  - DME (Diabetic Macular Edema)
  - DRUSEN
  - NORMAL

---

## ⚙️ Methodology
- Data preprocessing (resizing, normalization)
- Transfer Learning using ResNet
- Model training using PyTorch
- Evaluation using accuracy, precision, recall, and F1-score
- Visualization using Grad-CAM

---

## 🚀 Results
- Achieved ~90–98% accuracy on test data
- Generated confusion matrix and classification report
- Successfully visualized model attention using Grad-CAM

---

## 👁️ Grad-CAM Visualization
Grad-CAM highlights the regions in the OCT image where the model focuses while making predictions, improving interpretability in medical AI.

(Add your screenshots here)

---

## 🛠️ Tech Stack
- Python
- PyTorch
- Torchvision
- OpenCV
- Matplotlib
- Scikit-learn

---

## 📁 Project Structure
