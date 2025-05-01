As part of my ongoing effort to improve my data science skills, I recently started a new project where I combined PySpark for large-scale data processing and TensorFlow for machine learning. 
Here's an overview of the workflow and techniques I used:

Pre-Processing (with PySpark)
- Loaded the dataset into a PySpark DataFrame for efficient handling of large data.
- Selected relevant columns and dropped null values to ensure data quality.
- Parsed the date field to extract the month number, useful for time-based analysis.

Exploratory Data Analysis (EDA)
- After aggregating the necessary metrics using PySpark, I converted the results to a Pandas DataFrame for easier plotting and visualization. Key insights included:
- Total orders by date: Tracked the volume of orders over time.
- Total orders by weekdays: find weekdays in which people orders the most.
- Sales amount by product category: Identified high-performing product types.
- Monthly order trends: Grouped by parsed month to observe seasonality.

Machine Learning (with TensorFlow)
- Applied Label Encoding to categorical features such as ship-city and status.
- Built a neural network model using TensorFlow to predict the likelihood of an order being cancelled, based on:
  - Shipping city
  - Order amount
