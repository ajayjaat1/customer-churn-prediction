# 📊 Customer Churn Prediction using Machine Learning

## 🚀 Project Overview
Customer churn is a critical problem in the telecom industry, where companies aim to identify customers who are likely to leave their service.

This project builds a **machine learning-based churn prediction system** using the Telecom Churn Dataset. It not only predicts whether a customer will churn but also introduces a novel feature called **Customer Interaction Score (CIS)** to enhance prediction accuracy and interpretability.

---

## 🌟 Key Highlight: Customer Interaction Score (CIS)

To improve model performance, we introduced a **novel feature**:

### 💡 Customer Interaction Score (CIS)

CIS is a **composite metric** that captures overall customer engagement by combining:

- Day call minutes  
- Evening call minutes  
- Night call minutes  
- International call minutes  
- Customer service calls  

### ⚙️ How it Works
- All features are **normalized** to a common scale
- Usage metrics contribute positively
- Customer service calls (complaints) reduce the score

### 🎯 Purpose
- Identify **low-engagement users**
- Detect potential churners early
- Provide a **single interpretable metric** for behavior

---

## 📂 Dataset

- Telecom Churn Dataset (Kaggle)
- Contains customer information such as:
  - Usage behavior (calls, minutes, charges)
  - Account details
  - Customer service interactions
  - Churn label (target variable)

---

## 🔍 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Understanding feature distributions
- Identifying important variables
- Detecting patterns related to churn

---

### 2️⃣ Data Preprocessing
- Handling categorical variables
- Feature selection (removing irrelevant columns)
- Feature scaling (normalization)
- Creation of **Customer Interaction Score (CIS)**

---

### 3️⃣ Model Building

Multiple machine learning models were implemented and compared:

- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- LightGBM
- XGBoost
- AdaBoost
- Gradient Boosting
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Multi-layer Perceptron (Neural Network)
- Bagging Classifier
- Gaussian Process Classifier

---

### 4️⃣ Model Evaluation

Models were evaluated using:

- ✅ Accuracy Score  
- 📊 Confusion Matrix  
- 📈 Classification Report (Precision, Recall, F1-score)

---

## 📊 Results & Insights

- Tree-based models like **Random Forest, XGBoost, and Gradient Boosting** performed best.
- Customers with:
  - High customer service calls  
  - Low usage activity are more likely to churn.

- The **CIS feature improved model understanding** by capturing overall engagement in a single metric.

---

## 🧠 Key Learnings

- Importance of **feature engineering**
- Comparing multiple ML models improves reliability
- Combining features (like CIS) can reveal hidden patterns
- Customer behavior is better understood through **aggregated metrics**

---

## 🛠️ Tech Stack

- **Programming Language:** Python 
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn  
