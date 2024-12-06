Perform a detailed exploratory data analysis (EDA) on the NYC Yellow Taxi dataset, using advanced interactive visualizations (e.g., D3.js or Plotly).

Steps
1. Import Libraries and Load Dataset
Imported necessary libraries, including pandas and plotly.
Loaded the dataset (yellow_tripdata_2015-01.csv) from a .zip file stored on Google Drive.
Filtered the data to load only 100,000 rows for faster processing.
2. Data Cleaning
Converted tpep_pickup_datetime and tpep_dropoff_datetime columns to datetime format.
Calculated a new feature, trip_duration, in minutes.
Removed outliers in trip_duration (values >120 minutes or <1 minute).
Handled missing values and dropped irrelevant columns.
3. Data Analysis
Generated basic statistics for the dataset.
Correlation heatmap: Explored relationships between numerical columns like trip_distance, fare_amount, and trip_duration.
4. Visualization
Bar Chart:
Visualized the top 5 longest trips (trip_distance) and their corresponding fare_amount.
Scatter Plot:
Showed the relationship between trip_distance and fare_amount.
Marker size and color represent fare amounts for better interpretability.

Insights from the dataset:
Longer trips generally have higher fares.
Outliers were removed to improve data quality.


