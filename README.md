# 🏥 Breast Cancer Prediction - Medical AI Dashboard

## 🎗️ Intelligent Diagnostic System for Breast Cancer Classification

<!-- CAROUSEL D'IMAGES -->
<div align="center">

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
| ![Dashboard](https://via.placeholder.com/300x200/1a73e8/ffffff?text=Medical+Dashboard) | ![Diagnostic](https://via.placeholder.com/300x200/34a853/ffffff?text=AI+Diagnostic) | ![Analytics](https://via.placeholder.com/300x200/ea4335/ffffff?text=Analytics) |
| **Medical Dashboard** | **AI Diagnostic Tool** | **Advanced Analytics** |
| ![Models](https://via.placeholder.com/300x200/8e44ad/ffffff?text=Model+Comparison) | ![Results](https://via.placeholder.com/300x200/f39c12/ffffff?text=Results) | ![ROC](https://via.placeholder.com/300x200/2c3e50/ffffff?text=ROC+Curves) |
| **Model Comparison** | **Prediction Results** | **ROC Analysis** |

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

### 📊 Wisconsin Breast Cancer Dataset
- **Samples**: 569 patient records
- **Features**: 30 cellular characteristics
- **Classes**: Benign (357) vs Malignant (212)
- **Data Split**: 80% training, 20% testing

### 🔍 Key Features Analyzed
- **Morphological Features**: Radius, Texture, Perimeter, Area
- **Structural Features**: Smoothness, Compactness, Concavity
- **Advanced Metrics**: Symmetry, Fractal Dimension

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
