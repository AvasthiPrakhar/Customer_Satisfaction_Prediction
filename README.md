# Customer_Satisfaction_Prediction
Using feedback data from over 129,000 airline customers, a model that can predict the customer satisfaction KPI has been constructed.

A random forest classifier model was used to model this KPI.

The following actions were performed for a successful model:

- The data was explored and cleaned.
- Empty rows have been removed.
- The data was transformed appropriately to suit the model's needs.
- data was split into train, validate and test datasets.
- Hyperparameters for the model were tuned using GridSearchCV.
- An optimised Random forest was constructed based on the determined hyperparameters.
- The model was pickled locally.
- Evaluation metrics such as Precision, Accuracy, Recall and f1 score were determined.

Results:
- The constructed random forest model predicted satisfaction with more than 94.2% accuracy, 95% precision and approximately 94.5% recall.
