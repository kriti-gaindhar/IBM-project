# Heart Disease Prediction Using Machine Learning

# About the Project

This project focuses on analyzing heart disease data and implementing different Machine Learning algorithms to predict the possibility of heart disease.

The project explores both **Supervised and Unsupervised Machine Learning algorithms** using a Heart Disease dataset. Different models are implemented, evaluated, and compared to understand their performance and effectiveness.

The primary objective is to identify the most suitable algorithm for heart disease prediction based on evaluation metrics such as Accuracy and F1-Score.

# Project Objectives

- Understand the fundamentals of Machine Learning.
- Implement multiple supervised and unsupervised algorithms.
- Analyze and preprocess the Heart Disease dataset.
- Train and evaluate different machine learning models.
- Compare algorithm performance using evaluation metrics.
- Identify the best-performing model for heart disease prediction.

# Team Members

| Diya Verma | 250439 |
| Dishika Srivastav | 250438 |
| Kriti Gaindhar | 250446 |
| Prisha Chaturvedi | 250453 |

* Batch: C – 2nd Year  
* Course: IBM Machine Learning  
* Submitted To: Mr. Aayush Chand

# Machine Learning Algorithms Implemented

# 1. Supervised Learning

Supervised algorithms learn from labelled data to make predictions.

- **Linear Regression:** Predicts continuous numerical values and is also evaluated using a 0.5 threshold for binary classification.
- **K-Nearest Neighbours (KNN):** Classifies records based on the majority class of their nearest neighbours.
- **Decision Tree:** Uses decision-based rules to classify patient records.
- **Random Forest:** Combines multiple decision trees to improve prediction performance and reduce overfitting.

# 2. Unsupervised Learning

Unsupervised algorithms identify patterns and similarities in data without using labelled outputs during training.

- **Hierarchical Clustering:** Groups similar patient records using an agglomerative clustering approach.
- **K-Means Clustering:** Divides patient records into clusters based on feature similarity.

#  Model Performance Comparison

The following results were obtained from the supervised learning models:

| Algorithm | Accuracy | F1-Score |

| Linear Regression | 78.69% | 82.19% |
| KNN | 81.97% | 84.93% |
| Decision Tree | 81.97% | 84.93% |
| **Random Forest** | **83.61%** | **85.71%** |

# Best Performing Algorithm: Random Forest

Random Forest achieved the highest accuracy of **83.61%** and an F1-Score of **85.71%** among the evaluated supervised models.

It was selected as the best-performing model because:

- It combines predictions from multiple decision trees.
- It can capture complex relationships between features.
- It reduces the risk of overfitting compared with a single decision tree.
- It provides feature importance for understanding influential variables.

*Note: Unsupervised algorithms are evaluated separately using metrics such as Adjusted Rand Index (ARI) and Silhouette Score rather than classification accuracy and F1-Score.*

# Technologies & Libraries Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, SciPy
- **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook / Google Colab
- **Version Control:** Git and GitHub
- 

# Installation & Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/kriti-gaindhar/IBM-project.git
```

### Step 2: Navigate to the Project Directory

```bash
cd IBM-project
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib scipy scikit-learn jupyter
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open `final project.ipynb` and execute the cells sequentially.

Make sure `heart.csv` is present in the same directory as the notebook.

# Conclusion

This project demonstrates how different Machine Learning algorithms can be applied to healthcare-related datasets.

Through implementation and comparative analysis, Random Forest achieved the best performance among the supervised algorithms, followed by KNN and Decision Tree.

The unsupervised algorithms, K-Means and Hierarchical Clustering, were explored to identify patterns and similarities among patient records.

Overall, this project provided practical experience in data preprocessing, model training, hyperparameter tuning, clustering, evaluation, and comparative analysis.

# Disclaimer

This project is developed for educational and academic purposes only. Its predictions should not be considered a substitute for professional medical advice, diagnosis, or treatment.

---

**Developed as part of the IBM Machine Learning Project | 2nd Year – Batch C**

⭐ If you find this project interesting, consider giving this repository a star!
