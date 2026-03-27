# Python Data Retrieval Project

## Overview
This project demonstrates how to retrieve, clean, and analyze real-world data using Python. The goal was to build a predictive model using a dataset that includes numeric, categorical, and text features.

## Dataset
Women's E-Commerce Clothing Reviews dataset (Kaggle)

This dataset contains customer reviews, product categories, and feedback information used to predict whether a customer recommends a product.

## Features Used

### Numeric Features
- Age  
- Positive Feedback Count  
- Review Length (engineered feature)

### Categorical Features
- Division Name  
- Department Name  
- Class Name  

### Text Feature
- Review Text (processed using TF-IDF)

### Label
- Recommended IND (whether the customer recommends the product)

## Process
1. Loaded dataset into Python using pandas  
2. Cleaned missing values  
3. Engineered new features (review length)  
4. Applied preprocessing:
   - Scaling numeric features  
   - One-hot encoding categorical features  
   - TF-IDF vectorization for text  
5. Built a Logistic Regression model  
6. Evaluated performance using accuracy, classification report, and confusion matrix  

## Tools & Technologies
- Python  
- Pandas  
- Scikit-learn  
- Google Colab  

## Results
The model successfully predicted customer recommendations with strong accuracy and demonstrated how structured and unstructured data can be combined in a single machine learning pipeline.

## Repository Structure
- Notebook: Atena_Rayson_Data_Retrieval.ipynb  
- Data: cleaned_clothing_reviews.csv  

## Author
Atena Rayson
