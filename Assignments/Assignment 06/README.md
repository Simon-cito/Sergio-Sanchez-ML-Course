Assignment 06: Linear Models – Regression vs. Classification
The Problem
The objective of this assignment was to differentiate between the two primary types of supervised learning. I was tasked with solving two distinct problems using the Titanic dataset:

Regression: Predicting a continuous numerical value (the Ticket Fare).

Classification: Predicting a discrete category (Survival: Yes or No).

My Approach
Linear Regression for Fare Prediction: I built a model to predict how much a passenger paid based on their Ticket Class (Pclass) and other demographics. I learned that in regression, the goal is to minimize the "distance" between the prediction and the actual price.

Logistic Regression for Survival: I implemented a classification model to determine survival probability. Even though it has "Regression" in the name, I utilized it here as a classifier to draw a boundary between survivors and non-survivors.

Feature Analysis: I analyzed the Coefficients of the models to see which variables had the most weight. For example, I confirmed that a higher Ticket Class (lower numerical value) had a strong positive correlation with a higher Fare.

Results & Insights
Metric Selection: This assignment highlighted why we use different "yardsticks" for different problems.

For Fare Prediction, I used Mean Squared Error (MSE) because accuracy doesn't work for continuous numbers (being off by $0.01 is still a "good" prediction).

For Survival, I used Accuracy Score to see what percentage of the binary outcomes were correct.

Model Limitations: I discovered that while linear models are powerful, they assume a straight-line relationship. This insight helped me understand when more complex models (like those in later assignments) might be necessary.

"Ranger" Connection
This assignment represents the "Analytical Core" of the Microscope Buddy. When the robot moves its motors to focus, it uses Regression logic to calculate the precise numerical distance. When it looks at an object and decides if it is a "Cell" or "Debris," it uses Classification. By mastering both in this assignment, I have built the foundation for a robot that can both measure its environment and make decisions within it.
