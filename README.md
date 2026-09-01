# Telecom Customer Churn Prediction & Tiered Retention Strategy

## Overview

This repository contains the final assignment for GCI World 2026 Spring, focusing on developing a comprehensive predictive model for customer churn and designing a tiered retention strategy for Company A, a major wireless telecommunications provider.

The primary objective is to analyze customer data (approximately 100,000 subscribers) to predict churn probability and formulate actionable, tailored retention protocols that differentiate between high-value and budget customers. This approach is designed to maximize revenue protection while minimizing intervention costs.

## Project Deliverables
*   **[View Full Analysis Notebook](./telecom_churn_analysis.ipynb)**: The core Jupyter Notebook containing all data preprocessing, EDA, model training, and evaluation.
*   **[View Presentation Slides](./Telecom_Churn_Presentation.pdf)**: A comprehensive deck detailing our methodology, business implications, and strategic recommendations.
*   **[View Completion Certificate](./Certificate.pdf)**: Certification of completion for the GCI World 2026 Spring program.

## Business Context

The global telecommunications market is highly saturated, with mobile penetration exceeding 100% in most regions. Growth relies heavily on capturing competitor market share or increasing Average Revenue Per User (ARPU). Furthermore, the cost of acquiring a new subscriber is significantly higher (5-25x) than retaining an existing one. For a wireless operator, losing even a small percentage of customers annually translates to millions in lost recurring revenue.

Our solution addresses this by shifting the paradigm from reactive retention (post-cancellation offers) to proactive intervention, identifying behavioral signals that precede churn.

## Methodology

The analysis follows a robust end-to-end data science lifecycle:

1. **Exploratory Data Analysis (EDA)**: Uncovering underlying patterns and identifying key drivers of customer attrition.
2. **Feature Engineering**: Transforming raw demographic, geographic, and usage data into 24 distinct predictive signals.
3. **Predictive Modeling**: Training and comparing multiple machine learning architectures, including Logistic Regression, Random Forest, and XGBoost, to achieve optimal classification performance.
4. **Customer Segmentation**: Stratifying the subscriber base into distinct value tiers: VIP, Standard, and Budget.
5. **Tiered Retention Strategy**: Designing personalized, cost-effective intervention frameworks tailored to each specific customer segment, backed by rigorous ROI analysis.
6. **Acquisition Strategy**: Formulating complementary strategies to attract new customers and stimulate baseline growth.

## Data Architecture

The analysis leverages a comprehensive dataset composed of client profiles and historical usage records. 

*   `Client Data`: 100,000 instances, 50 features.
*   `Record Data`: 100,000 instances, 51 features.
*   **Combined Feature Space**: 100,000 instances across 100 aggregated features.

*(Note: Data files are kept locally or referenced via remote storage due to size constraints.)*

## Repository Structure

*   `telecom_churn_analysis.ipynb`: The primary Jupyter Notebook containing data preprocessing, exploratory analysis, model training, and strategic evaluations.
*   `data/`: Contains the raw datasets (Client profiles and Historical records).
*   `docs/`: Contains the original dataset overview document.
*   `notebooks/`: Contains supplementary and tutorial notebooks.
*   `Telecom_Churn_Presentation.pdf`: The presentation slides detailing methodology, business implications, and strategic recommendations.
*   `Certificate.pdf`: Certification of completion for the GCI World 2026 Spring program.

## Setup and Installation

To replicate the environment and execute the notebook:

1. Clone this repository to your local machine.
2. Ensure you have Python 3.10+ installed.
3. Install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

4. Launch Jupyter Notebook or Jupyter Lab to interact with the analysis.

## Acknowledgments

Developed as the Final Assignment for GCI World 2026 Spring. 
