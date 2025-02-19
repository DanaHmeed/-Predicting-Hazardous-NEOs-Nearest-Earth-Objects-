# Predicting Hazardous Nearest Earth Objects (NEOs)
## Project Description:
In this project, you will work with a real-world dataset that tracks Nearest Earth Objects (NEOs)
observed by NASA from 1910 to 2024. The dataset contains 338,199 records, each representing
an object in space that has been monitored for its proximity to Earth. Some of these objects are
classified by NASA as "is_hazardous," indicating that they pose a potential danger to our plane
Your task is to train a machine learning model that can accurately predict whether a NEO is
hazardous or not. This is a critical task, as the ability to accurately identify dangerous objects
could be vital for planetary defense.
## Project Overview
This project aims to predict whether a given Nearest Earth Object (NEO) is hazardous or not, based on data provided by NASA from 1910 to 2024. The dataset contains 338,199 records, each representing an NEO and its proximity to Earth, with some labeled as hazardous. The goal is to build a machine learning model to classify hazardous NEOs.

## Dataset
- **Data Source**: NASA
- **Time Period**: 1910 to 2024
- **Number of Records**: 338,199
- **Target Variable**: `is_hazardous` (Binary: 1 = Hazardous, 0 = Non-Hazardous)

## Steps and Methodology
1. **Data Cleaning**: 
   - Handling missing values (imputation with median for numerical features).
   - Dropping unnecessary columns (e.g., `name` and `neo_id`).
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing data distributions and correlations.
   - Analyzing class imbalance in the target variable.

3. **Preprocessing**:
   - Encoding categorical variables using one-hot encoding.
   - Scaling numerical features using StandardScaler.
   - Handling class imbalance with SMOTE (Synthetic Minority Over-sampling Technique).

4. **Model Training**:
   - Trained multiple machine learning models: Random Forest, Logistic Regression, and XGBoost.
   - Evaluated model performance using Precision, Recall, F1-Score, and AUC-ROC.

5. **Model Evaluation**:
   - Compared models based on evaluation metrics and selected the best-performing model.
   - Plotted ROC curves for visual performance comparison.

## Key Findings and Insights
- **Class Imbalance**: The dataset contains significantly more non-hazardous NEOs than hazardous ones, addressed using SMOTE.
- **Best Performing Model**: [Model name] based on AUC-ROC score of [score].
- **Feature Importance**: [Highlight any key features that were found to be important for classification].

## How to Run the Code
1. Clone the repository:
   ```bash
[(https://github.com/DanaHmeed/-Predicting-Hazardous-NEOs-Nearest-Earth-Objects-)]
