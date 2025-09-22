# 🧹 AI & ML Internship – Task 1

## 📌 Task: Data Cleaning & Preprocessing
The objective of this task is to learn how to clean and prepare raw data for Machine Learning using the Titanic dataset.

### ✅ Steps Performed
1. **Imported Dataset**  
   - Loaded Titanic dataset using Pandas.  
   - Explored dataset shape, info, and missing values.  

2. **Handled Missing Values**  
   - Replaced missing `Age` values with median.  
   - Filled missing `Embarked` values with mode.  
   - Dropped `Cabin` column (too many nulls).  

3. **Encoded Categorical Features**  
   - Converted `Sex` into numerical (male=0, female=1).  
   - Applied One-Hot Encoding for `Embarked`.  

4. **Feature Scaling**  
   - Standardized `Age` and `Fare` using StandardScaler.  

5. **Outlier Detection & Removal**  
   - Visualized outliers using boxplots.  
   - Removed outliers in `Fare` using the IQR method.  

---

## 📊 Final Dataset
- Dataset shape reduced after removing outliers.  
- Cleaned, encoded, and ready for ML model training.  

---

## ❓ Interview Questions (from task PDF)
1. What are the different types of missing data?  
2. How do you handle categorical variables?  
3. What is the difference between normalization and standardization?  
4. How do you detect outliers?  
5. Why is preprocessing important in ML?  
6. What is one-hot encoding vs label encoding?  
7. How do you handle data imbalance?  
8. Can preprocessing affect model accuracy?  

---

## 📁 Files in Repo
- `Task1.ipynb` → Jupyter Notebook with full preprocessing code.  
- `README.md` → This documentation file.  

---

## 🔗 Dataset Link
[Titanic Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## ✨ Author
**Balaji** – AI & ML Internship Participant  
