Lab 9: Ensemble Methods – The Wisdom of the Crowd
Overview
This lab explores Ensemble Methods, a powerful machine learning strategy that combines the predictions of multiple individual models to create a final result that is more accurate and robust. I implemented and compared a single Decision Tree against a Random Forest (a "committee" of trees) to observe how diversity in modeling leads to superior performance.

Key Learning Objectives
The Wisdom of the Crowd: Understood the core concept that averaging the answers of a large, diverse group of models often produces more accurate results than any single "expert" model.

Bagging (Bootstrap Aggregating): Learned how Random Forests use bagging to train different trees on random subsets of data, reducing the risk of a single tree "overfitting" to a specific anomaly.

Feature Importance: Leveraged the Random Forest's ability to rank features. I learned how to identify which variables (like petal length or width) actually drive the model's decision-making process.

Performance Comparison: Directly compared the stability of a single Decision Tree vs. the resilience of a Forest.

Tools & Libraries
Scikit-Learn: Used for RandomForestClassifier and DecisionTreeClassifier.

Matplotlib: Used to visualize Feature Importance rankings, providing a "look under the hood" of the model's logic.

Challenges & Insights
Reducing Variance: A major insight was seeing how a single Decision Tree can be "fickle"—changing its mind based on small shifts in data. The Random Forest smoothed out these fluctuations, providing a much more stable and reliable prediction.

Interpretability vs. Power: I learned that while a single tree is easier to "read" (you can follow the branches), a Forest is more powerful. Using Feature Importance plots is the bridge that allows us to understand a complex ensemble model.

"Ranger" Connection
In my Microscope Buddy project, I don't want the robot to make a decision based on one single "glance." By using Ensemble logic, I can have the AI evaluate a biological sample from multiple "perspectives" (different zoom levels or lighting filters) and have them vote on the final classification. This lab taught me that for a robot to be truly autonomous in a messy lab environment, it needs the "Wisdom of the Crowd" to avoid being fooled by a single piece of noise.
