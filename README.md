# Product Recommendation & Sentiment Analysis System

## Problem Statement
Online shoppers rely heavily on product reviews to make purchase decisions.
This project analyzes public retail product reviews to:
- Identify sentiment using Machine Learning
- Identify bestselling products per category
- Detect underperforming products driven by negative feedback
- Provide actionable business insights

## Approach
- Exploratory Data Analysis to understand review patterns
- TF-IDF based text vectorization
- Logistic Regression with class balancing
- Product-level sentiment aggregation
- Root-cause analysis using negative review themes

## Repository Structure
- notebooks/ : Jupyter notebooks for EDA, modeling, and insights
- outputs/ : CSV files with final results

## How to Run
Install dependencies:
pip install -r requirements.txt

Run notebooks in order:
1. 01_eda.ipynb
2. 02_sentiment_model.ipynb
3. 03_product_insights.ipynb

## Author
Vadla Koushik
