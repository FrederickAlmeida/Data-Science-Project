# Summary of 11_Default_NearestNeighbors

[<< Go back](../README.md)


## k-Nearest Neighbors (Nearest Neighbors)
- **n_jobs**: -1
- **n_neighbors**: 5
- **weights**: uniform
- **num_class**: 6
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5

## Optimized metric
accuracy

## Training time

2.7 seconds

### Metric details
|           |       4.0 |       5.0 |       6.0 |       7.0 |     8.0 |       9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----------:|----------:|----------:|--------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |  0.869565 |  0.869565 |  0.941176 |  0.925926 |  0.9625 |  1        |    0.94198 |    0.928122 |       0.943892 |  0.261397 |
| recall    |  1        |  1        |  0.941176 |  0.877193 |  0.9625 |  0.9375   |    0.94198 |    0.953062 |       0.94198  |  0.261397 |
| f1-score  |  0.930233 |  0.930233 |  0.941176 |  0.900901 |  0.9625 |  0.967742 |    0.94198 |    0.938797 |       0.942021 |  0.261397 |
| support   | 20        | 20        | 68        | 57        | 80      | 48        |    0.94198 |  293        |     293        |  0.261397 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 20 |                  0 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  0 |                 20 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 6.0 |                  3 |                  0 |                 64 |                  1 |                  0 |                  0 |
| Labeled as 7.0 |                  0 |                  2 |                  4 |                 50 |                  1 |                  0 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  3 |                 77 |                  0 |
| Labeled as 9.0 |                  0 |                  1 |                  0 |                  0 |                  2 |                 45 |

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