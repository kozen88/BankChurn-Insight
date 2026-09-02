# BankChurn-Insight: Enterprise Customer Attrition Data Mining Framework

A production-grade, highly modularized Data Mining and Predictive Modeling framework engineered to analyze, segment, and predict customer churn within the banking sector. Following the industry-standard **CRISP-DM methodology**, this project bypasses basic exploratory techniques to implement high-level analytical patterns—including advanced unsupervised clustering, complex dimensionality reduction for spatial visualization, and algorithmic frequent pattern mining.

## 📂 Project Materials & External Asset Architecture
Due to GitHub's strict file size boundaries and the massive storage footprint of relational data streams, large operational files and serialized model binaries have been decoupled from the codebase:

👉 [**Access Google Drive Project Folder**](https://drive.google.com/drive/folders/1N2vMyEzpSDIJY1jWgPUwK4XBm8F8LdxJ)

### 📦 Missing Files & Deployment Notice
> 📢 **Important:** If any binary file, massive output matrix, or deployment asset appears to be missing locally (such as the **238.55 MB Association Rules matrix** inside `FREQUENT_PATTERN_MINING/` or the **`best_churn_model.pkl`** binary inside `Imbalance_Approach/`), please **access the Google Drive link above** to recover the complete, uncompressed asset architecture.
>
> The full **40-page technical master report** is currently hosted on Drive in Italian (🇮🇹). A comprehensive technical translation and execution documentation in **English (🇬🇧)** will be uploaded directly to this repository shortly.

---

## 🛠️ Tech Stack & Project Modularization
- **Core Language & Stack:** Python (Pandas, NumPy, Scikit-Learn, SciPy)
- **Methodology Engine:** CRISP-DM (Cross-Industry Standard Process for Data Mining)
- **Modular Codebase Architecture:**
  - `01_Data_Wrangling.ipynb` (Standard Baseline Data Preparation & Imputation)
  - `02_Frequent_Pattern_Mining.ipynb` (FP-Growth & Apriori Market Basket Paradigms)
  - `03_Advanced_Clustering.ipynb` (Unsupervised Segmentation & Dimensionality Reduction)
  - `04_Supervised_Classification.ipynb` (Imbalanced Learning Pipelines)
  - `05_Ensemble_Optimization.ipynb` (Hyperparameter Tuning & Stacking Models)

---

## 🚀 Advanced Core Pillars & Engineering Strength Points

### 1. High-Tier Frequent Pattern Mining (FP-Growth & Apriori)
While 99% of junior profiles lack exposure to pattern mining frameworks, this engine implements raw **FP-Growth** and **Apriori** algorithms over the transactional layer. It isolates hidden behavior combinations and multi-variable churn triggers, extracting high-confidence rule matrices filtered by strict *Support, Confidence, and Lift* thresholds to map exactly how combinations of banking products influence customer flight.

### 2. Advanced Clustering & Spatial Dimensionality Reduction
Built a multi-stage unsupervised clustering pipeline to map out distinct behavioral personas:
- **Segmentation Engines:** Implemented algorithms (such as K-Means, DBSCAN, or Hierarchical Clustering) optimized to detect density-based groupings.
- **Dimensionality Reduction for Visual Analytics:** Utilized mathematical projection techniques (e.g., PCA, t-SNE) to compress high-dimensional client vector spaces into interpretable 2D/3D visual maps.
- **Granular Descriptive Statistics:** Every isolated cluster is thoroughly validated with specific descriptive statistics and feature distributions to extract actionable retention blueprints.

### 3. Class Imbalance Resolution & Supervised Pipelines
Tabular banking data suffers from heavy class skewness. This pipeline implements custom **SMOTE (Synthetic Minority Over-sampling Technique)** and tailored cost-sensitive class weights to reshape the feature space, shifting model optimization away from naive accuracy towards operational metrics like **Recall and F1-Score**.

### 4. Fine-Grained Hyperparameter Optimization & Ensemble Stacking
The classification suite features an independent optimization engine. It executes randomized and grid hyperparameter tuning over advanced estimators (Random Forests, Gradient Boosting, XGBoost), resolving overfitting and stacking multiple top-performing base learners into a unified meta-estimator designed to maximize business generalization.

---
*For any inquiries regarding modular code-review, data mining replication, or fintech consulting requests, please check the Google Drive repository or contact the owner.*
