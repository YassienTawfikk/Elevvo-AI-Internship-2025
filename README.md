## Elevvo AI Internship 2025

---

### Overview

**Elevvo AI Internship 2025** is a curated umbrella repository containing **six advanced AI/ML projects** developed during my internship at Elevvo.
Each project is modular, production-ready, and integrated as a Git submodule — spanning clustering, prediction, recommendation systems, deep learning, and forecasting.

Every subproject includes its own full folder structure, dataset processing pipeline, and a detailed `README.md` with methodology, visualizations, and performance metrics.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd1b9599-6aa1-4bc4-8483-9645eb71598c" width="49%" alt="MediCluster">
  <img src="https://github.com/user-attachments/assets/d7f73d2d-63b7-4559-8534-aaf2244d7fad" width="49%" alt="PredictiLoan">
  <img src="https://github.com/user-attachments/assets/9c70cda3-dd4a-4f54-9557-af484d182792" width="49%" alt="MusicSpectroNet">
  <img src="https://github.com/user-attachments/assets/b9e05c58-8fd7-4e47-b21e-1e19aa52c5fe" width="49%" alt="SmartRetailRegressor">
  <img src="https://github.com/user-attachments/assets/64ec811e-d70d-4dfc-815b-30ee1da70a54" width="49%" alt="MovieMatch100K">
  <img src="https://github.com/user-attachments/assets/252feffe-5f2e-4be9-8cc6-0b14b2d49e19" width="49%" alt="DriveSafe-Sign-Detection">
</p>

---

## Included Projects

| Project                      | Description                                                                              | Link                                                                                   |
| ---------------------------- | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **MediCluster**              | Patient dataset clustering using **K-Means** & PCA for healthcare segmentation           | [MediCluster](https://github.com/YassienTawfikk/MediCluster)                           |
| **PredictiLoan**             | Loan approval prediction with **Logistic Regression** and **SVM**                        | [PredictiLoan](https://github.com/YassienTawfikk/PredictiLoan)                         |
| **MusicSpectroNet**          | GTZAN music genre classification — **XGBoost Tabular ML** vs. **CNN Spectrograms**       | [MusicSpectroNet](https://github.com/YassienTawfikk/MusicSpectroNet)                   |
| **SmartRetailRegressor**     | Walmart sales forecasting using **Random Forest** & **XGBoost**                          | [SmartRetailRegressor](https://github.com/YassienTawfikk/SmartRetailRegressor)         |
| **MovieMatch100K**           | Movie recommendation system — **User CF**, **Item CF**, and **SVD Matrix Factorization** | [MovieMatch100K](https://github.com/YassienTawfikk/MovieMatch100K)                     |
| **DriveSafe-Sign-Detection** | Traffic sign recognition — **Custom CNN** vs. **MobileNetV2 Baseline**                   | [DriveSafe-Sign-Detection](https://github.com/YassienTawfikk/DriveSafe-Sign-Detection) |

Each project is integrated as a **Git submodule**. To clone this repository and initialize all modules:

```bash
git clone --recurse-submodules git@github.com:YassienTawfikk/Elevvo-AI-Internship-2025.git
```

---

### Key Features

* **Healthcare Clustering (MediCluster/)**

  * Missing value handling, categorical encoding, scaling, PCA visualization
  * Optimized K-Means with stability and cluster metrics

* **Financial Risk Prediction (PredictiLoan/)**

  * Logistic Regression vs. SVM, SMOTE imbalance handling, ROC/PR analysis

* **Music Genre Classification (MusicSpectroNet/)**

  * Tabular ML (XGBoost) vs. CNN image-based learning
  * Feature importance analysis and spectrogram visualizations

* **Retail Sales Forecasting (SmartRetailRegressor/)**

  * Advanced feature engineering with date & holiday encodings
  * Random Forest vs. XGBoost regression performance comparison

* **Recommendation Systems (MovieMatch100K/)**

  * User-based CF, Item-based CF, SVD factorization
  * Precision\@K and Recall\@K evaluation metrics

* **Traffic Sign Recognition (DriveSafe-Sign-Detection/)**

  * Custom CNN architecture vs. frozen MobileNetV2 baseline
  * Dataset class distribution and comparative evaluation

---

### Setup Instructions

After cloning:

```bash
# Choose a project to explore
cd MediCluster  # or PredictiLoan, MusicSpectroNet, etc.

# Install dependencies
pip install -r requirements.txt

# Run the app or main script
python main.py
```

---

### Author

<div>
  <table align="center">
    <tr>
      <td align="center">
        <a href="https://github.com/YassienTawfikk" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/126521373?v=4" width="120px;" alt="Yassien Tawfik"/><br/>
          <sub><b>Yassien Tawfik</b></sub>
        </a>
      </td>
    </tr>
  </table>
</div>

---
