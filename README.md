# 🚀 Duplicate Question Detection

Welcome to the **Duplicate Question Detection** project! This repository contains the code, data, and methodologies employed to identify duplicate questions in question-and-answer platforms like Quora. The aim is to improve user experience, reduce redundancy, and optimize knowledge sharing using cutting-edge NLP and machine learning techniques.

---

## 📖 Overview

Duplicate question detection is crucial for platforms where users often ask similar questions. By accurately identifying these duplicates, we can save time, reduce redundant content, and provide immediate answers to users. This project achieves these goals through:

- **Text Preprocessing:** Tokenization, stopword removal, and lemmatization.
- **Feature Engineering:** Techniques like Bag-of-Words, TF-IDF, and word embeddings.
- **Machine Learning Models:** Logistic Regression, Random Forest, XGBoost, and an ensemble model for robust predictions.

---

## ✨ Features

- **NLP Pipeline:** Efficient preprocessing for clean and structured data.
- **Multiple Models:** Comparison of models to find the best performer.
- **Evaluation Metrics:** Precision, recall, F1 score, and confusion matrix visualizations.
- **Generalization:** Models tested on new samples for real-world applicability.

---

## 🛠️ Technologies Used

- **Programming Language:** Python 🐍
- **Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn
- **NLP Techniques:** TF-IDF, Word2Vec, and more
- **Machine Learning Models:** Random Forest, Logistic Regression, SVM, and XGBoost

---

## 📈 Results and Analysis  

The following table highlights the performance of various machine learning models used in this project. Metrics like accuracy and F1 score were evaluated to compare their efficiency in detecting duplicate questions.  

| **Model**              | **Accuracy** 📊 | **F1 Score** 🎯 | **Key Observations**                                   |
|------------------------|-----------------|-----------------|-------------------------------------------------------|
| **Logistic Regression** | 63.0%          | 46.8%           | Simple and interpretable but struggles with complexity. |
| **Random Forest**       | 🏆 **68.7%**   | 🏆 **67.8%**    | Best performer with strong handling of non-linear relationships. |
| **Support Vector Machine (SVM)** | 66.7%      | 48.9%           | Performs well but computationally intensive.          |
| **XGBoost**             | 63.0%          | 49.7%           | Efficient but needs more optimization for this dataset. |
| **Combined Model**      | 64.7%          | 63.7%           | Ensemble approach improves robustness but falls short of Random Forest. |

### 🔍 Key Insights  
- The **Random Forest model** demonstrated the highest accuracy and F1 score, showcasing its ability to capture complex patterns and generalize effectively.  
- Ensemble techniques, as used in the **Combined Model**, provided balanced performance but couldn't surpass Random Forest in this scenario.  
- Future optimization efforts could focus on **XGBoost** and deep learning approaches to enhance results further.  

### 📊 Visuals  
- Word cloud representations for duplicate and non-duplicate pairs.
- Confusion matrices for each model's predictions.
- Violin plots showing word overlap distributions. 

Explore the complete performance metrics and visualizations in the `Results` folder.  
