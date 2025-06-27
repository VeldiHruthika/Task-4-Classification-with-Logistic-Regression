Task 4: Classification with Logistic Regression

About this Task:
Hey! This is my fourth task where I worked on building a binary classifier using Logistic Regression. I used the popular Breast Cancer Wisconsin dataset for this.

The main goal was to predict if a tumor is malignant or benign based on various medical features.

What I did in this task:
1.Imported the Breast Cancer dataset from sklearn.datasets and loaded it into Pandas DataFrames.

2.Explored the dataset to check the number of samples, feature names, and target class labels.

3.Split the dataset into training and test sets (80% train and 20% test) to evaluate model performance on unseen data.

4.Standardized the features using StandardScaler so that all input features had the same scale (mean = 0, std = 1).

5.Trained a Logistic Regression model using LogisticRegression() from Scikit-learn.

6.Made predictions on the test set to check how well the model is performing.

7.Evaluated the model using:

i.Confusion Matrix (to check TP, FP, TN, FN counts)

ii.Precision, Recall, F1-Score (using Classification Report)

iii.ROC-AUC Score (to check how well the model distinguishes between the two classes)

iv.ROC Curve plot (to visualize model performance across different thresholds)

8.Tuned the threshold manually (changed it from default 0.5 to 0.6) and observed how the confusion matrix and other metrics changed.

9.Explained and plotted the Sigmoid Function, which is the core behind logistic regression — showed how it maps any input to values between 0 and 1.


Some observations I made:

I.The model gave a very high ROC-AUC (almost 1) meaning it performed really well on this dataset.

II.Changing the threshold affected the trade-off between precision and recall (fewer false positives vs false negatives).

III.The sigmoid curve helped me understand how logistic regression converts input values (log-odds) to probabilities.
