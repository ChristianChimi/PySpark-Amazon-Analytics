## **Amazon E-Commerce Analytics with PySpark**

In this project, I combined PySpark for large-scale data processing and TensorFlow for machine learning to analyze Amazon e-commerce data. The project focuses on processing and analyzing large datasets, performing exploratory data analysis (EDA), and using machine learning techniques to predict the likelihood of order cancellations.

## **Pre-Processing**
    - Loading the Data: Imported the dataset into a PySpark DataFrame for efficient handling of large volumes of data.
    - Data Cleaning: Selected relevant columns and removed rows with null values to ensure the quality of the dataset.
    - Date Parsing: Extracted the month number from the date field to facilitate time-based analysis.

## **Exploratory Data Analysis (EDA)**
    - Total Orders by Date: Analyzed the total volume of orders over time to observe sales trends.
    - Total Orders by Weekday: Identified which weekdays had the highest order volume, providing insights into consumer behavior.
    - Sales Amount by Product Category: Examined sales performance across different product categories to identify high-performing product types.
    - Average Monthly Sales: Calculated the average monthly sales amount to better understand overall sales trends.

## **Machine Learning (with TensorFlow)**
    - Label Encoding: Applied Label Encoding to categorical features like ship-city and status to convert them into numerical format for machine learning models.
    - Neural Network Model: Built a neural network model using TensorFlow to predict order cancellations based on the following features:
        - Shipping City: The city where the order was shipped from.
        - Order Amount: The total amount of the order.
## **Key insights**
    - Order Trends: Analyzing orders over time revealed clear trends in sales volume, with certain weekdays showing higher order volumes, which can inform targeted marketing and promotional efforts.
    - Sales Performance: Product categories varied significantly in sales performance, providing insights into the most and least profitable product types for Amazon.
    - Cancellation Prediction: The neural network model developed with TensorFlow was able to predict order cancellations effectively based on key factors such as shipping city and order amount, suggesting that these features play a significant role in cancellation likelihood.


## **Conclusions**
This project demonstrates how PySpark and TensorFlow can be leveraged to process large e-commerce datasets and apply machine learning to derive meaningful insights. Through exploratory data analysis, we were able to identify key trends in sales, consumer behavior, and product performance. The neural network model for predicting order cancellations proves the effectiveness of machine learning in forecasting customer actions. These insights can be used to optimize sales strategies and reduce cancellation rates, providing value to e-commerce businesses like Amazon.

## **Technologies Used**
 - **Python**, **Pandas**, **PySpark**, **TensorFlow**, **Matplotlib**.
