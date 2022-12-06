# **Amex-Default-Prediction (from kaggle)** 

This project aims to use Machine Learning methods to predict the Default rate of customers at American Express. The project is from Kaggle platform, which can be found at: https://www.kaggle.com/competitions/amex-default-prediction. 

## Contents:
**1. Data Compression:** Compress the dataset from 16GB --> 2GB;

**2. Exploratory Data Analysis**

**3. Machine Learning Techniques:**
 * **Feature Preprocessing:**
   * **Feature Engineering:** Aggregate the data from Transaction level --> Customer_ID level(each customer_id has many transactions);
   * **Feature Selection:** Reduce the feature set from 940 features to 300 features;
   * **Feature Transformation:** Imputing and Encoding

 * **Model Training:**
   * Trained **LightGBM** using Bayesian Optimization method;
   * **Model Calibration**



The **Original dataset** can be found in the Kaggle project link, and the **Preprocessed dataset**(trained on models) can be found at: https://www.kaggle.com/datasets/christal559/aml4995
