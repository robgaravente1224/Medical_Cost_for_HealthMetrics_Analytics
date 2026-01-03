# Medical Cost Analysis Portfolio Project

## Executive Summary
This repository showcases an end-to-end data analysis project on medical insurance costs for a fictional company, HealthMetrics Analytics. The project's primary objective was to identify the key factors driving medical expenses and build a robust predictive model to forecast future costs.

Through a professional, multi-stage workflow, I have demonstrated my ability to:

Engineer a clean, usable dataset from raw, unstructured data using SQL.

Uncover critical business insights through in-depth Exploratory Data Analysis (EDA).

Build and evaluate a high-performing predictive model to inform strategic decision-making.

My central finding is that smoking status is the single most powerful predictor of high medical costs, with smokers incurring charges over three times higher than non-smokers. The predictive model I developed can forecast medical costs with 88% accuracy, providing a valuable tool for risk assessment and resource planning.

## The Business Challenge
As an analyst for HealthMetrics Analytics, I was tasked with a critical business problem: to understand the factors driving medical claims and develop a predictive tool to improve underwriting and risk management. This project addresses the challenge of transforming complex, raw data into actionable intelligence.

## Data & Methodology
I executed a comprehensive, three-part methodology:

## 1. Data Engineering & Workflow
I began with a raw dataset, medical_costs.csv, and developed a professional data engineering workflow using SQL to transform it into a structured, analytical-ready dataset. This process is fully documented and auditable.

Key Engineering Steps: I created business-relevant features like age_group and combined_health_status, and engineered smoker_binary and log_charges to prepare the data for modeling.

Reproducibility: The entire process is captured in my public SQL Fiddle, demonstrating a professional and reproducible approach to data handling.

## 2. Exploratory Data Analysis (EDA)
My EDA focused on uncovering the key drivers of medical costs through visualization and statistical testing.

Core Finding: I confirmed that smoking status is the dominant factor in medical costs. A statistical t-test validated that the difference in costs between smokers ($32,000) and non-smokers ($8,400) is highly significant.

Additional Insights: The analysis also identified a positive correlation between costs and both age and bmi, while highlighting regional cost variances.

## 3. Predictive Modeling
I built a series of models to forecast medical charges, showcasing my ability to select the right tools for the job.

Baseline Model: I started with a linear regression model that achieved an R-squared of 0.75, providing a strong foundation for the analysis.

Advanced Models: I then developed more sophisticated models, including Random Forest and XGBoost, which significantly improved performance, achieving an R-squared of 0.88.

Model Validation: The feature importance analysis from the Random Forest model reinforced my central finding by ranking smoker_binary as the most influential predictor.

## 4. Strategic Recommendations

Based on the predictive power of the model and the results of the Exploratory Data Analysis, I have identified three key strategic recommendations for HealthMetrics Analytics to optimize risk management and reduce claim liabilities:

A. Implement Targeted Wellness Incentives: Since smoking status is the primary driver of costs—with smokers incurring over 300% higher charges than non-smokers—the company should offer subsidized smoking cessation programs. A 10% reduction in the smoking population could lead to a significant decrease in total annual payouts.

B. Refine Premium Tiering for High-BMI Cohorts: The analysis reveals a compounding effect where high BMI significantly amplifies costs, particularly in the smoking demographic. Transitioning to a tiered pricing model that incorporates "Healthy Lifestyle" discounts for policyholders maintaining BMI and activity targets could improve the risk pool's overall health profile.

C. Data-Driven Financial Forecasting: The high accuracy of the Random Forest and XGBoost models allows the underwriting team to move away from historical averages. By applying this model to new applicants, HealthMetrics Analytics can more accurately forecast future claims, ensuring capital reserves are optimized and premiums are competitively yet safely priced.

## Repository Contents
README.md: Project overview and summary.

Notebooks: Contains the Jupyter notebooks for EDA and predictive modeling.

Data: Includes the raw medical_costs.csv and the engineered medical_costs_for_insurance.csv datasets.

Presentation: A PDF version of the project presentation.

## Links
* [**Medical Personal Costs Dataset on Kaggle**](https://www.kaggle.com/datasets/mirichoi0218/insurance)
* [**SQL Workflow on DB Fiddle**](https://www.db-fiddle.com/f/nb6pePvo4zH7tUaLi9aEYB/0)
* [**EDA Notebook**](https://colab.research.google.com/drive/1e2GU8vQhvM7-qOJjWaGIGlypI_fG2_T_#scrollTo=8MUlAw8aIBYc)
* [**Predictive Modeling Notebook**](https://colab.research.google.com/drive/1eJuYwVs19c4y0B8VIs5xQ7T258kTuUpg#scrollTo=CFelhxz_AqR0)
