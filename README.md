# 🧠 Employee Attrition Prediction using Machine Learning

This project aims to predict employee attrition (whether an employee will leave or stay) using machine learning models. The dataset includes demographic and job-related information.

## 📁 Dataset

The dataset used is `Employee.csv`, which contains features such as:

- Age
- Gender
- Education
- City
- Payment Tier
- Experience in Current Domain
- Whether the employee has been benched
- Joining Year
- Target column: `LeaveOrNot` (0 = Stay, 1 = Leave)

## 📊 Objectives

- Explore employee data through visualization
- Preprocess and transform categorical and numerical features
- Train and compare multiple machine learning classifiers
- Evaluate performance using accuracy, precision, recall, and F1-score

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- TQDM (for progress bars)

## 📈 Models Used

- Logistic Regression
- Gaussian Naive Bayes
- K-Nearest Neighbors
- SGD Classifier
- Linear SVC
- Perceptron
- Multi-layer Perceptron (Neural Network)

## 🧪 Model Evaluation

Each model is evaluated based on:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## 🧾 How to Run

1. Clone the repository
2. Ensure `Employee.csv` is placed inside a `data/` folder
3. Open the `notebook.ipynb` in Jupyter or VS Code
4. Run all cells to see EDA, training, and evaluation results

## 📌 Results

The notebook shows comparison results of various classifiers, helping identify which performs best at predicting employee attrition.

---

*This project is part of my data science portfolio to demonstrate classification, EDA, preprocessing, and model evaluation skills.*
