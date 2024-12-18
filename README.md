# Data Science Project: Comprehensive Workflow and Predictive Modeling

## Objective
This project applies a complete data science workflow to a synthetic dataset, focusing on predicting death outcomes. It includes data exploration, preparation, feature engineering, and predictive modeling.

---

## Workflow Overview

### Part 1: Data Preparation and Exploration
1. **Exploratory Data Analysis (EDA)**:
   - **Files**:
     - `EDA - Matan Shemesh.html`
   - **Tasks**:
     - Visualize distributions and relationships between features.
     - Identify potential issues like missing values or outliers.
   - **Deliverables**: Summary insights and visualizations (`countplots.pdf`).

2. **Missing Values Treatment**:
   - **File**: `Missing values - Matan Shemesh.html`
   - **Tasks**:
     - Analyze missing data patterns.
     - Apply appropriate imputation or removal strategies.
   - **Output**: `df_after_missing_values_treatment.csv`

3. **Outlier Treatment**:
   - **File**: `Outliers treatment - Matan Shemesh.html`
   - **Tasks**:
     - Detect outliers using statistical methods (e.g., IQR, Z-scores).
     - Address anomalies based on their impact on the dataset.
   - **Output**: `df_removed_outliers.csv`

4. **EDA Recheck**:
   - **File**: `EDA recheck - Matan Shemesh.html`
   - **Tasks**:
     - Re-evaluate data after treating missing values and outliers.
     - Confirm data readiness for further processing.

5. **Feature Enrichment**:
   - **File**: `Feature Enrichment - Matan Shemesh.html`
   - **Tasks**:
     - Generate new features to enhance predictive power.
   - **Output**: `df_after_Feature_Enrichment.csv`

6. **Feature Selection**:
   - **File**: `Feature selection - Matan Shemesh.html`
   - **Tasks**:
     - Select features most relevant for modeling.
   - **Output**: `DF_FINAL.csv`

### Part 2: Predictive Modeling
 **Model Development**:
   - **File**: `Task 2 - Application of predictive models.html`
   - **Tasks**:
     - Apply machine learning models to the prepared dataset (`DF_FINAL.csv`).
     - Evaluate model performance using metrics like accuracy, precision, recall, etc.
![evaluations](https://github.com/user-attachments/assets/aacd99a8-6ea8-401f-9767-978594f68483)

---

## Dataset
- **Source**: Synthetic dataset provided for analysis.
- **File**: `death_prediction_synthetic.csv`
- **Description**: 
  - Contains demographic and clinical features for predictive modeling.

---

## Deliverables
1. Intermediate datasets for each processing stage:
   - `df_after_missing_values_treatment.csv`
   - `df_removed_outliers.csv`
   - `df_after_Feature_Enrichment.csv`
   - `DF_FINAL.csv`
2. Final predictive modeling report.
3. Documentation with code explanations and rationales for decisions.

---

## Tools and Libraries
- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Tools**: Jupyter Notebook, HTML for report generation

---

## Acknowledgments
This is a final project of "Data Science Introduction" course.
