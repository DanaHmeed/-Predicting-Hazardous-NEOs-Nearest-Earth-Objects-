# 🚀 Predicting Hazardous Nearest Earth Objects (NEOs)
## Project Description:
A real-world dataset that tracks Nearest Earth Objects (NEOs)
observed by NASA from 1910 to 2024. The dataset contains 338,199 records, each representing
an object in space that has been monitored for its proximity to Earth. Some of these objects are
classified by NASA as "is_hazardous," indicating that they pose a potential danger to our plane
Your task is to train a machine learning model that can accurately predict whether a NEO is
hazardous or not. This is a critical task, as the ability to accurately identify dangerous objects
could be vital for planetary defense.

---

## 📊 Project Overview
This project aims to predict whether a given Nearest Earth Object (NEO) is hazardous or not, based on data provided by NASA from 1910 to 2024. The dataset contains 338,199 records, each representing an NEO and its proximity to Earth, with some labeled as hazardous. The goal is to build a machine learning model to classify hazardous NEOs.

---

## 🗂️ Dataset

- **Source**: NASA
- **Time Period**: 1910 to 2024
- **Number of Records**: 338,199
- **Target Variable**: `is_hazardous` (Binary: 1 = Hazardous, 0 = Non-Hazardous)

---

## 🔧 Steps and Methodology

1. **Data Cleaning**:
   - Handled missing values by imputing numerical features with the **median**.
   - Removed unnecessary columns like `name` and `neo_id`.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of features and target variables.
   - Analyzed correlations between different NEO attributes.
   - Addressed the class imbalance in the target variable.

3. **Data Preprocessing**:
   - Encoded categorical variables using **one-hot encoding**.
   - Scaled numerical features using **StandardScaler**.
   - Handled class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique).

4. **Model Training**:
   - Trained three machine learning models: 
     - **Random Forest Classifier**
     - **Logistic Regression**
     - **XGBoost Classifier**

5. **Model Evaluation**:
   - Evaluated models using **Precision**, **Recall**, **F1-Score**, and **AUC-ROC**.
   - Plotted the **ROC curve** to compare model performance.

---

## 📊 Key Findings and Insights

- **Class Imbalance**: The dataset had significantly more non-hazardous NEOs than hazardous ones, which was addressed by **SMOTE** to create a balanced dataset.
  
- **Best Performing Model**: 
  - The **Random Forest** classifier achieved the best results based on the **AUC-ROC** score.

- **Feature Importance**: 
  - Features such as **`absolute_magnitude`** and **`estimated_diameter_min`** were crucial in predicting whether an NEO is hazardous.

---
## ⚙️ How to Run the Code
 Clone the repository:
[(https://github.com/DanaHmeed/-Predicting-Hazardous-NEOs-Nearest-Earth-Objects-)]
