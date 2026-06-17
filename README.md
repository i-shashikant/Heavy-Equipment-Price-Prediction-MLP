# 🚜 Heavy Equipment Selling Price Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF)
![Status](https://img.shields.io/badge/Status-Active-success)

## 📖 Overview

This repository contains my **Machine Learning Practice (MLP)** project for the IIT Madras BS Degree Program.

The objective of this project is to predict the selling price of heavy equipment using machine learning techniques on a real-world Kaggle competition dataset.

---

## 🎯 Objective

Given various characteristics of heavy equipment such as:

- Manufacturing Year
- Operational Hours
- Product Configuration
- Vendor Information
- Asset Specifications
- Equipment Category

The task is to predict the transaction value (`TargetValue`) of the equipment.

---

## 📊 Dataset

**Competition:** Heavy Equipment Selling Price Prediction Challenge

Dataset Files:

- train.csv
- test.csv
- sample_submission.csv
- metadata.csv

### Training Data

- 138,701 observations
- 50 columns

### Test Data

- 15,000 observations
- 49 feature columns

Target Variable:

```
TargetValue
```

---

## 🧠 Machine Learning Workflow

```
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Baseline Model
   ↓
Model Evaluation
   ↓
Prediction
   ↓
Kaggle Submission
```

---

## 🤖 Baseline Model

### Dummy Regressor

The first baseline model implemented is:

```
DummyRegressor(strategy="mean")
```

This model ignores all input features and predicts the average target value for every observation.

### Purpose

- Establish a baseline performance.
- Compare future models against a simple benchmark.

---

## 📈 Current Performance

### Baseline Model

| Model | Score |
|-------|--------|
| DummyRegressor | 0.69962 |

Current Kaggle Leaderboard Rank:

```
~480
```

*(Leaderboard rank and score may improve as the project progresses.)*

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Kaggle Notebook
- Git
- GitHub

---

## 📂 Repository Structure

```
.
├── notebooks/
├── submissions/
├── images/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🚀 Future Improvements

The project roadmap includes:

- Data Cleaning
- Feature Engineering
- Handling Missing Values
- Categorical Encoding
- Random Forest Regressor
- Gradient Boosting
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Comparison

---

## 📚 Key Concepts Learned

During this project:

- Train/Test Split
- Features and Target Variable
- Baseline Models
- DummyRegressor
- Model Training (`fit`)
- Model Prediction (`predict`)
- Kaggle Submission Pipeline
- Machine Learning Workflow

---

## 🎓 Academic Context

This project is part of the **Machine Learning Practice (MLP)** course under the IIT Madras BS Degree Program.

The work involves:

- Kaggle Competition Participation
- Machine Learning Model Development
- Notebook Documentation
- Continuous Model Improvement
- Project Evaluation and Viva

---

## 📌 Current Progress

- [x] Kaggle Competition Joined
- [x] Notebook Created
- [x] Dataset Imported
- [x] Data Exploration
- [x] Baseline DummyRegressor
- [x] First Kaggle Submission
- [ ] Data Preprocessing
- [ ] Random Forest Model
- [ ] Hyperparameter Tuning
- [ ] Advanced Ensemble Models

---

## 📜 License

This project is developed for educational and academic purposes.

---

## 👨‍💻 Author

**Shashikant**

IIT Madras BS Degree Program

Machine Learning Practice (MLP)

2026