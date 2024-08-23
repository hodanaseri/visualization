# Heart Disease UCI Dataset Visualization
## Overview
This project focuses on visualizing the Heart Disease UCI dataset to gain insights into the factors associated with heart disease. The dataset contains various features related to patients' health, such as age, sex, chest pain type, resting blood pressure, and cholesterol levels. The goal of this project is to explore the dataset through various visualizations to better understand the relationships between these features and the presence of heart disease.
## Dataset
The [Heart Disease UCI dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) contains 920 instances with 16 attributes (features). The attributes include demographic, clinical, and lifestyle information:
- **ID**
- **Age**: Age of the patient.
- **Sex**: Gender of the patient (1 = male, 0 = female).
- **Chest Pain Type (cp)**: Type of chest pain experienced (0-3).
- **Resting Blood Pressure (trestbps)**: Resting blood pressure in mm Hg.
- **Serum Cholesterol (chol)**: Serum cholesterol in mg/dl.
- **Fasting Blood Sugar (fbs)**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- **Resting ECG (restecg)**: Resting electrocardiographic results (0-2).
- **Max Heart Rate (thalach)**: Maximum heart rate achieved.
- **Exercise-Induced Angina (exang)**: Exercise-induced angina (1 = yes, 0 = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: The slope of the peak exercise ST segment (0-2).
- **Number of Major Vessels (ca)**: Number of major vessels (0-3) colored by fluoroscopy.
- **Thal**: Thalassemia (0 = normal, 1 = fixed defect, 2 = reversible defect).
- **Target**: Diagnosis of heart disease (0 = no, 1 = yes).
## Objectives
1. **Data Exploration**:
   - Summarizing the dataset to understand the distribution of features.
   - Identifying missing or inconsistent data points.
2. **Visualizations**:
   - Creating various plots to explore the relationships between features and the target variable.
   - Visualizing the distribution of each feature.
   - Analyzing correlations between features.
   - Identifying patterns and trends associated with the presence of heart disease.
###  Data Exploration and Cleaning
   - Loading the dataset.
   - Checking for missing values and handle them appropriately.
   - Summarizing the dataset using statistical methods.
###  Visualization
- **Distribution Plots**:
    - Plot histograms and boxplots for numerical features to examine their distributions.
    - Using bar plots for categorical features to observe class distributions.
- **Correlation Analysis**:
    - Creating a heatmap to visualize correlations between features.
    - Identifying highly correlated features and their impact on heart disease.
- **Pairwise Relationships**:
    - Using pair plots to explore relationships between multiple features simultaneously.
- **Feature vs. Target Plots**:
    - Using scatter plots, bar plots, and violin plots to examine the relationship between each feature and the target variable.
###  Analysis
- Document key findings from the visualizations.
- Identifying which features show the strongest relationships with the target variable.
- Discussing any potential implications for predicting heart disease.
