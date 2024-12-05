# 20-ch-Supervised-Learning
Analysing the Logistic Regression Model's Performance <br>
Key metrics:<br>

Precision: This metric measures the proportion of positive predictions that are actually positive. For class 0 (healthy loans), the precision is 1.00, which means that every prediction of a healthy loan was indeed correct. For class 1 (risky loans), the precision is 0.84, indicating that 84% of predicted risky loans were accurate.<br>

Recall: This metric measures the proportion of actual positive cases that were correctly identified. For class 0, the recall is 0.99, meaning that 99% of all actual healthy loans were correctly predicted. For class 1, the recall is 0.94, indicating that 94% of all actual risky loans were correctly identified.<br>

F1-score: This is the harmonic mean of precision and recall, providing a balanced measure of performance. For both classes, the F1-score is high, suggesting good overall performance.<br>

Accuracy: Overall, the model achieves an accuracy of 0.99, meaning it correctly predicts 99% of all cases.<br>

Interpretation<br>

Based on the classification report, the logistic regression model performs exceptionally well in predicting both healthy and risky loans. It is particularly strong at identifying healthy loans, with near-perfect precision and recall. While it's slightly less accurate in predicting risky loans, it still maintains a high level of performance.