# Udacity Data Science Project

This repository contains my projecta for the Udacity Data Science Nanodegree. The goal of this project is to apply the CRISP-DM process to analyze a real-world dataset and build a predictive model.

## Project Overview

In this project, I explored data from the Centers for Medicare & Medicaid Services (CMS) to analyze patterns related to chronic condition prevalence across the United States. I performed data cleaning, exploratory data analysis, and used machine learning to predict condition-related metrics.

## CRISP-DM Process

1. **Business Understanding**  
   Identify the key questions the data can help answer — in this case, how chronic conditions vary by region and what factors might predict their prevalence.

2. **Data Understanding**  
   CMS public datasets were used, including demographic, cost, and chronic condition indicators.

3. **Data Preparation**  
   Data was cleaned, merged, and transformed using Python (pandas, numpy).

4. **Modeling**  
   Several classification models were tested including Logistic Regression, Random Forest, and Gradient Boosting. Metrics such as accuracy, precision, recall, and F1 score were used for evaluation.

5. **Evaluation**  
   The model's performance was assessed for real-world usefulness and fairness across different population groups.

6. **Deployment**  
   While not deployed to a production environment, the final notebook includes a simulation of how predictions might inform healthcare decisions.

## File Structure

```bash
.
├── data/                 # Raw and cleaned data
├── notebooks/            # Jupyter notebooks for EDA and modeling
├── models/               # Saved models (if applicable)
├── outputs/              # Graphs, charts, and final results
├── .github/workflows/    # GitHub Actions CI workflow
├── README.md             # Project overview and instructions
└── requirements.txt      # Python dependencies
