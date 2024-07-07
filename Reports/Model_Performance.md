# Model Performance Report

## Logistic Regression

|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 0.99              | 0.96          |      0.98          |
| 1          | 0.90               | 0.96           |      0.93           |
|            |                   |               |                   |
| Accuracy   |                                                0.96   |


## Support Vector Machine (SVM)
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 0.98               | 0.99           |       0.98          |
| 1          | 0.96              | 0.93           |      0.95           |
|            |                   |               |                   |
| Accuracy   |                                               0.9727   |


## Random Forest
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 0.98               | 0.98          |       0.98          |
| 1          | 0.93               | 0.93           |      0.93           |
|            |                   |               |                   |
| Accuracy   |                                                0.9636   |


## K-Nearest Neighbors (KNN)
|            | Precision         |       Recall  |    F1- Score      |
|------------|-------------------|---------------|-------------------|
| 0          | 0.94              | 0.95           |       0.95          |
| 1          | 0.85               | 0.82           |      0.84           |
|            |                   |               |                   |
| Accuracy   |                                               0.9181  |


## Model Performance Comparison

| Model                          | Training Accuracy | Test Accuracy |
|--------------------------------|-------------------|---------------|
| Support Vector Machine (SVM)   | 96%               | 97%           |
| Logistic Regression            | 98%               | 96%           |
| Random Forest                  | 1              | 96%           |
| K-Nearest Neighbors (KNN)      | 1               | 92%           |


After comparing all the techniques, we could observe that when we apply support vector 
machine, it could achieve 97% accuracy on our test set. Therefore, we can conclude that SVM 
technique good for our dataset.
By evaluating our SVM model as the best model, we can plot the ROC curve. The figure below 
illustrates the ROC curve for the SVM model.
<p align="center">
 <img src="ROC curve for SVM.png" width=500 height=350>
</p>
According to the above figure, the curve is very close to the top left corner of the plot. This indicates 
that the classifier has a high True Positive Rate and a low False Positive Rate. Also, it has an Area 
Under Curve (AUC) value of 0.99390. Considering the AUC and the ROC curve, we can conclude that 
the classifier is highly effective at distinguishing between the positive and negative classes
