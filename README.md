# Task 1: Data Cleaning & Preprocessing – Titanic Dataset

## 🧠 Objective
Clean and prepare raw data for machine learning.

## 📁 Dataset
- Source: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-dataset.csv`

## ✅ Preprocessing Steps
1. **Missing Values**
   - `Age`: Filled with median
   - `Embarked`: Filled with most frequent value
   - `Cabin`: Dropped (too many missing values)

2. **Encoding**
   - `Sex`: Label encoded (`male`=1, `female`=0)
   - `Embarked`: One-hot encoded

3. **Feature Scaling**
   - Standardized `Age`, `Fare`, `Pclass`, `SibSp`, `Parch` using `StandardScaler`

4. **Outlier Handling**
   - Removed outliers in `Fare` using IQR method

## 📦 Output
- `titanic_cleaned.csv`: Final preprocessed dataset
- `titanic_preprocessing.ipynb`: Code notebook

## 💡 Tools Used
- Python, Pandas, NumPy
- Seaborn & Matplotlib for visualizations
- Scikit-learn for encoding & scaling
