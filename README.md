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
- **Mean Absolute Error (MAE):** 0.0108
- **Mean Squared Error (MSE):** 0.0069
- **Root Mean Squared Error (RMSE):** 0.0829

Random Forest achieved the highest overall performance among all evaluated models with an accuracy of approximately 99.3%.


## Results

**Random Forest Regressor**
- Accuracy: **99.31%**
- Mean Absolute Error (MAE): **0.0108**
- Root Mean Squared Error (RMSE): **0.0829**

**Decision Tree Regressor**
- Accuracy: **99.26%**
- Mean Absolute Error (MAE): **0.0095**
- Root Mean Squared Error (RMSE): **0.0814**

**Support Vector Machine (SVM)**
- Accuracy: **97.93%**
- Mean Absolute Error (MAE): **0.0928**
- Root Mean Squared Error (RMSE): **0.2644**

**k-Nearest Neighbors (k-NN)**
- Accuracy: **98.96%**
- Mean Absolute Error (MAE): **0.0147**
- Root Mean Squared Error (RMSE): **0.1008**



5-Fold Cross-Validation Results
Model                          Accuracy                MAE               RMSE        Weighted F1
----------------------------------------------------------------------------------------------
Random Forest           0.9922 ± 0.0015    0.0104 ± 0.0019    0.0858 ± 0.0146    0.9922 ± 0.0015
Decision Tree           0.9924 ± 0.0013    0.0092 ± 0.0021    0.1151 ± 0.0218    0.9924 ± 0.0013
SVM                     0.9827 ± 0.0010    0.0671 ± 0.0029    0.1603 ± 0.0195    0.9827 ± 0.0010
k-NN                    0.9895 ± 0.0028    0.0140 ± 0.0025    0.1045 ± 0.0157    0.9896 ± 0.0028



### Model Selection

Random Forest Regressor was selected as the final model due to its highest overall accuracy (99.31%), strong generalization capability, and robustness against overfitting. Its ensemble learning approach combines multiple decision trees to produce stable and reliable predictions for room occupancy estimation.

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
Hyperparameter Tuning Results (GridSearchCV)
Best Parameters: {'bootstrap': False, 'max_depth': 10, 'max_features': 'sqrt', 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 100}
Best CV Score: 0.9909798821330014


Project Structure
Room-Occupancy-Prediction-ML/
├── README.md
├── requirements.txt
├── Room_Occupancy_Prediction.ipynb
├── circuit_schematic.png
├── classification_report.png
├── confusion_matrix.png
├── model_performance_comparison.png
├── cross_validation_accuracy.png
└── signal_conditioned.png


