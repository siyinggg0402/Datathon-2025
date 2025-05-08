# NUS SDS Datathon 2025  
**Machine Learning Classification of Companies: Prediction of Domestic and Global Markets**

This project was developed as part of the NUS Students' Data Science Society (SDS) Datathon 2025, a 6-day intensive data science challenge. The objective was to explore real-world datasets and apply machine learning techniques to classify companies into either domestic or global markets based on their attributes.

---

## 📊 Project Overview

The dataset provided contained company-related data such as number of employees, sales, and industry types. The goal was to build a predictive model that accurately classifies companies as either **domestically** or **globally operated**. We evaluated the significance of different features and experimented with various machine learning models to identify the best performer.

---

## 🧹 Data Cleaning

- Identified and removed null values and duplicated rows.
- Inspected outliers to prevent skewed results.
- Dropped irrelevant or sparsely populated features.
- Analyzed relationships between independent and dependent variables to assess feature significance.

---

## 🔧 Data Preprocessing

- Split data into training and testing sets.
- Scaled numerical features and encoded categorical variables.
- Checked for class imbalance in the target variable and took steps to address it if needed.

---

## 🤖 Machine Learning Techniques

- Explored Random Forest, Decision Tree, and Multi-Layer Perceptron models.
- Random Forest yielded the highest accuracy and precision:
  - **87% accuracy** for "Is Domestic Ultimate"
  - **91% accuracy** for "Is Global Ultimate"
- Model performance was evaluated using:
  - ROC Curve
  - Confusion Matrix
  - Recall, Precision, and Accuracy scores

---

## 💡 Key Insights

- **Feature Importance**:
  - For predicting **Domestic** companies: "Industry" type was most influential.
  - For **Global** companies: Number of **global employees** played a major role.

---

## ⚙️ Setup Instructions

### 1. Prerequisites

- Python 3.8+ → [Download here](https://www.python.org/downloads/)
- `pip` (comes with Python)
- `virtualenv` (optional, for isolated environments)

Check versions:
```bash
python --version
pip --version
```


Thanks to NUS Statistics and Data Science Society for organising this datathon, as well as my teammates Amelia Lon Hwee Min and Vivien Chin for working together in this project. 

