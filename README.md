# Diagnostic Intelligent - Cancer du Sein

## Projet Challenge : Application Web Interactive de Machine Learning

Système expert d'aide au diagnostic du cancer du sein utilisant l'Intelligence Artificielle

---

## Table des Matières

- [Aperçu du Projet](#aperçu-du-projet)
- [Architecture du Projet](#architecture-du-projet)
- [Interfaces et Fonctionnalités](#interfaces-et-fonctionnalités)
- [Visualisations et Analytics](#visualisations-et-analytics)
- [Algorithmes et Performances](#algorithmes-et-performances)
- [Installation et Déploiement](#installation-et-déploiement)
- [Résultats et Métriques](#résultats-et-métriques)
- [Perspectives d'Amélioration](#perspectives-damélioration)
- [Contact et Contribution](#contact-et-contribution)
- [Licence](#licence)
- [Disclaimer Médical](#disclaimer-médical)

---

## Aperçu du Projet

Ce projet propose une application web interactive de machine learning pour la classification des tumeurs mammaires en bénignes ou malignes. L’objectif est d’assister les professionnels de santé dans le diagnostic précoce grâce à une interface intuitive et des modèles d’IA performants.

### Dataset Utilisé

- Source : Wisconsin Breast Cancer Dataset  
- Échantillons : 569 patients  
- Caractéristiques : 30 paramètres cellulaires par tumeur  
- Classes : Bénin (357) / Malin (212)

### Objectifs Pédagogiques

- Développer une application web de machine learning
- Automatiser le traitement des données médicales
- Tester plusieurs modèles de classification
- Visualiser les résultats et leurs métriques
- Proposer une interface adaptée au contexte médical

---


### Technologies Utilisées

- Frontend : Streamlit  
- Machine Learning : Scikit-learn, XGBoost  
- Visualisation : Matplotlib, Plotly  
- Traitement des données : Pandas, NumPy  
- Déploiement : Streamlit Cloud / Local

---

## Interfaces et Fonctionnalités

### 1. Page d’Accueil Médical

![Accueil Médical](https://via.placeholder.com/800x400/1a73e8/ffffff?text=Page+Accueil+Médical)

Fonctionnalités :

- Présentation du système expert
- Indicateurs de performance (sensibilité, spécificité)
- Informations médicales sur le cancer du sein

### 2. Page de Diagnostic IA

![Diagnostic IA](https://via.placeholder.com/800x400/34a853/ffffff?text=Interface+Diagnostic+IA)

- Saisie de paramètres cellulaires via sliders
- Simulation du score de risque
- Rapport de diagnostic avec niveau de confiance

### 3. Page Analytics Patients

![Analytics Patients](https://via.placeholder.com/800x400/ea4335/ffffff?text=Analytics+et+Visualisations)

- Distributions et corrélations
- Analyse démographique
- Visualisations interactives

### 4. Page Algorithmes

![Algorithmes IA](https://via.placeholder.com/800x400/8e44ad/ffffff?text=Comparaison+Algorithmes)

- Tableau comparatif des modèles
- Performances et temps d’exécution

---

## Visualisations et Analytics

### Distribution des Paramètres Cliniques

![Distribution](https://via.placeholder.com/600x300/667eea/ffffff?text=Distribution+Paramètres)

### Matrice de Corrélation Médicale

![Corrélation](https://via.placeholder.com/600x300/764ba2/ffffff?text=Matrice+Corrélation)

### Analyse Probabiliste des Diagnostics

![Probabilités](https://via.placeholder.com/600x300/00b894/ffffff?text=Analyse+Probabiliste)

### Performance des Algorithmes

![Performance](https://via.placeholder.com/600x300/fd79a8/ffffff?text=Performance+Algorithmes)

---

## Algorithmes et Performances

| Algorithme | Accuracy | Precision | Recall | Temps (s) |
|------------|----------|-----------|--------|-----------|
| SVM | 97.4% | 96.8% | 96.2% | 2.1 |
| Random Forest | 96.5% | 95.9% | 95.4% | 1.8 |
| XGBoost | 95.6% | 94.7% | 94.9% | 3.2 |
| Logistic Regression | 95.2% | 94.2% | 94.8% | 0.5 |
| K-NN | 94.7% | 93.5% | 94.1% | 0.3 |
| Gradient Boosting | 93.8% | 92.6% | 93.2% | 4.1 |
| Decision Tree | 92.1% | 90.8% | 91.5% | 0.8 |

---

## Installation et Déploiement

### Installation Locale

```bash
git clone https://github.com/username/breast-cancer-prediction.git
cd breast-cancer-prediction
python -m venv medical_env
source medical_env/bin/activate  # Linux/Mac
medical_env\Scripts\activate     # Windows
pip install -r requirements.txt
streamlit run app.py
