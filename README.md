# Room Occupancy Prediction using Machine Learning

## Overview

This project predicts the number of occupants in a room using environmental sensor data such as temperature, humidity, light intensity, and CO₂ concentration.

Multiple machine learning algorithms were trained and evaluated to identify the best-performing model.

---

## Dataset

This project uses the **Room Occupancy Estimation Dataset** available on Kaggle.

**Source:** https://www.kaggle.com/datasets/ananthr1/room-occupancy-estimation-data-set

---

## Features

- Data preprocessing
- Feature selection
- Model training
- Hyperparameter tuning using GridSearchCV
- 5-Fold Cross Validation
- Performance comparison across multiple models
- Confusion Matrix
- Classification Report
- Prediction visualization

---

## Models Used

- Random Forest
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## Results

**Best Model:** Random Forest

**Accuracy:** 99.31%

Random Forest achieved the highest overall performance among all evaluated models with an accuracy of approximately 99.3%.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Open and run the notebook:

```
Room_Occupancy_Prediction.ipynb
```

---

## Requirements

```
numpy
pandas
matplotlib
scikit-learn
```

---

## Repository Structure

```
Room-Occupancy-Prediction-ML/
│── README.md
│── requirements.txt
│── Room_Occupancy_Prediction.ipynb
│── images/
│   ├── confusion_matrix.png
│   ├── model_comparison.png
│   ├── cross_validation.png
│   └── prediction_plot.png
```

