# Model Performance Report

## Logistic Regression

|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 97%               | 97%           |       88          |
| 1          | 96%               | 96%           |      88           |
|            |                   |               |                   |
| Accuracy   |                                                0.96   |


## Support Vector Machine (SVM)
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 97%               | 97%           |       88          |
| 1          | 96%               | 96%           |      88           |
|            |                   |               |                   |
| Accuracy   |                                                0.96   |


## Random Forest
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 97%               | 97%           |       88          |
| 1          | 96%               | 96%           |      88           |
|            |                   |               |                   |
| Accuracy   |                                                0.96   |


## K-Nearest Neighbors (KNN)
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 97%               | 97%           |       88          |
| 1          | 96%               | 96%           |      88           |
|            |                   |               |                   |
| Accuracy   |                                                0.96   |


## Model Performance Comparison

| Model                          | Training Accuracy | Test Accuracy |
|--------------------------------|-------------------|---------------|
| Support Vector Machine (SVM)   | 97%               | 97%           |
| Logistic Regression            | 96%               | 96%           |
| Random Forest                  | 96%               | 96%           |
| K-Nearest Neighbors (KNN)      | 92%               | 92%           |


After comparing all the techniques, we could observe that when we apply support vector 
machine, it could achieve 97% accuracy on our test set. Therefore, we can conclude that SVM 
technique good for our dataset.
By evaluating our SVM model as the best model, we can plot the ROC curve. The figure below 
illustrates the ROC curve for the SVM model.

<img src>    </img>

According to the above figure, the curve is very close to the top left corner of the plot. This indicates 
that the classifier has a high True Positive Rate and a low False Positive Rate. Also, it has an Area 
Under Curve (AUC) value of 0.99390. Considering the AUC and the ROC curve, we can conclude that 
the classifier is highly effective at distinguishing between the positive and negative classes
