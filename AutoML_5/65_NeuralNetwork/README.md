# Summary of 65_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 16
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

5.0 seconds

### Metric details
|           |       4.0 |       5.0 |       6.0 |       7.0 |       8.0 |       9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----------:|----------:|----------:|----------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |  0.740741 |  1        |  0.871429 |  0.844828 |  0.962025 |  0.979592 |   0.901024 |    0.899769 |       0.908565 |  0.334486 |
| recall    |  1        |  0.5      |  0.897059 |  0.859649 |  0.95     |  1        |   0.901024 |    0.867785 |       0.901024 |  0.334486 |
| f1-score  |  0.851064 |  0.666667 |  0.884058 |  0.852174 |  0.955975 |  0.989691 |   0.901024 |    0.866605 |       0.897705 |  0.334486 |
| support   | 20        | 20        | 68        | 57        | 80        | 48        |   0.901024 |  293        |     293        |  0.334486 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 20 |                  0 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  3 |                 10 |                  5 |                  2 |                  0 |                  0 |
| Labeled as 6.0 |                  3 |                  0 |                 61 |                  3 |                  1 |                  0 |
| Labeled as 7.0 |                  1 |                  0 |                  4 |                 49 |                  2 |                  1 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  4 |                 76 |                  0 |
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
