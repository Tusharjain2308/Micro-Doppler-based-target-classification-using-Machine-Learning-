# 🛰️ Micro-Doppler Signature Classification: Bird vs Drone

This project aims to classify radar-based micro-Doppler signatures into three categories: **Bird**, **Drone**, and **Bird+Drone**, using deep learning (ResNet-50) for feature extraction and classical machine learning models for final classification.

The implementation is done in a Jupyter Notebook: `Major_project_MicroDoppler.ipynb`.

---

## 🧠 Project Highlights

- ✅ **End-to-End Pipeline**: Preprocessing → Deep Feature Extraction → ML Classification  
- 🧠 **ResNet-50 Backbone**: Used to extract 2048-dimensional feature vectors  
- 📊 **Classical ML Models**: Trained on extracted features using:
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors
  - Logistic Regression
  - Stacking Classifier  
- 📁 **Multi-type Inputs**: Uses three radar-derived representations:
  - Spectrograms
  - Cepstrograms
  - Constant Velocity Diagrams (CVDs)

---



