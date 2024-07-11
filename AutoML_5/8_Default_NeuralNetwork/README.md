# Summary of 8_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **num_class**: 6
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5

## Optimized metric
accuracy

## Training time

5.2 seconds

### Metric details
|           |       4.0 |       5.0 |       6.0 |       7.0 |     8.0 |       9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----------:|----------:|----------:|--------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |  0.869565 |  0.952381 |  0.915493 |  0.98     |  0.9875 |  0.979167 |   0.955631 |    0.947351 |       0.957517 |  0.243335 |
| recall    |  1        |  1        |  0.955882 |  0.859649 |  0.9875 |  0.979167 |   0.955631 |    0.9637   |       0.955631 |  0.243335 |
| f1-score  |  0.930233 |  0.97561  |  0.935252 |  0.915888 |  0.9875 |  0.979167 |   0.955631 |    0.953941 |       0.955357 |  0.243335 |
| support   | 20        | 20        | 68        | 57        | 80      | 48        |   0.955631 |  293        |     293        |  0.243335 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 20 |                  0 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  0 |                 20 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 6.0 |                  1 |                  1 |                 65 |                  0 |                  1 |                  0 |
| Labeled as 7.0 |                  1 |                  0 |                  6 |                 49 |                  0 |                  1 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  1 |                 79 |                  0 |
| Labeled as 9.0 |                  1 |                  0 |                  0 |                  0 |                  0 |                 47 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
