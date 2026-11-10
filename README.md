Task 32: Train-Test Split
Veda Technology – AI & ML Internship | AI & ML Track
Objective
Split a machine-learning dataset into training and testing subsets using Scikit-learn.
Dataset
The Iris dataset contains 150 records and five columns:
- sepal_length
- sepal_width
- petal_length
- petal_width
- species
Tools
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
Implementation
1. Load the Iris dataset.
2. Separate the feature columns (X) from the target column (y).
3. Use train_test_split() with test_size=0.2.
4. Set random_state=42 so the split can be reproduced.
5. Save the original, training, and testing datasets as CSV files.
Results
Dataset	Rows	Columns
Original dataset	150	5
Training features (X_train)	120	4
Testing features (X_test)	30	4
Training target (y_train)	120	
Testing target (y_test)	30	


Files
- Task32_Train_Test_Split.ipynb – complete implementation in one code cell
- iris.csv – original dataset
- train.csv – training subset (120 rows)
- test.csv – testing subset (30 rows)
- Task32_Report.docx – internship task report
Interview Questions
1. Why do we split data into training and testing sets?
To train a model on one portion of the data and evaluate its performance on separate, unseen data.

2. What is training data?
Training data is the portion used by a machine-learning model to learn patterns and relationships.

3. What is testing data?
Testing data is the separate portion used to evaluate how well the trained model performs on unseen examples.
Conclusion
The Iris dataset was successfully divided into 80% training data and 20% testing data using Scikit-learn. The training and testing subsets were saved as separate CSV files.