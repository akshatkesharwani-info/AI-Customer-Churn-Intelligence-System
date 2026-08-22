# AI Customer Churn Intelligence System

 
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![Free APIs](https://img.shields.io/badge/AI%20cost-%240%20(free%20tier)-success)

A churn prediction project that explains risk factors and generates actionable retention advice.

This project predicts whether a customer is likely to churn, shows why the model thinks so using SHAP, and then uses AI to suggest a practical retention strategy.

## Why this project

Businesses often know which customers may leave, but they also need to understand why and what to do next. This project connects prediction with explanation and action.

## What it does

- Trains a Random Forest model to predict churn probability.
- Uses SHAP to explain customer-level risk factors.
- Sends those factors to AI for a retention recommendation.
- Produces both model output and business-friendly explanation.

## Sample output

Customer ID: 0604-THJFP  
Churn Probability: 2%  
Main Reasons: [('Contract', -0.087), ('tenure', -0.054), ('TechSupport', -0.032)]

AI Recommendation:
Recommend proactively reaching out with a personalized contract-renewal incentive, bundled with a complimentary Tech Support upgrade.

## Model performance

- AUC: 0.83
- Accuracy: 0.79
- Precision (churn class): 0.65
- Recall (churn class): 0.49

## Dataset

- Telco Customer Churn
- Loaded directly from a public URL

## Tech Stack

- Python
- scikit-learn
- Random Forest
- SHAP
- Cerebras API
- Groq API
