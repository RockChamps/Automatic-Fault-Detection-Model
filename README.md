# Automatic-Fault-Detection-Model
Machine Learning and Deep Learning Project - Automatic Fault Detection Model 
# 🔊 AI-Based Engine Fault Diagnosis Using Acoustic Signals

> An intelligent system that listens to machines and understands their health.

---

## 🚀 Overview

This project demonstrates an AI-driven approach to **engine fault diagnosis using sound signals**.  
By analyzing acoustic patterns produced by engine components, the system classifies **normal vs faulty conditions** without requiring physical inspection or intrusive sensors.

The complete pipeline is implemented and tested in **Google Colab**, showcasing how raw engine audio can be transformed into actionable machine intelligence.

---

## 🧠 Motivation

Modern engines generate rich acoustic signatures that reflect their internal condition.  
Leveraging these signals enables:

- Early fault detection before mechanical failure
- Non-invasive and cost-effective diagnostics
- Scalable solutions for smart maintenance systems
- Alignment with Industry 4.0 and AIoT ecosystems

This project focuses on **listening to machines** rather than dismantling them.

---

## 🏗️ Key Features

- Multi-class engine condition recognition  
- Robust audio preprocessing and normalization  
- Extraction of meaningful spectral and temporal features  
- Balanced and controlled train/test data split  
- Waveform visualization for signal-level inspection  
- Modular pipeline suitable for future expansion  

---

## 🧩 Engine Conditions Covered

### ✅ Healthy States
- Timing Chain  
- Piston Spark  
- Head Engine  
- Exhaust  

### ❌ Faulty States
- Faulty Timing Chain  
- Faulty Piston Spark  
- Faulty Head Engine  
- Faulty Exhaust  

Each condition is treated as a distinct acoustic identity.

---

## 🔄 Workflow Overview
Raw Engine Audio
↓
Audio Cleaning & Normalization
↓
Feature Extraction
↓
Dataset Structuring
↓
Train / Test Split
↓
Model-Ready Feature Vectors


The workflow is modular and easily adaptable to new models, datasets, or deployment targets.

---

## 📊 Dataset Strategy

- Controlled number of samples per class  
- Equal representation in training and testing  
- Transparent file-level inspection  
- Strict class-wise separation  

This ensures fair evaluation and reproducibility of results.

---

## 🛠️ Tech Stack

- Python  
- Librosa  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  
- Google Colab  

---

## 🔮 Future Scope

- Real-time inference using edge devices (ESP32, microcontrollers)
- CNN-based learning on spectrograms
- Cloud API for live engine diagnostics
- Web or mobile dashboard for visualization
- Industrial-scale predictive maintenance systems

---

## 🎯 Applications

- Predictive Maintenance  
- Automotive Diagnostics  
- Smart Manufacturing  
- Research & Academic Projects  
- Hackathons and Innovation Challenges  

---

## 👨‍💻 Author

**Durva K and Aditya D**  
Artificial Intelligence & Data Science  

> “Machines speak through sound — AI makes sense of it.”
