# Practical Assignment 8: Decision Trees

This assignment involves building a **Decision Tree Classifier** using the **Pima Indians Diabetes Dataset** (from Kaggle) to predict the onset of diabetes based on diagnostic measures.

## Objectives
1.  **Data Preparation:** Downloading the dataset and performing **Feature Selection** (Splitting Dependent `Outcome` vs. Independent variables).
2.  **Modeling:** Splitting the data into training/testing sets and building a Decision Tree Classifier using `scikit-learn`.
3.  **Visualization:** Creating a pictorial representation (flowchart) of the decision tree to interpret the decision rules.
4.  **Metric Analysis:** Calculating and explaining **Entropy**, **Information Gain**, and **Gini Index** to justify the selection of the root node and subsequent splits.

## Libraries Used
* **Pandas/Numpy:** Data handling.
* **Scikit-Learn:** Decision Tree implementation (`DecisionTreeClassifier`), data splitting, and metrics.
* **Matplotlib/Graphviz:** Visualizing the tree structure.