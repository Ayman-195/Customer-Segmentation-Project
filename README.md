# Customer Segmentation

## Table of Contents:
- [Introduction](#introduction)
- [Attributes](#attributes)
- [Importing Libraries](#importing-libraries)
- [Loading the Data](#loading-the-data)
- [Data Cleaning & Feature Engineering](#data-cleaning--feature-engineering)
- [Data Preprocessing](#data-preprocessing)
- [Clustering](#clustering)
- [Data Insights](#data-insights)
- [Conclusion](#conclusion)

## Introduction:
This project aims to perform customer segmentation using unsupervised clustering methods, focusing on KMeans and DBSCAN algorithms. The objective is to group customers based on their purchasing behavior, family structure, income, and response to promotional campaigns. After testing different clustering techniques, KMeans was selected as the final method due to its superior performance.

## Attributes:
The dataset consists of several attributes divided into categories: People, Products, Promotion, and Place.

### People:
- **ID**: Customer's unique identifier
- **Year_Birth**: Customer's birth year
- **Education**: Customer's education level
- **Marital_Status**: Customer's marital status
- **Income**: Customer's yearly household income
- **Kidhome**: Number of children in the customer's household
- **Teenhome**: Number of teenagers in the customer's household
- **Dt_Customer**: Date of customer's enrollment with the company
- **Recency**: Number of days since the customer's last purchase
- **Complain**: 1 if the customer complained in the last 2 years, 0 otherwise

### Products:
- **MntWines**: Amount spent on wine in the last 2 years
- **MntFruits**: Amount spent on fruits in the last 2 years
- **MntMeatProducts**: Amount spent on meat in the last 2 years
- **MntFishProducts**: Amount spent on fish in the last 2 years
- **MntSweetProducts**: Amount spent on sweets in the last 2 years
- **MntGoldProds**: Amount spent on gold in the last 2 years

### Promotion:
- **NumDealsPurchases**: Number of purchases made with a discount
- **AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- **AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- **AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- **AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- **AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- **Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise

### Place:
- **NumWebPurchases**: Number of purchases made through the company’s website
- **NumCatalogPurchases**: Number of purchases made using a catalogue
- **NumStorePurchases**: Number of purchases made directly in stores
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month

### Target:
The target of this project is to perform clustering to summarize customer segments and understand their behaviors.

## Importing Libraries:
The project begins by importing essential libraries for data manipulation, visualization, and clustering.

## Loading the Data:
The dataset is loaded and briefly explored to understand its structure and key attributes.

## Data Cleaning & Feature Engineering:
This section covers data cleaning processes such as handling missing values, outlier detection, and feature engineering, including creating new features that enhance clustering performance.

## Data Preprocessing:
Preprocessing steps include scaling numerical features, encoding categorical variables, and performing dimensionality reduction techniques to optimize the data for clustering.

## Clustering:
Multiple clustering methods, including KMeans and DBSCAN, were tried. After evaluating performance metrics and visualizing clusters, KMeans was selected as the final approach due to its clear and interpretable results.

## Data Insights:
Using the identified clusters, the data was analyzed to extract meaningful insights. The clusters were profiled based on various attributes, such as age, education, family size, marital status, and spending habits, to understand customer segments better.

## Conclusion:
In this project, unsupervised clustering was performed using KMeans. After dimensionality reduction and cluster analysis, four distinct clusters were identified. These clusters were then profiled based on family structure, income, and spending patterns. The results provide valuable insights that can be used to develop targeted marketing strategies and improve customer engagement.
