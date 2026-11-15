# 🌸 Multi-Class Benchmark Classification Pipeline

### DATHEON Machine Learning Internship – Task 1

## 📌 Project Overview

This project implements an end-to-end multiclass classification pipeline using the Iris flower dataset. It compares Logistic Regression and Decision Tree algorithms using Scikit-learn.

## 🎯 Objective

To build supervised machine learning models, perform feature scaling, evaluate classification performance, and visualize the results.

## 📊 Dataset Information

- Dataset: Iris Flower Dataset
- Original Records: 150
- Duplicate Records Removed: 1
- Final Records: 149
- Input Features: 4
- Target Variable: Species
- Classes: Setosa, Versicolor, Virginica

## 🛠️ Technologies Used

- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## ⚙️ Project Implementation

1. Dataset loading and inspection.
2. Exploratory Data Analysis (EDA).
3. Missing value and duplicate analysis.
4. Species distribution visualization.
5. Pairplot visualization.
6. Feature selection.
7. Train-test splitting (80/20).
8. Feature scaling using StandardScaler.
9. Logistic Regression classification.
10. Decision Tree classification.
11. Model evaluation using Accuracy, Precision, Recall and F1-score.
12. Confusion matrix heatmaps.
13. Model performance comparison.
14. Decision boundary visualization.

## 📈 Model Performance

Both models achieved 93.33% accuracy on the test dataset.

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 93.33% |
| Precision | 93.33% | 93.33% |
| Recall | 93.33% | 93.33% |
| F1-score | 93.33% | 93.33% |

## 📁 Project Structure

```text
datheon-task-1-iris-classification/
│
├── iris.csv
├── Datheon_Task1_Iris_Classification.ipynb
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open the Jupyter Notebook in VS Code.
4. Select the Python kernel.
5. Run all cells to reproduce the results.

## 🎓 Key Learnings

- Data preprocessing and exploratory data analysis.
- Feature scaling and data normalization.
- Supervised machine learning.
- Classification model training and evaluation.
- Data visualization and performance benchmarking.

## 📝 Conclusion

Both Logistic Regression and Decision Tree achieved 93.33% accuracy on the Iris test dataset.

This project provided practical experience in developing an end-to-end machine learning classification pipeline using Python and Scikit-learn.

## Internship

Completed as part of the DATHEON Machine Learning Internship.
