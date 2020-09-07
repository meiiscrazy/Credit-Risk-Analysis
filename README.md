# Credit-Risk-Analysis

The goal is to predict credit risk by using machine learning algorithims and apply it to an imbalanced dataset. The dataset had 68470 low risk loans and 347 high risk loans so we needed to create a model that would best fit our dataset. Because our dataset is uneven we need to first reasmple the data to produce more accurate predictions. We used random oversampling, smote oversampling, cluster centroid undersampling, smoteen sampling, balanced random forest, and easy ensemble to compare accuracy scores. Every model except for the Easy Ensemble model had very low precision scores, varying from 0.01 to 0.02. It also had very similar recall percentages varying around 70%. 

Out of all the models I would choose the Easy Ensemble AdaBoost Classifier as it provides the best balanced accuracy score, recall, and precision score. Let's compare the F1 scores for the Easy Ensemble AdaBoost. For high risk loans the F1 score is 0.97 while the F1 score for low risk loans is 0.16. The close the F1 score is to 1 the better the accuracy and precision. The other models have much lower F1 scores which proves that the Easy Ensemble AdaBoost Classifier is best suited for our needs.

### Random Oversampling

High Risk - Precision: 0.02, Recall: 0.72, Balanced Accuracy: 0.703
Low Risk - Precision: 1, Recall: 0.73

### SMOTE Oversampling

High Risk - Precision: 0.02, Recall: 0.73, Balanced Accuracy: 0.730
Low Risk - Precision: 1, Recall: 0.73

### Cluster Centroid Undersampling

High Risk - Precision: 0.01, Recall: 0.76, Balanced Accuracy: 0.712
Low Risk - Precision: 1, Recall: 0.66

### SMOTEEN Combination Sampling

High Risk - Precision: 0.02, Recall: 0.75, Balanced Accuracy: 0.740
Low Risk - Percision: 1, Recall: 0.73

### Balanced Random Forest w/ Random Oversampling

High Risk - Precision: 0.01, Recall: 0.74, Balanced Accuracy: 0.703
Low Risk - Precision: 1, Recall: 0.66

### Easy Ensemble AdaBoost Classifier

High Risk - Precision: 0.09, Recall: 0.92, Balanced Accuracy: 0.932
Low Risk - Precision: 1, Recall: 0.94