# TNBC_PREDICTIONS_

# 🧬 Deep Learning and Metabolomics  for Biomaker Discovery in Triple-Negative Breast Cancer (TNBC): Insights from Explainable AI and Pathway Enrichment.

This project leverages machine learning and deep learning techniques to classify **Triple-Negative Breast Cancer (TNBC)** into four molecular subtypes using metabolomic data. It incorporates **explainable AI (SHAP)** and **pathway enrichment analysis** to enhance biomarker discovery.

---

## 🎯 Objectives

- Build accurate classification models for TNBC subtypes from metabolomics data
- Compare performance between traditional ML and deep learning models
- Apply SHAP to interpret model decisions and identify top predictive metabolites
- Conduct pathway enrichment analysis on identified biomarkers

---

## 🧪 Dataset

- **Data Source**: Preprocessed metabolomics dataset with 70+ metabolic features
- **Target**: TNBC subtypes (BL1, BL2, LAR, M)
- **Preprocessing**:
  - UMAP for dimensionality reduction (70 → 10 features)
  - K-Means clustering for subtype annotation
  - ANOVA for top metabolite selection

---

## 🧠 Models Implemented

### ✅ Traditional Machine Learning
- Logistic Regression
- K-Nearest Neighbors
- XGBoost
- Support Vector Machine (SVM)

### ✅ Deep Learning Architectures
- Fully Connected Neural Network (FCNN)
- Residual CNN (ResCNN)
- BiLSTM
- Transformer

---

## 📊 Model Performance (Best Results)

| Model       | Accuracy | ROC-AUC | F1 Score |
|-------------|----------|---------|----------|
| FCNN        | 96.4%    | 0.98    | 0.95     |
| ResCNN      | 95.7%    | 0.97    | 0.94     |
| BiLSTM      | 94.1%    | 0.96    | 0.93     |
| Transformer | 93.3%    | 0.95    | 0.92     |

> FCNN demonstrated the best performance across all key metrics.

---

## 🔍 Explainability with SHAP

- Applied SHAP (SHapley Additive exPlanations) to interpret model predictions
- Identified top metabolic features contributing to subtype classification
- Generated summary plots and subtype-specific SHAP visualizations

![SHAP Summary Plot](path/to/your/shap_summary_image.png)

---

## 🧬 Pathway Enrichment Analysis

- Used MetaboAnalyst to explore biological significance of SHAP-ranked features
- Identified dysregulated pathways unique to each TNBC subtype
- Enhanced understanding of metabolic signatures for potential biomarkers

---

## 📂 Repository Structure
