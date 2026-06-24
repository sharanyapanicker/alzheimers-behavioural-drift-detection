# Alzheimer's Behavioural Drift Detection

**MSc Artificial Intelligence with Business Strategy Dissertation**
*Aston University (2025)*

## Overview

This project investigates the generation and validation of synthetic smart-home sensor data for detecting behavioural drift associated with early-stage Alzheimer's disease.

The project extends the SHARON (Simulator of Human Activities, ROutines and Needs) framework to generate long-term smart-home datasets containing progressive behavioural changes such as disrupted sleep patterns, irregular toileting, and meal-related routine changes. The generated datasets were validated against the CASAS benchmark dataset and used to evaluate multiple anomaly detection models.

---

## Research Questions

* Can synthetic smart-home sensor data realistically represent daily living behaviours?
* Can anomaly detection models identify progressive behavioural drift in smart-home environments?
* Does increasing the amount of pre-drift training data improve anomaly detection performance?

---

## Methodology

### Synthetic Data Generation

* Extended and customised the SHARON simulator
* Generated normal and behavioural drift datasets
* Simulated Activities of Daily Living (ADLs)
* Modelled progressive dementia-inspired routine changes

### Dataset Validation

Synthetic datasets were compared against the CASAS benchmark dataset using:

* Entropy Analysis
* Jaccard Similarity

### Anomaly Detection

The following models were evaluated:

* Isolation Forest
* One-Class SVM
* Autoencoder
* LSTM

Experiments were conducted using multiple training horizons (30, 90, and 120 days) to evaluate model robustness under behavioural drift.

---

## Technologies Used

### Simulation

* Java
* SHARON Simulator
* Apache Ant

### Data Processing & Machine Learning

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow
* Keras

### Development Environment

* Google Colab
* GitHub


## Key Outcomes

* Generated synthetic smart-home datasets containing progressive behavioural drift.
* Validated synthetic data against the CASAS benchmark dataset.
* Evaluated both classical machine learning and deep learning approaches for anomaly detection.
* Demonstrated the potential of synthetic smart-home data for dementia-focused anomaly detection research.

---

## Acknowledgements

This project builds upon the SHARON (Simulator of Human Activities, ROutines and Needs) framework developed by the Artificial Intelligence and Decision Support Systems Laboratory (ATG), Politecnico di Milano.

Original SHARON Repository:

https://github.com/ATG-PoliMi/Sharon

The simulator was extended and customised as part of this dissertation to support behavioural drift modelling and anomaly detection research in dementia-focused smart-home environments.
