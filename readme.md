# **Amazon E-Commerce Analytics with PySpark**
## **Overview**
In this project, I combined PySpark for large-scale data processing and TensorFlow for machine learning to analyze Amazon e-commerce data. The project focuses on processing and analyzing large datasets, performing exploratory data analysis (EDA), and using machine learning techniques to predict the likelihood of order cancellations.

## **Pre-Processing**
- Loading the Data: Imported the dataset into a PySpark DataFrame for efficient handling of large volumes of data.
- Data Cleaning: Selected relevant columns and removed rows with null values to ensure the quality of the dataset.
- Date Parsing: Extracted the month number from the date field to facilitate time-based analysis.

## **Exploratory Data Analysis (EDA)**
- Analyzed the total volume of orders over time to observe sales trends.
- Identified which weekdays had the highest order volume, providing insights into consumer behavior.
- Examined sales performance across different product categories to identify high-performing product types.
- Calculated the average monthly sales amount to better understand overall sales trends.

## **Machine Learning (with TensorFlow)**
- Applied Label Encoding to categorical features like ship-city and status to convert them into numerical format for machine learning models.
- Built a neural network model using TensorFlow to predict order cancellations based on the following features:
  - Shipping City: The city where the order was shipped from.
  - Order Amount: The total amount of the order.

## **Key insights**
- Analyzing orders over time revealed sales trends, with certain weekdays showing higher order volumes, which can improve targeted marketing and promotional efforts.
- Product categories varied significantly in sales performance, providing insights into the most and least profitable product types for Amazon.
- The neural network model developed with TensorFlow to predict order cancellations based on key factors (shipping city, order amount) suggesting that these features play a significant role in cancellation likelihood.

## **Technologies Used**
 - **Python**, **Pandas**, **PySpark**, **TensorFlow**, **Matplotlib**.

## **Conclusions**
This project demonstrates how PySpark and TensorFlow can be useful to process large e-commerce datasets and apply machine learning to derive meaningful insights. The neural network model for predicting order cancellations proves the effectiveness of machine learning in forecasting customer actions. These insights can be used to optimize sales strategies and reduce cancellation rates, providing value to e-commerce businesses like Amazon.
