Assignment 12: Ethics, Fairness, and Bias in Machine Learning
The Problem
Machine learning models are only as fair as the data used to train them. If historical data contains societal biases, the resulting AI will likely inherit and amplify those prejudices. The goal of this assignment was to conduct a Fairness Audit on a real-world dataset to identify demographic disparities and evaluate the ethical implications of deploying such a model in sensitive areas like hiring or lending.

My Approach
Algorithmic Auditing: I trained a baseline classification model and then "interrogated" its performance across different demographic subgroups (specifically focusing on Gender and Race).

Fairness Metrics Analysis: I calculated and compared specific metrics for each subgroup:

False Positive Rate (FPR): How often the model incorrectly predicted a "positive" outcome for a specific group.

False Negative Rate (FNR): How often the model missed a "positive" outcome for a specific group.

The Proxy Investigation: I researched why simply "removing" sensitive columns like 'sex' or 'race' (Fairness through Blindness) is often ineffective because other features (like zip code or occupation) can act as mathematical proxies for that missing information.

Results & Insights
Identifying Disparate Impact: My analysis revealed that the model did not perform equally across all groups. A significant gap in False Negative Rates proved that the model was systematically "missing" qualified individuals from certain demographics.

The "Fairness vs. Accuracy" Trade-off: I learned that a model with high overall accuracy can still be a "failed" model if its errors are concentrated on a vulnerable subgroup.

Ethical Decision-Making: This assignment shifted my perspective from seeing AI as a purely mathematical tool to seeing it as a social one. I learned that as an engineer, I must decide which error types (FPR vs. FNR) are more harmful based on the real-world context of the application.

"Ranger" Connection
This assignment is the moral compass for my Ethos Engine. A "Ranger" must ensure the path is safe for everyone, not just the majority. Whether it is ensuring my Microscope Buddy isn't biased toward certain lighting conditions that might hide specific cell types, or building an AI startup in 2026, this lab provided the auditing framework I will use to ensure my technology is high-performing, transparent, and fundamentally just.
