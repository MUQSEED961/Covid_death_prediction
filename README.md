# COVID-19 Death Prediction using Machine Learning & Power BI

## Project Overview
This project focuses on analyzing US county-level COVID-19 data and predicting the number of deaths using machine learning and deep learning models. The objective is to build an end-to-end data analytics solution that includes data preprocessing, model development, evaluation, and visualization through a Power BI dashboard.

---

## Dataset
- **Source:** New York Times COVID-19 dataset
- **Level:** US county-level
- **Key Columns:**
  - `date`
  - `county`
  - `state`
  - `fips`
  - `cases`
  - `deaths`

The dataset provides daily cumulative COVID-19 cases and deaths for each county in the United States.

---

## Problem Statement
To predict the number of COVID-19 deaths based on reported cases and time-based features, and to compare the performance of baseline and deep learning models.

---

## Objective
- **Target Variable:** `deaths`
- **Input Features:**
  - `cases`
  - Engineered time-based features extracted from `date` (year, month, day)

Identifiers such as `county`, `state`, and `fips` were excluded from modeling as they do not contribute predictive value.

---

## Data Preprocessing
The following preprocessing steps were performed:
- Checked and handled missing and empty values
- Converted the `date` column to datetime format
- Extracted time-based features from the date column
- Removed non-informative identifier columns
- Converted data types where required for modeling

---

## Models Used
- **Linear Regression**
  - Used as a baseline model to understand linear relationships
- **Multi-Layer Perceptron (MLP)**
  - Used to capture non-linear patterns in the data

---

## Evaluation Metrics
Since this is a regression problem, model performance was evaluated using:
- **RMSE (Root Mean Squared Error)**
- **R² Score**

---

## Results
- Linear Regression provided a baseline performance.
- The Multi-Layer Perceptron model improved prediction accuracy by capturing non-linear relationships.
- The final model achieved an **R² score of approximately 80%**.

---

## Power BI Dashboard
An interactive Power BI dashboard was created to visualize:
- Trends in COVID-19 cases and deaths
- Time-based patterns
- Analytical insights derived from the dataset

Dashboard screenshots are included in this repository.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab
- Power BI

---

## Key Learnings
- Importance of starting with a baseline model
- Feature engineering from time-based data
- Comparing traditional ML models with deep learning models
- Integrating machine learning results with business intelligence dashboards

---

## Conclusion
This project demonstrates an end-to-end data analytics and machine learning workflow, combining data preprocessing, predictive modeling, evaluation, and visualization to generate meaningful insights from real-world data.

---

## Author
**MUQSEED961**

