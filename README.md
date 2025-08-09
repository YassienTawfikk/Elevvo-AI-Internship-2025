# Elevvo AI Internship 2025

---

## Overview

**Elevvo AI Internship 2025** is a curated umbrella repository containing six diverse AI/ML projects developed during my Elevvo internship. Each project is modular, standalone, and integrated as a Git submodule, covering a wide spectrum of machine learning techniques — from clustering and predictive modeling to recommendation systems, deep learning, and time-series forecasting.

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

| Project                      | Description                                                                  | Link                                                                                   |
| ---------------------------- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| **MediCluster**              | Patient segmentation using K-Means clustering and PCA visualization.         | [MediCluster](https://github.com/YassienTawfikk/MediCluster)                           |
| **PredictiLoan**             | Loan approval prediction using Logistic Regression and SVM.                  | [PredictiLoan](https://github.com/YassienTawfikk/PredictiLoan)                         |
| **MusicSpectroNet**          | Music genre classification via Tabular ML (XGBoost) and CNN on spectrograms. | [MusicSpectroNet](https://github.com/YassienTawfikk/MusicSpectroNet)                   |
| **SmartRetailRegressor**     | Walmart sales forecasting with Random Forest and XGBoost regression.         | [SmartRetailRegressor](https://github.com/YassienTawfikk/SmartRetailRegressor)         |
| **MovieMatch100K**           | Movie recommendation system using collaborative filtering and SVD.           | [MovieMatch100K](https://github.com/YassienTawfikk/MovieMatch100K)                     |
| **DriveSafe-Sign-Detection** | Traffic sign detection with custom CNN and MobileNetV2.                      | [DriveSafe-Sign-Detection](https://github.com/YassienTawfikk/DriveSafe-Sign-Detection) |

---

### Key Technical Highlights

#### **MediCluster**

* Complete preprocessing: missing value imputation (mode/median), label encoding, feature weighting for clinical relevance.
* K-Means clustering with optimal k determined by elbow method, validated with Calinski–Harabasz and Davies–Bouldin scores.
* PCA dimensionality reduction preserving 95% variance for visualization.
* Inference pipeline packaged via joblib for direct cluster prediction from raw input.

#### **PredictiLoan**

* Categorical encoding and scaling of financial, demographic, and credit score features.
* SMOTE applied for class imbalance handling.
* Model comparison between Logistic Regression and kernel-based SVM with hyperparameter tuning.
* Evaluation via confusion matrices, ROC curves, and cross-validated F1-scores.

#### **MusicSpectroNet**

* Dual-modality approach: tabular (Librosa-extracted audio features) and spectrogram-based CNN.
* MFCCs, chroma, spectral centroid, bandwidth, rolloff, zero-crossing rate engineered for tabular model.
* XGBoost model achieving 92.64% vs. CNN baseline at 23.33%.
* Detailed confusion matrix and feature importance visualizations.

#### **SmartRetailRegressor**

* Integration of sales, store, and holiday datasets with extensive date-based and holiday distance features.
* One-hot encoding for store/dept, sinusoidal encoding for seasonal periodicity.
* Model comparison: XGBoost (96.72% R²) outperforming Random Forest.
* Insights into feature importance and sales peaks around major holidays.

#### **MovieMatch100K**

* Implementation of user-based CF, item-based CF, and matrix factorization via SVD.
* Train/test split with ranking metrics: Precision\@K and Recall\@K.
* SVD achieving 41.78% Precision\@5 vs. \~6% for basic CF approaches.
* Handling of cold-start users and integration of genre/title metadata for richer recommendations.

#### **DriveSafe-Sign-Detection**

* Custom CNN trained from scratch on GTSRB dataset (43 classes) with dropout regularization.
* MobileNetV2 used as frozen feature extractor for baseline comparison (intentional underfitting scenario).
* Achieved 96.23% test accuracy on CNN; macro precision/recall both >0.94.
* Visual outputs: training curves, class distribution, confusion matrices.

---

### Setup Instructions

To clone with all submodules:

```bash
git clone --recurse-submodules https://github.com/YassienTawfikk/Elevvo-AI-Internship-2025.git
```

To explore a project:

```bash
cd MediCluster  # or any other submodule
pip install -r requirements.txt
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
