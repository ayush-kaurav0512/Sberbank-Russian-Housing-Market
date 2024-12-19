# Sberbank Russian Housing Market Prediction

## Description

Housing costs are a major financial commitment for both individuals and developers. To mitigate uncertainty in budgeting, Sberbank, Russia’s largest and oldest bank, aims to improve real estate price prediction. This enables renters, developers, and lenders to make more informed decisions when purchasing or leasing properties.

While the Russian housing market is relatively stable, the country’s volatile economic landscape adds complexity to forecasting property prices. Pricing predictions require accounting for interactions between housing characteristics such as location and size, combined with macroeconomic conditions. Simple regression models are insufficient to capture these intricate dynamics.

In this project, we develop advanced algorithms to predict property sale prices using a rich dataset provided by Sberbank. Accurate predictions will empower Sberbank to provide reliable pricing guidance to their customers, reducing uncertainty in an unpredictable economy.

---

## Objective

The primary goal of this project is to predict the **sale price** (`price_doc`) of properties in Russia, leveraging housing and macroeconomic data to build a robust forecasting model.

---

## Evaluation Metric

The submissions are evaluated based on the **Root Mean Squared Logarithmic Error (RMSLE)** between the predicted and actual property sale prices. RMSLE ensures a focus on proportional differences, favoring accuracy in smaller values while tolerating larger deviations in high-value predictions.

---

## Dataset Description

The dataset includes detailed housing data combined with macroeconomic patterns, enabling competitors to predict property prices effectively.

### Data Files:
1. **`train.csv`**: Includes transaction details for properties from August 2011 to June 2015, with the target variable (`price_doc`) representing sale prices.
2. **`test.csv`**: Contains transaction data for properties from July 2015 to May 2016, excluding the target variable.
3. **`macro.csv`**: Provides economic and financial indicators for Russia, linked to the `train.csv` and `test.csv` datasets via the `timestamp` column.
4. **`sample_submission.csv`**: A template file outlining the required submission format.
5. **`data_dictionary.txt`**: Explains the fields available in the other data files.

---

## Workflow

1. **Exploratory Data Analysis (EDA)**: 
   - Analyze property characteristics and macroeconomic trends.
   - Identify missing values, outliers, and patterns.
   
2. **Data Preprocessing**:
   - Handle missing data and outliers.
   - Normalize numerical features and encode categorical variables.

3. **Feature Engineering**:
   - Create meaningful features from housing attributes and economic indicators.
   - Investigate temporal trends in housing prices.

4. **Model Development**:
   - Experiment with advanced models (e.g., Gradient Boosting, XGBoost, and LightGBM).
   - Fine-tune hyperparameters to optimize performance.

5. **Evaluation**:
   - Measure model performance using RMSLE.
   - Validate predictions against unseen data.

6. **Deployment**:
   - Provide an actionable, scalable solution for predicting property prices.

---

## Key Insights in Report

The accompanying Excel report includes:
- Detailed exploratory analysis of housing and macroeconomic data.
- Correlation analysis between features and property prices.
- Model comparison metrics and insights.
- Recommendations for improving prediction accuracy and scalability.

---

## Kaggle Competition

This project originates from the Kaggle competition **[Sberbank Russian Housing Market](https://www.kaggle.com/c/sberbank-russian-housing-market/overview)**. It offers an opportunity to apply advanced predictive modeling techniques to solve a real-world business challenge.

## Video Report Exaplanation 
https://asu.zoom.us/rec/share/217OHNbe-jU_i2RZZG5GQ6czpuQQqMYJ1WnamJxMACRARufYaMKWYUxZkIQxc-Bq.dzS4goNImCTTFSkd?startTime=1732663245000

Passcode: H@hj=#7K
