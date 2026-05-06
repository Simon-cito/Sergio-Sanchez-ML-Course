Assignment 04: Exploratory Data Analysis (EDA) – The Titanic Dataset
The Problem
Before building a predictive model, a machine learning engineer must understand the "raw material"—the data. The goal of this assignment was to perform a deep-dive Exploratory Data Analysis on the Titanic passenger manifest to identify patterns, handle missing information, and determine which factors (features) most strongly correlate with survival.

My Approach
Data Profiling: Used Pandas to inspect the dataset’s structure, identifying 891 entries and 12 initial features.

Cleaning & Imputation: Addressed the "Age" and "Cabin" columns, which had significant missing data. I learned how to fill these gaps without distorting the overall distribution.

Statistical Visualization: Created charts to visualize survival rates across different demographics.

Gender Bias: Analyzed the "Women and Children First" protocol's impact on the data.

Socio-Economic Impact: Investigated the correlation between Ticket Class (Pclass) and survival probability.

Feature Engineering: Identified that "Sex" and "Pclass" were the most powerful predictors, while "Embarked" and "Fare" provided additional secondary context.

Results & Insights
The Survival Gap: The EDA clearly visualized the wealth gap; passengers in 1st class had a significantly higher survival rate than those in 3rd class, regardless of age.

The Power of Visuals: By using Histograms and Boxplots, I was able to see outliers in the "Fare" data that could have confused a machine learning model if left unaddressed.

Preparing for the Model: This analysis served as the blueprint for the preprocessing steps taken in later assignments. It proved that "cleaning" is 80% of the work in AI.

"Ranger" Connection
In my Microscope Buddy project, EDA is the "Scouting Report." Before I can program a robot to find a cell, I have to analyze hundreds of images to understand what a "normal" cell looks like versus a "distraction" (like a bubble or a scratch). This assignment taught me the discipline of questioning my data before trusting it—a vital skill for ensuring my robotic systems are accurate and unbiased.
