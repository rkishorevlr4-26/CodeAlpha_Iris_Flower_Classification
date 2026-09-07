# Iris Flower Classification — CodeAlpha Data Science Internship

## Project Overview
This project builds and evaluates multiple machine learning classification models to categorize Iris flowers into three species (*Setosa*, *Versicolor*, and *Virginica*) based on sepal and petal dimensions.

## Dataset
* **Source:** Scikit-learn Built-in Iris Dataset (Fisher's Iris)
* **Samples:** 150 instances (50 per class)
* **Features:** 
  * Sepal Length (cm)
  * Sepal Width (cm)
  * Petal Length (cm)
  * Petal Width (cm)
* **Target:** `species` (0: Setosa, 1: Versicolor, 2: Virginica)

## Workflow
1. **Exploratory Data Analysis (EDA):** Visualized multi-dimensional feature distributions and inter-class separability using Seaborn pairplots.
2. **Data Preprocessing:** Stratified train-test split (80/20) and standardized continuous features using `StandardScaler`.
3. **Model Training & Comparison:** Trained Logistic Regression, Support Vector Classifier (SVC), and Random Forest Classifier.
4. **Evaluation:** Evaluated accuracy, precision, recall, F1-scores, and confusion matrices.
5. **Inference Pipeline:** Built custom single-sample prediction pipeline.

## Model Performance & Results
| Model | Test Accuracy | Precision (Macro) | Recall (Macro) | F1-Score (Macro) |
| :--- | :---: | :---: | :---: | :---: |
| **Support Vector Machine (SVC)** | **100.00%** | **1.00** | **1.00** | **1.00** |
| Logistic Regression | 93.33% | 0.93 | 0.93 | 0.93 |
| Random Forest Classifier | 90.00% | 0.90 | 0.90 | 0.90 |

The linear Support Vector Classifier achieved 100% test accuracy on the hold-out test set with zero misclassifications.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/rkishorevlr4-26/CodeAlpha_Iris_Flower_Classification.git
   '''
   
