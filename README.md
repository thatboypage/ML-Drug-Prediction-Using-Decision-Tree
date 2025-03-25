# 🧪 ML-Drug-Prediction-Using-Decision-Tree

## 📌 Project Description

This project aims to develop a **multi-class classification model** that predicts the most suitable drug for a patient based on their health attributes. Using features like **Age**, **Sex**, **Blood Pressure**, and **Cholesterol**, the model suggests one of five drugs: **Drug A, Drug B, Drug C, Drug X**, or **Drug Y**.

The model is built using a **Decision Tree Classifier**, trained on patient data to recommend a potential treatment plan for future patients.


## 🔍 Insights & Workflow

### 📥 Step 1: Data Loading
- Loaded patient data from `drug200.csv`.
- Initial exploration to understand structure and key features.

### 🧹 Step 2: Data Preprocessing
- Handled categorical features (e.g., converting 'Sex', 'BP', 'Cholesterol' to numerical labels).
- Checked for missing values and data consistency.

### 📊 Step 3: Exploratory Data Analysis (EDA)
- Visualized feature distributions using Seaborn and Matplotlib.
- Investigated correlations and class distributions.

### 🌳 Step 4: Model Building
- Built a **Decision Tree Classifier** using scikit-learn.
- Trained the model with features: Age, Sex, BP, and Cholesterol.
- Target variable: Drug type.

### 📈 Step 5: Evaluation
- Evaluated model using accuracy and confusion matrix.
- Achieved strong classification performance across multiple drug types.


## 📉 Sample Output

Confusion Matrix showing predicted vs actual drug labels:
![Confusion Matrix](image.png)


## 💡 Key Takeaways

- Decision Trees are effective for multi-class classification in medical datasets.
- Feature encoding is critical when dealing with categorical data.
- Visualizations aid in understanding feature impact on model predictions.


## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
