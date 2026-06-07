# 🏋️ Body Performance — Data Mining & Machine Learning

**Author:** Malek Jaafra & May Zariat  
**Program:** 2nd Year Big Data & Data Analytics  

---

## 📌 Project Overview

This project is a Machine Learning classification study based on real-world biometric data from the Body Performance dataset (Kaggle).

The goal is to predict a person's physical performance class (A, B, C, D) using body measurements and physical attributes.

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Clustering (Unsupervised Learning)
- Supervised Machine Learning models comparison

---

## 📊 Dataset

- Source: Kaggle — Body Performance Dataset  
- - Link: [Body Performance Dataset](https://www.kaggle.com/datasets/kukuroo3/body-performance-data) 

### Features:
- Age  
- Gender  
- Height / Weight  
- Body Fat %  
- Blood Pressure  
- Grip Force  
- Sit-ups count  
- Broad jump distance  

### Target:
- Performance Class (A → D)

---

## 🔧 Project Workflow

### 1. Data Preprocessing
- Handling missing values  
- Removing duplicates  
- Fixing inconsistent data  

### 2. Feature Engineering
- BMI calculation  
- Encoding categorical variables  

### 3. Exploratory Data Analysis (EDA)
- Statistical analysis (mean, variance, distribution)  
- Data visualization (histograms, boxplots, correlation matrix)  

### 4. Unsupervised Learning
- K-Means Clustering  
- Hierarchical Clustering (CAH)  

### 5. Supervised Learning Models
- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbors (KNN)  
- Random Forest  
- Gradient Boosting  

---

## 🤖 Model Performance

| Model | Accuracy |
|------|----------|
| Logistic Regression | ~0.60 |
| Decision Tree | ~0.60 |
| KNN (k=16) | ~0.61 |
| Random Forest | ~0.71 |
| Gradient Boosting | **~0.73 (Best Model)** |

---

## 🏆 Key Result

The Gradient Boosting model achieved the best performance with approximately **73% accuracy**, outperforming all other tested models.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📁 Project Structure
```
Body-Performance-Data-Mining/
│
├── projet_data_mining.ipynb
├── bodyPerformance.csv
└── README.md
```

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Feature selection optimization  
- Deep learning models  
- Deployment as a web application  

---

## 👩‍💻 Authors

- Malek Jaafra  
- May Zariat    
