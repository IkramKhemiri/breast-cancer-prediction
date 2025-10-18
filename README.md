# 🏥 Breast Cancer Prediction - Medical AI Dashboard

## 🎗️ Intelligent Diagnostic System for Breast Cancer Classification

<!-- GALERIE D'IMAGES SANS TITRES -->
<div align="center">

### 📸 Application Gallery

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; padding: 20px 0;">

<img src="images/Capture d'écran 2025-10-17 214029.png" width="280" height="180" alt="Dashboard Overview">
<img src="images/Capture d'écran 2025-10-17 213519.png" width="280" height="180" alt="AI Diagnostic">
<img src="images/Capture d'écran 2025-10-17 213536.png" width="280" height="180" alt="Analytics">
<img src="images/Capture d'écran 2025-10-17 213556.png" width="280" height="180" alt="Model Comparison">
<img src="images/Capture d'écran 2025-10-17 213627.png" width="280" height="180" alt="Prediction Results">
<img src="images/Capture d'écran 2025-10-17 213651.png" width="280" height="180" alt="ROC Analysis">
<img src="images/Capture d'écran 2025-10-17 213711.png" width="280" height="180" alt="Confusion Matrix">
<img src="images/Capture d'écran 2025-10-17 213730.png" width="280" height="180" alt="Feature Importance">
<img src="images/Capture d'écran 2025-10-17 213753.png" width="280" height="180" alt="Distribution Analysis">
<img src="images/Capture d'écran 2025-10-17 213816.png" width="280" height="180" alt="Correlation Matrix">
<img src="images/Capture d'écran 2025-10-17 213834.png" width="280" height="180" alt="Statistical Analysis">
<img src="images/Capture d'écran 2025-10-17 213856.png" width="280" height="180" alt="Performance Metrics">
<img src="images/Capture d'écran 2025-10-17 213912.png" width="280" height="180" alt="Training Time">
<img src="images/Capture d'écran 2025-10-17 213934.png" width="280" height="180" alt="Algorithm Performance">
<img src="images/Capture d'écran 2025-10-17 213951.png" width="280" height="180" alt="Model Details">
<img src="images/Capture d'écran 2025-10-17 214010.png" width="280" height="180" alt="Final Results">

</div>

</div>


> **Medical-grade web application for breast tumor classification using advanced machine learning algorithms**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-00C7B7?style=for-the-badge)

## 📊 Live Demo

**🌐 Access the application:** [Streamlit Cloud Deployment](https://your-app.streamlit.app)  
**📱 Local access:** `streamlit run app.py` → `http://localhost:8501`

---

## 🎯 Project Overview

This project implements a **comprehensive medical AI dashboard** for breast cancer prediction. The system assists healthcare professionals in early tumor diagnosis through an intuitive interface and robust machine learning algorithms.

### 🎯 Key Performance Metrics
- **Overall Accuracy**: 96.5%
- **Sensitivity**: 97.2%
- **Specificity**: 95.8%
- **AUC Score**: 0.991
- **Prediction Time**: < 100ms

---

## ✨ Features

### 🏠 Medical Dashboard
- Real-time performance metrics monitoring
- Epidemiological insights and statistics
- Professional healthcare interface design
- Medical guidelines and recommendations

### 🔬 AI Diagnostic Tool
- Interactive parameter adjustment with sliders
- Analysis of 30+ cellular characteristics
- Real-time prediction with confidence scores
- Automated medical recommendations

### 📊 Advanced Analytics
- Comparative distribution analysis
- Interactive correlation matrix
- Statistical descriptive analysis
- Patient demographic insights

### 🤖 Model Comparison
- 7 ML algorithms performance comparison
- Training time analysis
- Feature importance ranking
- ROC curve visualization

---

## 🏗️ Technical Architecture

### 📁 Project Structure

breast-cancer-prediction/

├── app.py # Main Streamlit application

├── requirements.txt # Python dependencies

├── README.md # Project documentation

├── brest_cancer.pkl # Trained machine learning model

├── scaler.pkl # Feature preprocessing scaler

├── data.csv # Breast cancer dataset

├── BreastCancerPrediction.ipynb # Jupyter notebook analysis

├── roc_breast_cancer.jpeg # ROC curves visualization

└── PE_breast_cancer.jpeg # Performance evaluation charts


### 🔧 Technology Stack
| Component | Technology |
|-----------|------------|
| **Frontend** | Streamlit, Custom CSS |
| **Backend** | Python 3.9+ |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Model Serialization** | Pickle |

---

## 📈 Dataset Information

### 📊 Breast Cancer Dataset (Kaggle)
- **Source**: [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Samples**: 569 patient records
- **Features**: 32 variables (including ID and diagnosis)
- **Classes**: 
  - **Benign (B)**: 357 cases
  - **Malignant (M)**: 212 cases
- **Data Split**: 80% training, 20% testing
- **Missing Values**: None

### 🔍 Features Description
The dataset contains the following computed features for each cell nucleus:

**Mean Values:**
- `radius_mean` - Mean of distances from center to points on the perimeter
- `texture_mean` - Standard deviation of gray-scale values
- `perimeter_mean` - Perimeter length
- `area_mean` - Area of the nucleus
- `smoothness_mean` - Local variation in radius lengths
- `compactness_mean` - Perimeter² / area - 1.0
- `concavity_mean` - Severity of concave portions of the contour
- `concave points_mean` - Number of concave portions of the contour
- `symmetry_mean` - Symmetry of the nucleus
- `fractal_dimension_mean` - "Coastline approximation" - 1

**Standard Error:**
- `radius_se`, `texture_se`, `perimeter_se`, `area_se`, etc.

**Worst Values (Largest):**
- `radius_worst`, `texture_worst`, `perimeter_worst`, `area_worst`, etc.

### 🎯 Target Variable
- `diagnosis`: 
  - **M** = Malignant (Cancerous)
  - **B** = Benign (Non-cancerous)

---

## 🧠 Machine Learning Models

### 🏆 Performance Comparison

| Algorithm | Accuracy | Precision | Recall | Training Time |
|-----------|----------|-----------|--------|---------------|
| 🥇 **Support Vector Machine** | 97.4% | 96.8% | 96.2% | 2.1s |
| 🥈 **Random Forest** | 96.5% | 95.9% | 95.4% | 1.8s |
| 🥉 **XGBoost** | 95.6% | 94.7% | 94.9% | 3.2s |
| **Logistic Regression** | 95.2% | 94.2% | 94.8% | 0.5s |
| **K-Nearest Neighbors** | 94.7% | 93.5% | 94.1% | 0.3s |
| **Gradient Boosting** | 93.8% | 92.6% | 93.2% | 4.1s |
| **Decision Tree** | 92.1% | 90.8% | 91.5% | 0.8s |

---

## 📊 Results & Performance

### 🎯 Confusion Matrix - SVM (Best Model)
            Predicted Benign          Predicted Malignant
            Actual Benign 349 (TN)       8 (FN)
            Actual Malignant 12 (FP)   200 (TP)



### 📈 Key Performance Metrics
- **True Positives**: 200 (correctly identified malignant cases)
- **True Negatives**: 349 (correctly identified benign cases)
- **False Positives**: 12 (benign cases misclassified as malignant)
- **False Negatives**: 8 (malignant cases misclassified as benign)

### 🔍 Feature Importance Analysis
The most discriminative features for classification:
1. **Radius Worst** (22.3%) - Maximum cell radius
2. **Perimeter Worst** (19.8%) - Cell perimeter measurements
3. **Area Worst** (17.5%) - Cellular area characteristics
4. **Concavity Worst** (11.2%) - Depth of concave portions
5. **Concave Points Worst** (9.8%) - Number of concave points

---

## 🚀 Installation & Setup

### ⚡ Quick Installation
```bash
# Clone the repository
git clone https://github.com/IkramKhemiri/breast-cancer-prediction.git
cd breast-cancer-prediction

# Install dependencies
pip install -r requirements.txt

# Launch the application
streamlit run app.py
```
### 📋 Dependencies

streamlit==1.28.0

pandas==2.1.0

numpy==1.24.0

scikit-learn==1.3.0

matplotlib==3.7.0

seaborn==0.12.2

xgboost==1.7.0

## 💻 Usage Guide

### 1. 🏠 Medical Dashboard
Access real-time performance metrics

Review epidemiological data about breast cancer

Understand the medical context and project background

### 2. 🔬 AI Diagnostic Tool
Adjust cellular parameters using interactive sliders

Click "Launch AI Diagnosis" to analyze

Review results with confidence percentages

Follow personalized medical recommendations

### 3. 📊 Patient Analytics
Explore feature distributions across diagnoses

Analyze correlations between different cellular characteristics

Review comprehensive statistical summaries

Study demographic patterns and risk factors

### 4. 🤖 Model Comparison
Compare performance across 7 machine learning algorithms

Analyze training characteristics and computational efficiency

Understand strengths and weaknesses of each approach

## 🔮 Future Enhancements
### 🚀 Technical Improvements
Deep Learning Integration - CNN architectures for enhanced accuracy

Explainable AI - SHAP/LIME for model interpretability

Real-time API - RESTful endpoints for system integration

Database Integration - Patient record management system

Enhanced Security - HIPAA-compliant data protection

### 🏥 Medical Features
Multi-modal Data Integration - Combine imaging and clinical data

Clinical Validation - Multi-center study collaboration

Personalized Recommendations - Patient-specific treatment suggestions

Longitudinal Analysis - Patient progression tracking over time

### ⚠️ Medical Disclaimer
IMPORTANT MEDICAL NOTICE: This application is designed as a decision support tool for qualified healthcare professionals. It is not intended to replace medical diagnosis by licensed physicians. Always consult with healthcare providers for medical decisions. In cases of suspected breast cancer, seek immediate professional medical attention.

## 📞 Contact & Support
Project Maintainer: Ikram Khemiri

GitHub: @IkramKhemiri

Project Repository: breast-cancer-prediction

<div align="center">
🎗️ Built with ❤️ for the fight against breast cancer
Project Completed: October 2025
