Lab 3: Machine Learning Workflow & Classification
Overview
This lab explores the fundamental machine learning lifecycle using the Wine Quality dataset. The primary focus was implementing a complete end-to-end workflow: from Exploratory Data Analysis (EDA) and data preprocessing to model training and evaluation.

Key Learning Objectives
Learning Paradigms: Distinguished between Supervised (classification/regression), Unsupervised (clustering), and Reinforcement Learning.

The ML Workflow: Implemented the 6-step standard process: Preparation → Feature Selection → Splitting → Training → Evaluation → Interpretation.

Classification Models: Built and compared a Logistic Regression model and a Decision Tree classifier.

Evaluation Metrics: Analyzed model performance using Accuracy Scores and Confusion Matrices to visualize misclassifications.

Tools & Libraries
Scikit-Learn: Used for data splitting (train_test_split), model building, and performance metrics.

Pandas & NumPy: Used for data manipulation and structure.

Matplotlib & Seaborn: Used for EDA, specifically for class distribution plots and feature correlation heatmaps.

Challenges & Insights
Feature Impact: Through hands-on experimentation, I discovered that selecting specific high-impact features (like proline and flavanoids) significantly improved model accuracy compared to using arbitrary features.

The "Trap" Recognition: Identifying patterns in the confusion matrix helped me understand which wine classes were more easily confused by the algorithm, emphasizing the importance of data quality over just algorithmic complexity.

"Ranger" Connection
In my final project, the "Microscope Buddy," I apply these same workflow principles. Just as I had to distinguish between wine cultivars here, my AI must distinguish between biological cells and air bubbles. This lab provided the structural blueprint for how I handle data splitting and model validation in my robotics research.
