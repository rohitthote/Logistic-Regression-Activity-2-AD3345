# Logistic-Regression-Activity-2-AD3345
# Logistic Regression – California Housing Price Classification

## 📌 Project Overview

This project implements a Logistic Regression classification model using Python and Scikit-learn to classify California houses into two categories: Low Price and High Price.

The California Housing dataset is used to understand how different housing features influence the classification of house prices.

Since Logistic Regression is a classification algorithm, the continuous median house value is converted into two categories using the median house value as the classification threshold.

## 🎯 Objectives

- Understand Logistic Regression.
- Perform Exploratory Data Analysis (EDA).
- Convert continuous values into categorical classes.
- Select independent and dependent variables.
- Split data into training and testing sets.
- Perform feature scaling using StandardScaler.
- Train a Logistic Regression model.
- Predict class labels and probabilities.
- Evaluate model performance.
- Analyze the confusion matrix and classification report.
- Predict the category of a new house.

## 🛠️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 📂 Dataset Information

**Dataset:** California Housing Dataset

The dataset contains information about housing in California.

### Input Features

| Feature | Description |
|---|---|
| MedInc | Median income |
| HouseAge | Median house age |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Block population |
| AveOccup | Average household occupancy |
| Latitude | Geographical latitude |
| Longitude | Geographical longitude |

### Target Variable

The original target variable is `MedHouseVal` (Median House Value).

It is converted into two categories:

- **0 – Low Price:** House value less than or equal to the median.
- **1 – High Price:** House value greater than the median.

## ⚙️ Project Workflow

1. Import required libraries.
2. Load the California Housing dataset.
3. Inspect dataset structure and statistics.
4. Perform Exploratory Data Analysis (EDA).
5. Convert continuous house values into binary categories.
6. Select independent variables (X) and dependent variable (y).
7. Split the dataset into training and testing sets.
8. Perform feature scaling using StandardScaler.
9. Train the Logistic Regression model.
10. Generate predictions.
11. Evaluate model accuracy.
12. Analyze the confusion matrix.
13. Generate the classification report.
14. Predict class probabilities.
15. Classify a new house example.

## 📊 Model Evaluation Metrics

The model is evaluated using:

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-Score:** Harmonic mean of precision and recall.
- **Confusion Matrix:** Compares actual and predicted classes.

## 📈 Visualizations

The project includes:

- Histograms for feature distributions.
- Correlation heatmap.
- Confusion matrix visualization.

## 🔍 Key Learnings

- Understanding Logistic Regression as a classification algorithm.
- Understanding the sigmoid function.
- Converting continuous values into categorical classes.
- Understanding binary classification.
- Performing feature scaling.
- Interpreting classification probabilities.
- Evaluating classification performance.
- Understanding precision, recall and F1-score.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the `.ipynb` notebook using Jupyter Notebook or Google Colab.
3. Install the required libraries if necessary.
4. Run all notebook cells sequentially.
5. Observe the predictions and evaluation results.

## 📁 Repository Structure

```text
logistic-regression/
│
├── logistic_regression.ipynb
└── README.md
```

## 👨‍💻 Author

**Rohit Thote**

B.Tech – Artificial Intelligence and Data Science

GitHub: [rohitthote](https://github.com/rohitthote)

**Faculty GitHub:** 
[https://github.com/complexiota]
