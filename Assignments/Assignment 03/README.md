The Problem
In this assignment, the goal was to develop a predictive model that could accurately categorize different types of wine based on their chemical composition. Unlike basic binary classification, this required the model to distinguish between three distinct categories using 13 different chemical features (such as Alcohol, Malic Acid, and Ash).

My Approach
Multiclass Logic: I implemented a Logistic Regression model specifically configured for multiclass targets.

Feature Analysis: I explored the Wine Dataset to understand how chemical markers correlate with specific wine cultivars.

Model Training: I split the data into training and testing sets (80/20) to ensure the model could generalize its "tasting" logic to new samples it hadn't seen before.

Validation: I used an accuracy score to measure how often the model correctly identified the specific wine type.

Results & Insights
Model Performance: The model achieved high accuracy, proving that chemical profiles are distinct enough to be used as a "fingerprint" for wine classification.

Chemical Predictors: I observed that certain features, like Proline and Flavanoids, had a significant impact on the model's ability to separate the three classes.

The "Decision Boundary": This assignment taught me that even with multiple categories, a linear model can find the "boundary" between groups if the data is preprocessed correctly.

"Ranger" Connection
This assignment provides the "Sorting" logic for the Microscope Buddy. In a lab setting, my robot won't just see "target" or "no target"; it will encounter various types of biological entities (e.g., bacteria, cells, debris). The multiclass classification skills I used here allow my robot to not just detect an object, but to categorize exactly what it is, similar to how this model identifies the specific cultivar of a wine based on its "ingredients."
