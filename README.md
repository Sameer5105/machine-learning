# 🛡 Network Anomaly Detection - Machine Learning Classification Project

This project explores the application of machine learning models to detect network anomalies in a multi-class classification dataset.  
The dataset originally contained *350,000+ records* with severe class imbalance, making it a perfect case study for the impact of data imbalance on model performance.
---

## 📋 Project Overview

### 🔎 Objective
- Classify network traffic records as either *normal* or belonging to one of 7 anomaly types.
- Show how models completely fail on imbalanced data and dramatically improve after balancing.

### 🛠 Dataset
- Real-world network intrusion detection dataset
- 8 classes:
  - anomalous(DoSattack)
  - anomalous(dataProbing)
  - anomalous(malitiousControl)
  - anomalous(malitiousOperation)
  - anomalous(scan)
  - anomalous(spying)
  - anomalous(wrongSetUp)
  - normal

---

## 💡 Techniques Applied

- Exploratory Data Analysis (EDA)
- Class imbalance diagnosis
- Dataset balancing (under-sampling normal class)
- Data preprocessing: label encoding, Standardscaling
- Model evaluation with classification metrics

---

## 🤖 Models Trained

| Model | Imbalanced Data | Balanced Data |
|------|-----------------|---------------|
| SVM  | Failed (~12% accuracy)|Success (~99% accuracy) |


> *Conclusion:* Balancing the dataset was critical for fair performance.

---
