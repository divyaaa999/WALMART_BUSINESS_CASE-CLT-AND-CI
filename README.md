# Walmart Customer Purchase Behavior Analysis

## Overview:

This project analyzes a dataset of customer transactions from Walmart during a Black Friday sale to understand customer purchasing behavior. The primary goal is to determine if there are significant differences in spending habits between male and female customers and to provide actionable insights for the business.

## Business Problem:

The management team at Walmart wanted to investigate whether female customers spend more than male customers during the Black Friday sales event. This analysis explores the relationship between the purchase amount and various customer demographics like gender, age, marital status, and city category.

## Dataset:

The dataset used for this analysis is walmart_data.csv, which contains transactional data of customers. Key features include:

###### User_ID

###### Product_ID

###### Gender

###### Age

###### Occupation

###### City_Category

###### Stay_In_Current_City_Years

###### Marital_Status

###### Product_Category
 
###### Purchase (Purchase Amount in dollars)

## Analysis and Findings:

The project involves a detailed exploratory data analysis (EDA) to understand the distribution of the data and the relationships between different variables. Statistical methods, specifically the Central Limit Theorem (CLT) and Confidence Intervals, were employed to make inferences about the larger population of Walmart customers.

## Key Insights:

###### Gender and Spending: 
The analysis revealed insights into the spending patterns of male and female customers. Confidence intervals for the average purchase amount for both genders were calculated to determine if there is a statistically significant difference.

###### Other Demographics: 
The study also explored how factors like age, marital status, and city of residence influence customer spending.

###### Product Categories: 
Insights were drawn about which product categories are most popular among different customer segments.

## Recommendations:

Based on the analysis, several actionable recommendations were proposed for Walmart's business strategy:

###### Targeted Marketing: 
Develop marketing campaigns tailored to the spending habits of different demographic segments (e.g., gender-specific promotions).

###### Product Placement: 
Optimize product placement in stores and online based on the purchasing patterns of various customer groups.

###### Personalized Offers: 
Leverage customer data to provide personalized discounts and product recommendations to enhance customer experience and drive sales.

## Technical Details:

The analysis was conducted using Python in a Jupyter Notebook (Walmart_Business_Case.ipynb). The key libraries used include Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and SciPy for statistical analysis.

This repository contains the dataset, the Jupyter Notebook with the complete analysis, and supplementary documents outlining the business case and questions.
