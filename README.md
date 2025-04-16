# Early Prediction of Diabetes Risk Using Machine Learning

## Overview
This project aims to improve early detection of diabetes by applying machine learning models to the CDC's 2015 Behavioral Risk Factor Surveillance System (BRFSS) dataset. By identifying key health indicators and socioeconomic factors, the model helps predict individuals at high risk of developing diabetes—enabling timely interventions, optimized treatment, and improved public health outcomes.

---

## Objectives
- Build predictive models to classify individuals based on their diabetes risk.
- Identify key features (e.g., BMI, blood pressure, cholesterol, general health) most correlated with diabetes.
- Use exploratory data analysis and visualizations to uncover patterns and trends.
- Evaluate and compare machine learning models based on classification metrics.
- Empower healthcare professionals with data-driven tools for early diagnosis.

---

## Methods
- **Data Source**: BRFSS 2015 dataset (253,680 rows, 22 variables)
- **Preprocessing**:
  - Removed 23,899 duplicate rows
  - Converted binary variables to numeric
  - Excluded non-contributing variables (e.g., income, alcohol consumption)
- **EDA**:
  - Analyzed diabetes distribution across variables like BMI, cholesterol, and blood pressure
  - Visualized key relationships (e.g., BMI vs Diabetes, General Health vs Diabetes)
- **Modeling**:
  - Algorithms used: Logistic Regression, Decision Tree, Quadratic Discriminant Analysis
  - Training/testing split applied
  - Evaluation metrics: Precision, Recall, F1-score

---

## Key Insights
- Logistic Regression outperformed other models with an **F1-score of 90.6%** for diabetes prediction.
- Top features influencing diabetes: **BMI**, **High Blood Pressure**, **Cholesterol**, and **General Health**.
- Data-driven visualizations highlight strong correlations between difficulty walking and diabetes occurrence.
- The cleaned dataset ensured zero missing values and high-quality predictions.

---

## Classification Metrics (for Class 2 - Diabetes)
| Model                | Precision | Recall  | F1 Score |
|---------------------|-----------|---------|----------|
| Logistic Regression | 0.844     | 0.979   | 0.906    |
| Decision Tree       | 0.871     | 0.832   | 0.851    |
| Quadratic Model     | 0.907     | 0.826   | 0.864    |

---

## Tools Used
- Python, Pandas, NumPy, Scikit-learn, Matplotlib
- Machine Learning (Logistic Regression, Decision Trees, QDA)
- Data Cleaning, Feature Engineering
- Exploratory Data Analysis (EDA)
- Cross-validation & Model Evaluation

---

## Dataset
- Source: [CDC BRFSS 2015](https://www.cdc.gov/brfss/annual_data/2015/pdf/codebook15_llcp.pdf)
- License: Public Domain (CDC)
- Format: CSV, 253K rows x 22 columns

---

## References
- [CDC BRFSS Dataset](https://www.cdc.gov/brfss/)
- [Related Research Paper](https://www.cdc.gov/pcd/issues/2019/19_0109.htm)

--
