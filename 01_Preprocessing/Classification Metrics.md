## Classification metrics

Classification metrics are used to evaluate the performance of classification models, which predict categorical outcomes. Here is a summary of the most common classification metrics:

1. Accuracy: Measures the proportion of correct predictions, that is, the number of true positives plus the number of true negatives divided by the total number of samples. It is a good metric when the classes are balanced, but can be misleading when the classes are imbalanced.

2. Precision: Measures the proportion of true positives among the total number of positive predictions. It is a good metric when the focus is on minimizing false positives.

3. Recall: Measures the proportion of true positives among the total number of actual positives. It is a good metric when the focus is on minimizing false negatives.

4. F1 score: The harmonic mean of precision and recall. It is a good metric when there is a trade-off between precision and recall.

5. ROC curve and AUC: ROC (Receiver Operating Characteristic) curve plots the true positive rate against the false positive rate at different classification thresholds. AUC (Area Under the Curve) measures the area under the ROC curve, which represents the model's ability to distinguish between positive and negative samples.

6. Confusion matrix: A table that summarizes the number of true positives, true negatives, false positives, and false negatives. It is useful for understanding the types of errors made by the classifier.

7. Log loss: Measures the logarithmic loss between the predicted probabilities and the true binary labels. It is a good metric when the model outputs probabilities instead of discrete predictions.

8. Classification report: A summary of precision, recall, F1 score, and support for each class, as well as the overall accuracy and macro/micro average scores. It is a good way to get an overview of the model's performance across different classes.