# Fusion-Enhanced-Contrastive-Learning-for-Human-Activity-Recognition
 Developing a Temporal Fusion Contrastive Learning (TFCL) framework for Human Activity Recognition using wearable sensors. By fusing biometric features with accelerometer and gyroscope data, TFCL achieved superior accuracy over CNN, LSTM, and ML models, with a web app for real-time activity visualization.

This project presents a **Temporal Fusion Contrastive Learning (TFCL) framework** for **Human Activity Recognition (HAR)** using wearable sensor data.  
It integrates **biometric features** (e.g., age, height, gait) with **sensor data** (accelerometer, gyroscope) to enable **robust, personalized, and privacy-aware recognition**.  

A **web-based application**, deployed using **WAMP server**, provides real-time and historical activity visualization, making the framework interactive and accessible.  

---

## 📌 Problem Statement
Human Activity Recognition plays a vital role in fitness tracking, healthcare, and smart wearables.  
However, existing HAR models:  
- Depend heavily on **labeled datasets**, which are expensive and privacy-sensitive.  
- Fail to **generalize across users**, reducing personalization and adaptability.  

This project addresses these challenges with a **fusion-enhanced self-supervised learning approach**.  

---

## 🏗️ Architecture
- **TFCL (Proposed Framework):**  
  - Combines **sensor data** (accelerometer, gyroscope) with **biometric metadata**.  
  - Uses **contrastive learning** to learn robust, adaptive representations.  

- **Baselines for Comparison:**  
  - Deep Learning: CNN, LSTM  
  - Classical ML: SVM, Random Forest, KNN  

---

## ⚙️ Requirements
Install dependencies with:  

```bash
pip install -r requirements.txt
