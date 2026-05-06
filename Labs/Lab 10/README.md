```markdown
# Lab 10: Unsupervised Learning – Clustering & PCA

## Overview
This lab explores Unsupervised Learning, the branch of machine learning that finds hidden structures in unlabeled data. I implemented two primary techniques: K-Means Clustering to automatically group similar data points and Principal Component Analysis (PCA) to simplify complex datasets while preserving their essential information.

## Key Learning Objectives

* **K-Means Clustering: Implemented the K-Means algorithm to discover natural groupings within the Iris dataset without using pre-existing labels.
* **The Elbow Method: Used the "Elbow" visualization to mathematically determine the optimal number of clusters ($k$). I learned how to balance model complexity with cluster cohesion.
* **Principal Component Analysis (PCA): Applied PCA to reduce the Iris dataset from 4 dimensions down to 2. I discovered that 95% of the data's "truth" could be maintained even after removing half the features.
* **Pattern Discovery: Learned how unsupervised models can act as a "first pass" for data scientists to understand a new dataset before applying supervised labels.

---

## Challenges & Insights

* **Dimensions of Truth: A major insight was realizing that high-dimensional data often contains redundant information. PCA proved that we can "flatten" a dataset to make it easier for humans to see patterns without losing the core signal of the data.
* **The Subjectivity of Clusters: I learned that unlike classification (where there is a right/wrong answer), clustering requires a human "Ranger" to interpret if the groups found by the AI make logical or physical sense in the real world.



---

## "Ranger" Connection

In my **Microscope Buddy** project, Unsupervised Learning is for discovery. If the robot sees a sample it has never encountered, it can use K-Means to say, *"I don't know what this is yet, but I've found 12 other things that look just like it."*
