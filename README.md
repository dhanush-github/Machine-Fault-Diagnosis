# Bearing-Fault-Diagnosis

This Repository is to understand the Machine Fault Diagnosis, Especially in Bearing Elements and their Conditional Monitoring

Dataset Link: https://data.nasa.gov/download/brfb-gzcv/application%2Fzip

The Test Setup: 


![image](https://github.com/dhanush-github/Machine-Fault-Diagnosis/assets/82599768/7215590e-e07f-45bc-b1c8-2909715c94cc)


Here’s a **clean, technical-yet-storytelling style README** for your
**Machine Fault Diagnosis & Prognosis** project—
leveraging all key steps, methods, and summary findings from your PPT. This will *wow* technical and business audiences alike!

---

```markdown
# 🏭 Machine Fault Diagnosis & Prognosis

**Author:** N. Sai Dhanush  
**Guide:** Dr. Ambika P.S, CEN Dept, Amrita Vishwa Vidyapeetham

---

## 🚀 Project Overview

This project tackles the crucial challenge of early fault detection and failure prediction in rotating machinery—using state-of-the-art statistical, machine learning, and deep learning techniques.  
From vibration data collection, through feature engineering, to final classification and RUL prediction, the pipeline delivers insights that can prevent costly downtime.

---

## 🎯 Objectives

- Diagnose faults in rolling element bearings (REB) using sensor data
- Predict the *remaining useful life (RUL)* of machine components
- Build a robust end-to-end pipeline: data pre-processing ➡️ feature engineering ➡️ model training

---

## 🛠️ Methodology

**1. Fault Diagnosis**
- Analyze vibration signals from rotating machines
- Extract statistical, time-domain, and frequency-domain features
- Label “faulty” vs. “healthy” states for bearings

**2. Fault Prognosis**
- Predict when a failure will occur (RUL) using current & historical sensor data
- Use both model-based and data-driven (machine learning) methods

---

### 📦 Data & Preprocessing

- **Datasets:** NASA IMS Bearing Dataset, FEMTO Dataset
- **Preprocessing:**  
  - Filtering, normalization (including DAIN deep normalization)
  - Time series reduction: Piecewise Aggregate Approximation (PAA)
  - Noise removal: Singular Spectrum Analysis
  - Change point detection: Deep autoencoder networks

---

### 🔎 Feature Engineering

- **Time-domain:** Mean, RMS, peak, kurtosis, skewness, crest factor
- **Frequency-domain:** Power spectral density, entropy
- **Wavelet features:** Energy coefficients
- **Autoencoder-learned features**
- **Feature selection:** Tree-based selectors, correlation to RUL

---

### 🤖 Modeling & Algorithms

- **Machine Learning:**  
  - Random Forest, CatBoost, SVM, Decision Trees  
  - PCA, LDA, clustering for fault pattern recognition
- **Deep Learning:**  
  - LSTM, RNN, GRU (for RUL sequence modeling)
  - CNNs, Autoencoders (for feature learning & change point detection)
- **Oversampling:** SMOTE to balance faulty/healthy classes

---

## 🏆 Results

- **Fault Classification:**  
  - *Random Forest, CatBoost* achieve up to **95–100% accuracy** (with oversampling/statistical features)
  - Hybrid deep + statistical features boost performance further
- **RUL Prediction:**  
  - Evaluated by R², RMSE, and percentage RUL error
  - LSTM and advanced DL models provide robust RUL forecasting

---

## 🗺️ Workflow

```

Data Preprocessing
↓
Feature Extraction & Selection
↓
Data Concatenation (across experiments)
↓
Faulty/Healthy Labeling
↓
Model Training (ML/DL)
↓
Evaluation & Visualization

```

---

## 📚 Key Concepts Explained

- **Fault Frequencies:** BPFO, BPFI, FTF, Ball Spin Frequency
- **Preprocessing Methods:** Filtering, smoothing, augmentation, normalization
- **Feature Extraction:** Time, frequency, wavelet, autoencoder
- **Prognosis Stages:** Data collection → Analysis → Fault identification → Evolution prediction → Action planning/execution

---

## 📁 Files Included

- `Machine Fault Diagnosis & Prognosis.pptx` — Methodology & presentation
- *Notebook/codebase and sample data files (add links if in repo)*

---

## 🔬 Future Work

- Explore *Dynamic Mode Decomposition (DMD)* for enhanced fault detection
- Extend deep learning methods to multi-modal sensor data

---



