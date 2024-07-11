# Summary of 1_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 3
- **num_class**: 6
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5

## Optimized metric
accuracy

## Training time

2.6 seconds

### Metric details
|           |       4.0 |       5.0 |       6.0 |       7.0 |       8.0 |   9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----------:|----------:|----------:|----------:|------:|-----------:|------------:|---------------:|----------:|
| precision |  0.866667 |  0.666667 |  0.712644 |  0.810811 |  0.814433 |     1 |   0.812287 |    0.81187  |       0.813984 |  0.765252 |
| recall    |  0.65     |  0.3      |  0.911765 |  0.526316 |  0.9875   |     1 |   0.812287 |    0.729263 |       0.812287 |  0.765252 |
| f1-score  |  0.742857 |  0.413793 |  0.8      |  0.638298 |  0.892655 |     1 |   0.812287 |    0.747934 |       0.796343 |  0.765252 |
| support   | 20        | 20        | 68        | 57        | 80        |    48 |   0.812287 |  293        |     293        |  0.765252 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 13 |                  3 |                  4 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  0 |                  6 |                 12 |                  2 |                  0 |                  0 |
| Labeled as 6.0 |                  2 |                  0 |                 62 |                  4 |                  0 |                  0 |
| Labeled as 7.0 |                  0 |                  0 |                  9 |                 30 |                 18 |                  0 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  1 |                 79 |                  0 |
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
