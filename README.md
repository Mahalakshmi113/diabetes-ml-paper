# Prediction of Diabetes Using Machine Learning Models

This repository contains the research work and code for predicting diabetes using various machine learning algorithms on the **PIMA Indian Diabetes Dataset**.

## 📄 Files in this Repository
- `ML paper diabetes.pdf` — Full research paper describing the methodology, experiments, and results.
- `KNN v3.ipynb` — Jupyter Notebook implementing the models and analysis.

## 📌 Abstract
Diabetes is one of the most deadly health conditions affecting millions worldwide. Early detection can significantly reduce complications and save lives.  
This study evaluates the predictive capabilities of **K-Nearest Neighbors (KNN)**, **Decision Trees**, **Random Forests**, and **Logistic Regression** for diabetes diagnosis.  
The results reveal that **Logistic Regression achieves the highest accuracy at 88%**, demonstrating machine learning’s potential in proactive healthcare diagnostics.

## 📊 Dataset
- **Name**: PIMA Indian Diabetes Dataset  
- **Source**: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Description**: Contains medical data for female patients aged 21+ of Pima Indian heritage, including features like pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, pedigree function, and age.

## ⚙️ Methodology
The following models were implemented using **Scikit-Learn**:
1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Logistic Regression**

Minimal preprocessing was applied, including outlier removal using the Interquartile Range (IQR) method.

## 📈 Results
| Model                   | Accuracy |
|-------------------------|----------|
| KNN Classifier          | 81%      |
| Decision Tree Classifier| 81%      |
| Random Forest Classifier| 87%      |
| Logistic Regression     | 88%      |

**Best performing model**: Logistic Regression (88%)

## 🚀 Future Improvements
- Experiment with neural networks and deep learning approaches.
- Perform hyperparameter tuning for better accuracy.
- Apply feature engineering to create new informative features.

## 👩‍💻 Authors
- Ashwin N Hebbar  
- Shivam Sai Kiran  
- Mahalakshmi

---
📢 *This project demonstrates the usability of machine learning in healthcare, showing its potential to make diagnostics faster, cheaper, and more accessible.*
