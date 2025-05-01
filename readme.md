Hi! this is a new data analytics project. As i always want to improve my skills, i recently decided to try TensorFlow and PySpark.

Pre-Processing:
  - Load PySpark dataframe, filter columns and drop null values.
  - Parse date to get number of the month

Eda: 
  - Aggregated the data using PySpark and then converted it to a Pandas DataFrame for easier visualization and analysis.
  - Group by category to plot amounts.
  - Group by months to plot total orders.

Machine learning:
  - Used label encorder to transform city o ship and status into numbers.
  - Used TensorFlow with a neural network to predict (using city ship and amount) if the order is likely to be cancelled.

