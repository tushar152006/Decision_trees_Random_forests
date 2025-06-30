# Decision_trees_Random_forests
Task 5: Decision Trees and Random Forests

 Objective
The objective of this task is to explore tree-based models such as **Decision Trees** and **Random Forests** for classification problems using Scikit-learn and Graphviz.

Tools & Libraries
(Python,Scikit-learn,Pandas,Matplotlib & Seaborn (for visualization),Graphviz (for tree rendering))


 Dataset
We used a dataset related to heart disease prediction.


Steps Performed

 1. Load and Preprocess Data
- Load the dataset using `pandas`.
- Split into features (`X`) and target (`y`).
- Train/test split using `train_test_split`.

2- Fit a `DecisionTreeClassifier`.
- Predict and evaluate using `accuracy_score` and `classification_report
 
 3. Visualize the Tree
- Export the trained tree using `export_graphviz`.
- Visualize using the `graphviz` library.

 4. Analyze Overfitting
- Plot training and testing accuracy across different tree depths.

5. Train Random Forest Classifier
- Use `RandomForestClassifier` with multiple trees.
- Compare performance with the decision tree.

6. Feature Importance
- Extract and visualize feature importance from the Random Forest.

7. Cross-Validation
- Use `cross_val_score` to validate model stability.

Evaluation Metrics
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Cross-validation scores


 Files
- `decision_tree.png`: Visualization of the trained decision tree.
- `heart.csv`: Dataset used.
- `task5_decision_tree_random_forest.ipynb`: Main notebook file.



 Key Learnings
- Decision trees can overfit, so controlling depth is important.
- Random forests help reduce variance and improve accuracy.
- Feature importances help interpret models.


