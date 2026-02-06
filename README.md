# 🧠 SmartObesity: Lifestyle-Based Obesity Level Prediction using Machine Learning

Machine Learning project to predict obesity levels based on lifestyle habits, eating patterns, and physical condition data.

This project applies data preprocessing, feature engineering, and multiple classification models to analyze and predict obesity categories.

---

## 📌 Background

Obesity is a major global health issue influenced by lifestyle, diet, physical activity, and daily habits.  
By leveraging machine learning, we can identify patterns and predict obesity levels early to support preventive health actions.

---

## 🎯 Objectives

- Analyze lifestyle and health-related data
- Build a machine learning model to predict obesity levels
- Compare multiple algorithms
- Evaluate model performance using classification metrics

---

## 📊 Dataset Information

Dataset contains lifestyle, eating habits, and health indicators such as:

- Age, Gender
- Height, Weight
- Eating habits (FAVC, FCVC, NCP, CAEC)
- Water intake (CH2O)
- Smoking habit
- Physical activity (FAF)
- Screen time (TUE)
- Transportation mode (MTRANS)
- Family history with overweight
- Target label: **NObeyesdad (Obesity level category)**

Total data: 2111 records

---

## 🛠️ Tech Stack

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

---

## 🔄 Machine Learning Workflow

### 1. Data Understanding
- Data inspection
- Descriptive statistics
- Checking missing values & duplicates

### 2. Data Cleaning
- Remove duplicated records

### 3. Feature Engineering & Preprocessing
- Ordinal encoding
- One-hot encoding
- Standard scaling
- Min-max scaling
- Log transformation
- ColumnTransformer pipeline

### 4. Data Splitting
- Train-test split (80:20)

### 5. Modeling
Models used:
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

### 6. Evaluation
- Accuracy
- F1-score
- Recall
- Cross-validation
- Confusion Matrix

---

## 📈 Model Performance

Model performance evaluated using cross-validation and classification metrics.

Metrics used:
- Accuracy
- F1 Macro
- Recall Macro

Visualization:
- Confusion Matrix


---

## 💡 Insights

- Lifestyle habits significantly influence obesity level
- Physical activity and eating behavior are strong predictors
- Machine learning can effectively classify obesity categories

---

## 👤 Author

Muhammad Rizcy  
Information Systems Student 

