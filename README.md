# Monkeypox Skin Disease Classification – Master's Research

This repository contains the source code, experiments, sample data, trained models, and evaluation results from my master's research on multi-class skin disease classification using deep learning.

 📘 Research Information

**Title:** Monkeypox Detection System Based on Skin Lesions using Deep Learning   
**Author:** Afnan Fahad Aljohani  
**Supervisor:** Prof. Dr. Mohammed Al-Sarem  
**University:** Taibah University 
**Department:** Information System  
**Year:** 2025 

---

 📌 Project Description

This research proposes a hybrid classification system for six skin conditions — including Monkeypox — using features extracted from three pre-trained CNNs (ResNet50, EfficientNetB0, MobileNetV2), enhanced by CBAM (Convolutional Block Attention Module), and classified using both an Artificial Neural Network (ANN) and multiple SVM kernels.

---
🧠 Key Components

- **CNN Feature Extractors:** ResNet50, EfficientNetB0, MobileNetV2  
- **Attention Mechanism:** CBAM (Channel & Spatial attention)  
- **Classifiers:** ANN (final model), SVM (Linear, RBF, Polynomial, Hybrid)  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, AUC, Confusion Matrix  

🗂 Dataset

## 🗂 Dataset

- **Original Dataset:**  
  Mpox Skin Lesion Dataset Version 2.0 (MSLD v2.0)  
  🔗 https://www.kaggle.com/datasets/joydippaul/mpox-skin-lesion-dataset-version-20-msld-v20

- **Final Balanced Dataset (used for model training):**  
  This dataset includes 1000 images per class after downsampling and augmentation.  
  🔗 [Download final_balanced_train.zip](https://github.com/Afnan23126/monkeypox-classification-MASTER-RESEARCH/releases/download/v1.0-balanced-data/final_balanced_train-20250504T170951Z-001.zip)

> All preprocessing and augmentation steps are documented and reproducible through the provided notebook.



## 🧪 How to Run the Code

1. Download or clone this repository.
2. Open the notebook file: MonkeyPoxClassification_MArch2025_Final_with_ANN_18_Mar.ipynb
3. 3. Run the notebook step-by-step using Jupyter Notebook or Google Colab.
4. Make sure you upload the required dataset folders and `.npy` feature files if not already present.
