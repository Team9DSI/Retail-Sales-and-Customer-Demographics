# Retail Sales and Customer Demographics Analysis

## Project Overview

This project aims to analyze a dataset containing retail sales transactions and customer demographics. By leveraging machine learning techniques, we will derive insights, forecast sales, and understand customer behavior. The dataset includes various features such as transaction details, customer demographics, and geographical information.

In today’s competitive retail landscape, understanding customer behavior and sales trends is crucial for success. This project seeks to harness the power of data analysis and machine learning to explore a comprehensive dataset that encompasses retail sales and customer demographics.

By analyzing transaction data, customer profiles, and geographical information, we aim to uncover actionable insights that can inform marketing strategies, optimize inventory management, and enhance customer experience.

---

🌐 [**`https://www.team9.ca`**](https://team9.ca) **Explore a live, interactive MVP demo on our website!**

- Our interactive website showcases models we've built as part of our data science and machine learning projects. Explore hands-on tools that demonstrate how machine learning solves real-world challenges, from predicting sales trends to understanding customer behavior.

---


### Key Objectives

- **Purchasing Behavior Analysis**: Understand how new customers differ in purchasing behavior from returning customers, identifying trends and customer preferences.
- **Customer Segmentation**: Use clustering techniques to segment customers based on their purchasing behavior, enabling targeted marketing campaigns.
- **Product Recommendation System**: Develop a product recommendation system using K-Nearest Neighbors (K-NN) to enhance cross-selling and upselling opportunities.
- **Sales Forecasting**: Build time series models to predict future sales, helping retailers prepare for demand fluctuations.
- **Customer Lifetime Value (CLV) Prediction**: Predict the total value a customer will generate over their lifetime to identify high-value customers and tailor retention strategies.
- **Behavioral Insights**: Analyze how factors such as age and gender influence product preferences, transaction size, and purchase frequency.

By leveraging these insights, retailers can make data-driven decisions to improve customer acquisition, retention, and revenue generation, resulting in a more personalized and efficient retail experience.
Join us on this journey to transform raw data into meaningful strategies for success in the retail sector!

### Team Members

[**`Charles Colaco`**](https://github.com/CharlesColaco),[**`Mark Conrad Maramag`**](https://github.com/markmaramag),[**`Srujana Gunde`**](https://github.com/s-gunde)

## Table of Contents

- [Implementation](https://github.com/Team9DSI/Retail-Sales-and-Customer-Demographics/blob/main/models/README.md)  (**Explore our Jupyter Notebooksto Dive deeper into our Machine Learning Projects**)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Analysis and Predictions](#analysis-and-predictions)
- [Data Preparation](#data-preparation)
- [Video Links](#video-links)


## Dataset Description

The dataset contains the following columns:

- **Transaction ID**: Unique identifier for each transaction.
- **Date**: Date when the transaction occurred.
- **Customer ID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Product Category**: Category of the purchased product (e.g., Electronics, Clothing).
- **Quantity**: Number of units purchased.
- **Price per Unit**: Price of one unit of the product.
- **Total Amount**: Total monetary value of the transaction.
- **Geographical Information**: City, Province, Country


## Technologies Used

- **Python**: Programming language for data analysis and modeling.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Numerical operations and matrix manipulations.
- **Scikit-learn**: Machine learning library for modeling and prediction.
- **Matplotlib / Seaborn**: Data visualization tools to create graphs and charts.
- **Keras**
- **Jupyter Notebook / JupyterLab**: Interactive development environment for analysis and visualization.

## Analysis and Predictions

### Key Business Questions

- **How does the purchasing behavior of new customers differ from that of returning customers?**  
  We will analyze transaction patterns and differences in purchase frequency, category preferences, and transaction amounts.

- **Are certain product categories more popular with specific genders?**  
  By segmenting customers by gender, we can identify which product categories are more frequently purchased by men or women.

- **Can we predict the quantity of items a customer will purchase in a single transaction based on their demographics and previous transaction history?**  
  Using regression models, we will predict the quantity of items a customer will likely purchase, factoring in their demographics and historical purchases.

- **Is there any relationship between the categories purchased, gender and the total amount spent?**  
  We will explore correlations between product categories purchased, gender and total transaction amounts to uncover key purchasing patterns.

### Predictive Modeling

- **Sales Forecasting**: Time series analysis (e.g., SARIMA) will be used to forecast future sales based on historical trends.
- **Customer Segmentation**: Clustering algorithms (e.g., K-Means, Hierarchical Clustering) will be used to group customers based on their purchasing behavior, enabling targeted marketing campaigns.
- **Purchasing Behaviour Analysis**: Random Forest model will be used to explore differences in purchasing behaviour between new and returning customers, focusing on trends, spending, and discounts.
- **Recommendation System**: Deeplearning Models & Techniques will be used to build a product recommendation system that suggests products based on customer purchase history and preferences.
- **Customer Lifetime Value (CLV)**: Regression and classification techniques will be used to predict the CLV of customers, helping identify high-value customers.

## Data Preparation

- **Data Cleaning and Preprocessing**:
  - Handle missing values, remove duplicates, and correct inconsistencies in the dataset.
  - Normalize data for consistent analysis, particularly in demographic variables (e.g., age, gender).
- **Feature Engineering**:
  - Extract date-based features (e.g., month, weekday) to understand seasonal patterns.
  - Calculate Customer Lifetime Value (CLV) by aggregating customer transaction data over time.
- **Handling Missing Values and Outliers**:

  - Missing values will be handled using imputation or removal depending on the nature of the data.
  - Outliers will be detected and addressed to avoid skewed analysis and predictions.

- **Normalization and Encoding**:
  - Normalize numerical variables for consistent scaling across features.
  - Encode categorical variables (e.g., gender, product category) using techniques like one-hot encoding or label encoding.

## Video Links

- [Charles Colaco](https://drive.google.com/file/d/1K9jHiWTrfJU5oZKNKApZrtPnZ2P7OLzB/view?usp=drive_link)
- [Mark Conrad Maramag](https://drive.google.com/file/d/1Y_UIF5wVGIqj1NvTb8UUpYtCzNQLxylc/view?usp=drive_link)
- [Srujana Gunde](https://drive.google.com/file/d/1HEMeCCWRaVIcdLkoJIekfLS-B6HUcp5i/view?usp=sharing)
  
## Conclusion

This project aims to transform raw retail sales and customer demographic data into actionable business insights. By employing machine learning techniques, we will not only uncover trends in customer behavior but also build predictive models that can forecast sales, recommend products, and predict customer lifetime value. The insights generated will assist retailers in optimizing their marketing, inventory, and sales strategies, ultimately improving customer satisfaction and driving growth.
