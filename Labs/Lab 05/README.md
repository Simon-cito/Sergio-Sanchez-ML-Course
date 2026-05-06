Lab 5: Data Preparation & Preprocessing Techniques
Overview
This lab focuses on the critical transition from raw, "messy" data to model-ready features. Using the Titanic dataset, I implemented advanced preprocessing techniques to handle missing information and transform categorical variables into numerical formats that a machine learning engine can process.

Key Learning Objectives
Imputation (Handling Missing Data): Applied statistical strategies to fill gaps in the dataset, such as using the median for age to avoid the skewing effects of outliers.

Categorical Encoding: Implemented One-Hot Encoding to translate text-based data (like "Sex" or "Embarked") into binary vectors (1s and 0s).

Feature Engineering: Created new, more predictive features by dropping irrelevant data (like Cabin or Ticket) and focusing on the core attributes that drive model decisions.

Pipeline Logic: Understood that models are "mathematical engines" that require numerical continuity to function correctly.

Tools & Libraries
Pandas: Used for .fillna() operations and creating dummy variables with get_dummies.

Scikit-Learn: Utilized for splitting data and initializing the preprocessing logic.

Challenges & Insights
The "Why" of One-Hot Encoding: A key insight was realizing that a computer cannot calculate "Male + Female," but it can calculate the presence (1) or absence (0) of a trait. This is a fundamental concept in how I approach AI objectivity.

Decision Tree Resilience: I learned that while some models require "Feature Scaling" (making all numbers the same size), Decision Trees are naturally resilient to different scales because they evaluate features independently at each split.

"Ranger" Connection
In the development of my Ethos Engine (my AI governance project), data preparation is where "Moral Logic" begins. By using One-Hot Encoding, I can allow an AI to process complex cultural or dietary needs objectively without assigning an arbitrary "ranking" to them. This lab taught me how to structure data so that the resulting AI decisions are both mathematically sound and contextually fair.
