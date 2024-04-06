# Question 1: How can I measure the performance of my model?
## Evaluating the Performance of Machine Learning Models

Measuring the performance of a machine learning model is crucial for understanding its effectiveness in solving a particular problem. The choice of performance metrics depends on the type of problem we are trying to address. Here are some commonly used metrics:

1. **Classification Problems**:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Area Under the ROC Curve (AUC)

2. **Regression Problems**:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R-Squared

In addition to these standard metrics, it's essential to evaluate our model's performance on different subsets of our data, known as data slices. This helps ensure that our model performs well across all segments of our data and helps remove bias.

Furthermore, real-world impact metrics can be defined to measure how changes in our model affect user experience or other real-world factors.

The selection of the appropriate metric(s) depends on our specific problem and the business context. For instance, in some cases, precision (avoiding false positives) might be more important than recall (finding all the positives), or vice versa.

Lastly, continuous monitoring of our model's performance over time is crucial, as data distribution and performance can shift. This helps in identifying any degradation in the model's performance and taking necessary actions, such as re-training the model.


## ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Question 2: What are: Accuracy, Confusion Matrix, Precision, Recall & F1 Score, ROC & AUC. Log Loss?
## Understanding Model Performance Metrics

Measuring the performance of a machine learning model is crucial for assessing its effectiveness and suitability for solving a particular problem. Here are some common metrics and techniques used to evaluate model performance:

### Accuracy
- **Definition:** Accuracy measures the ratio of correct predictions to the total number of predictions.
- **Use:** It provides a general overview of the model's performance but may not be suitable for imbalanced datasets.

### Confusion Matrix
- **Definition:** A confusion matrix is a table summarizing the model's performance, displaying true positives, true negatives, false positives, and false negatives.
- **Use:** It provides a detailed breakdown of the model's predictions.

### Precision, Recall, and F1-Score
- **Precision:** Measures the proportion of true positive predictions out of the total positive predictions.
- **Recall (Sensitivity/True Positive Rate):** Measures the proportion of true positive instances correctly identified by the model.
- **F1-Score:** Harmonic mean of precision and recall, offering a balanced performance metric.

### Receiver Operating Characteristic (ROC) Curve and Area Under the Curve (AUC)
- **ROC Curve:** Graph plotting true positive rate against false positive rate at different classification thresholds.
- **AUC (Area Under the Curve):** Summary metric representing the probability of ranking a positive instance higher than a negative one.

### Log Loss
- **Definition:** Also known as cross-entropy loss, it evaluates the performance of classification models outputting probabilities.
- **Use:** Penalizes false classifications, aiming to minimize the log loss for better model performance.
