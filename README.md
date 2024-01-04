# Instacart Market Basket Analysis

<img src="https://github.com/anubhavnehru/Instacart-Market-Basket-Analysis/assets/32483022/dadb46fd-6fdf-4a9e-875a-a255b2829a2c" width="800" height="500">

## Project Overview

This project focuses on leveraging [open-source Instacart data](https://www.kaggle.com/c/instacart-market-basket-analysis) to conduct in-depth analysis of customer shopping behavior. The primary goal is to identify customer segments and perform market basket analysis using advanced machine learning algorithms, including Apriori and a Rule-Based Ensemble Model.


Key Concepts used :
- EDA
- Customer Segmentation: K-means over PCA
- Market Basket Analysis : Apriori Algorithm and Rule-Based Ensemble Model

## Problem Statement

Market basket analysis is a pivotal aspect for retailers, providing insights into customer shopping behavior to enhance decision-making. By harnessing customer transaction data and addressing data management challenges, businesses can optimize product placement and elevate the overall customer experience, particularly in the online grocery sector represented by platforms like Instacart.

- Understanding Customer Shopping Behavior
- Identifying distinct customer segments based on their purchasing patterns
- Predicting products likely to be reordered
- Conducting department and aisle analysis
- Uncovering peak purchasing times and days of the week for targeted promotional activities

## Project Contents

- Data Exploration and Preprocessing
- Customer Segmentation Analysis
- Market Basket Analysis using Apriori Algorithm
- Rule-Based Ensemble Model Implementation

## Technologies Used

- Pandas, NumPy, Scikit-learn
- Data Visulaization
- PCA
- K-means
- Apriori Algorithm
- Rule-Based Ensemble Model


## Key Findings

- Conducted comprehensive department and aisle analysis.
- Identified peak purchasing times for effective targeted promotions.
- Discovered distinct customer segments based on purchasing behavior.
  - Health Enthusiasts
  - Snack Lovers
  - Veggie Lovers
  - Diary Enthusiasts
  - Balanced Shoppers   
- Same Brand Same Product Different Flavour
   - Based on the market basket analysis the key finding was that customers have a higher probability of buying the same brand's same product but of a different flavour

<p align="center">
<img src="https://github.com/anubhavnehru/Instacart-Market-Basket-Analysis/assets/32483022/19586a75-f077-447e-a420-66f1ddb7b0f9" width="300" height="300">
</p>

## Future Enhancements

- To optimize Market Basket Analysis, we need to categorize customers into distinct segments based on the user’s preferences. We can improve the understanding of these preferences by including additional data such as consumer demographics
- We propose two levels of cross-selling product recommendations
  - Cross-selling with Highest Lift Product
  - Recommending products with the strongest lift with aisle
- If we get Revenue information from Instacart,we can run more Customer Targeting analysis, like RFM Analysis, CLTV, etc

- Enhanced visualization for intuitive data interpretation.

Feel free to explore the notebooks and provide feedback. Your insights are valuable for continuous improvement!
