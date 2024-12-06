Objective
Perform automated EDA using Sweetviz and generate reports for full dataset analysis and subset comparisons.

Steps
1. Install and Import Libraries
Installed Sweetviz for auto-EDA.
Imported libraries (pandas, sweetviz).
2. Load the Dataset
Unzipped and loaded the NYC Yellow Taxi dataset from Google Drive.
Processed the first 100,000 rows for faster analysis.
3. Full EDA Report
Used sv.analyze() to generate a full HTML report with:
Summary statistics for all columns.
Feature distributions.
Correlations between numerical columns.
4. Subset Comparison
Created subsets based on trip distance:
Short Trips: trip_distance < 5 miles.
Long Trips: trip_distance >= 5 miles.
Used sv.compare() to generate a comparison report, highlighting differences in fare amounts, trip durations, and passenger counts.

