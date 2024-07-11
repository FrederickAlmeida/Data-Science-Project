# Summary of 59_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 64
- **dense_2_size**: 32
- **learning_rate**: 0.08
- **num_class**: 6
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5

## Optimized metric
accuracy

## Training time

4.4 seconds

### Metric details
|           |       4.0 |       5.0 |       6.0 |       7.0 |       8.0 |       9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----------:|----------:|----------:|----------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |  0.909091 |  0.952381 |  0.969697 |  0.941176 |  0.938272 |  0.923077 |    0.94198 |    0.938949 |       0.942612 |  0.249153 |
| recall    |  1        |  1        |  0.941176 |  0.842105 |  0.95     |  1        |    0.94198 |    0.955547 |       0.94198  |  0.249153 |
| f1-score  |  0.952381 |  0.97561  |  0.955224 |  0.888889 |  0.944099 |  0.96     |    0.94198 |    0.946034 |       0.941262 |  0.249153 |
| support   | 20        | 20        | 68        | 57        | 80        | 48        |    0.94198 |  293        |     293        |  0.249153 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 20 |                  0 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  0 |                 20 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 6.0 |                  2 |                  1 |                 64 |                  0 |                  1 |                  0 |
| Labeled as 7.0 |                  0 |                  0 |                  2 |                 48 |                  4 |                  3 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  3 |                 76 |                  1 |
| Labeled as 9.0 |                  0 |                  0 |                  0 |                  0 |                  0 |                 48 |

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
