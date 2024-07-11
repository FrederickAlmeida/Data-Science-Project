# Summary of 119_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: entropy
- **max_features**: 0.7
- **min_samples_split**: 30
- **max_depth**: 7
- **eval_metric_name**: accuracy
- **num_class**: 6
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5

## Optimized metric
accuracy

## Training time

12.5 seconds

### Metric details
|           |       4.0 |   5.0 |       6.0 |       7.0 |   8.0 |       9.0 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|------:|----------:|----------:|------:|----------:|-----------:|------------:|---------------:|----------:|
| precision |  0.952381 |     1 |  0.984615 |  0.948276 |     1 |  0.979592 |   0.979522 |    0.977477 |       0.979773 |  0.156844 |
| recall    |  1        |     1 |  0.941176 |  0.964912 |     1 |  1        |   0.979522 |    0.984348 |       0.979522 |  0.156844 |
| f1-score  |  0.97561  |     1 |  0.962406 |  0.956522 |     1 |  0.989691 |   0.979522 |    0.980705 |       0.979463 |  0.156844 |
| support   | 20        |    20 | 68        | 57        |    80 | 48        |   0.979522 |  293        |     293        |  0.156844 |


## Confusion matrix
|                |   Predicted as 4.0 |   Predicted as 5.0 |   Predicted as 6.0 |   Predicted as 7.0 |   Predicted as 8.0 |   Predicted as 9.0 |
|:---------------|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
| Labeled as 4.0 |                 20 |                  0 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 5.0 |                  0 |                 20 |                  0 |                  0 |                  0 |                  0 |
| Labeled as 6.0 |                  1 |                  0 |                 64 |                  3 |                  0 |                  0 |
| Labeled as 7.0 |                  0 |                  0 |                  1 |                 55 |                  0 |                  1 |
| Labeled as 8.0 |                  0 |                  0 |                  0 |                  0 |                 80 |                  0 |
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
