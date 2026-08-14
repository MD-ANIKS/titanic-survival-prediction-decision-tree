#  Titanic Survival Prediction using Decision Tree

A machine learning classification project that predicts whether a passenger survived the Titanic disaster using a **Decision Tree Classifier**.

This project follows a complete classification workflow, including data preprocessing, feature preparation, model implementation, prediction, and performance evaluation.

##  Project Overview

The Titanic dataset is used to predict passenger survival.

The target variable is:

* `0` → Did not survive
* `1` → Survived

The main goal of this project is to implement a **Decision Tree** classification model and evaluate its performance using standard classification metrics.

##  Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

##  Machine Learning Workflow

1. Load the Titanic dataset
2. Explore the dataset
3. Clean and preprocess the data
4. Handle missing values
5. Encode categorical features
6. Separate features and target
7. Split the dataset into training and testing sets
8. Apply feature scaling
9. Implement the Decision Tree classifier
10. Make predictions
11. Evaluate the model

##  Decision Tree

The project uses the **Decision Tree Classifier** from Scikit-learn.

A Decision Tree makes predictions by learning a series of decision rules from the input features. The model recursively splits the data based on feature conditions to classify passengers into survival categories.

##  Model Performance

The Decision Tree model achieved an accuracy of:

**80.34%**

```text
Accuracy: 0.8033707865168539
```

### Confusion Matrix

```text
[[90, 16],
 [19, 53]]
```

The confusion matrix represents the model's predictions compared with the actual survival classes.

### Classification Report

```text
              precision    recall  f1-score   support

           0       0.83      0.85      0.84       106
           1       0.77      0.74      0.75        72

    accuracy                           0.80       178
   macro avg       0.80      0.79      0.79       178
weighted avg       0.80      0.80      0.80       178
```

### Performance Summary

| Metric    | Class 0 | Class 1 |
| --------- | ------: | ------: |
| Precision |    0.83 |    0.77 |
| Recall    |    0.85 |    0.74 |
| F1-Score  |    0.84 |    0.75 |
| Support   |     106 |      72 |

**Overall Accuracy:** `80.34%`

##  Project Structure

```text
titanic-survival-prediction-decision-tree/
│
├── titanic_survival_prediction_decision_tree.ipynb
├── README.md
```

##  How to Run

### 1. Clone the repository

```bash
git clone https://github.com/MD-ANIKS/titanic-survival-prediction-decision-tree.git
```

### 2. Navigate to the project

```bash
cd titanic-survival-prediction-decision-tree
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
titanic_survival_prediction_decision_tree.ipynb
```

##  Outcomes

Through this project:

* Data preprocessing
* Handling missing values
* Feature preparation
* Categorical feature encoding
* Train-test splitting
* Decision Tree classification
* Making predictions
* Confusion Matrix
* Classification Reports
* Precision
* Recall
* F1-score
* Accuracy evaluation

##  Model Evaluation

The Decision Tree model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report


---

**Machine Learning Project | Decision Tree Classification**
