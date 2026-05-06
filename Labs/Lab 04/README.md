Lab 4: Exploratory Data Analysis (EDA) – The Titanic Dataset
Overview
This lab focuses on Exploratory Data Analysis (EDA), the essential process of using summary statistics and visualization to uncover patterns and anomalies before building a machine learning model. Using the famous Titanic dataset, I acted as a "data detective" to find the "hidden truths" behind passenger survival.

Key Learning Objectives
Pattern Recognition: Identified that wealth (Class) and demographics (Age/Sex) were the strongest predictors of survival.

Statistical Visualization: Implemented various plot types to see what raw numbers hide:

Count Plots: To visualize the survival gap between classes.

Histograms: To find age-based survival "spikes" (identifying that children had a higher survival rate).

Boxplots: To identify outliers in Fare prices and understand the distribution of wealth on the ship.

Data Integrity: Used .info() and .describe() to check for missing values and data types, ensuring the dataset was healthy before analysis.

Tools & Libraries
Seaborn & Matplotlib: Used for creating advanced statistical visualizations.

Pandas: Used for data manipulation, grouping, and summary statistics.

Challenges & Insights
Beyond the Mean: A major insight from this lab was that summary statistics like the "mean" can be misleading. For example, while the average fare might seem low, a Boxplot revealed extreme outliers in 1st Class that skewed the average.

The Survival "Spike": By using histograms with a "hue" for survival, I could clearly see that being a "Female from 1st Class" or a "Young Child" were the most significant indicators of survival, supporting the "women and children first" historical narrative with hard data.

"Ranger" Connection
In my Robotics work, EDA is how I calibrate sensors. Just as I looked for anomalies in the Titanic data, I use these same visualization techniques to find "noise" in robotic sensor feeds. Identifying the "hidden truth" in a dataset is exactly like identifying the "scent" of biological cells in a blurry microscope slide—it requires looking past the surface level to find the underlying patterns.
