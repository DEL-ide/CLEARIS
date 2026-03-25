# CLEARIS

**Machine learning-based model for Prognostic Risk Stratification in Cervical Clear Cell Adenocarcinoma: A global modelling study**

---

## Overview

This repository contains the Python implementation of the **CLEARIS** framework, developed for **prognostic risk assessment in cervical clear cell adenocarcinoma (CCCA)**.

The codebase focuses on:

* Survival model development and optimization
* Model performance evaluation
* Risk stratification and visualization

⚠️ **Note:**
All features used in this study were pre-selected in the R environment and are described in detail in the manuscript. This repository performs downstream modeling and analysis based on the selected features.

🌐 **Web Application:**
A web-based implementation of the CLEARIS model is available at:
👉 https://ccacsurvival.com/

---

## Methodological Framework

The Python implementation of CLEARIS includes the following components:

### 1. Model Development and Optimization

* Survival models are constructed using pre-selected features
* Hyperparameter tuning is performed using **Optuna**
* **5-fold cross-validation** is applied to improve model robustness and generalization

---

### 2. Model Evaluation

* Model performance is assessed using:

  * Concordance index (C-index)
* External validation can be performed if applicable

---

### 3. Risk Stratification and Visualization

* Patients are stratified based on predicted risk scores
* Three risk groups are defined:

  * Low-risk
  * Intermediate-risk
  * High-risk
* Visualization includes:

  * Kaplan–Meier survival curves
  * Risk stratification plots

---

## Outputs

The pipeline generates:

* Individual patient risk scores
* Time-dependent risk predictions (e.g., 1-, 3-, and 5-year survival risk)
* Survival analysis visualizations suitable for publication

---

## Disclaimer

This model is intended for research purposes only. Further validation in multi-center and prospective cohorts is required before clinical application.

---
