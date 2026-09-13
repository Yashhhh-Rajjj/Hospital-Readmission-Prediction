# Hospital Readmission Prediction

## Case Study 1 - MLE CA1

### Objective

Predict whether a patient will be readmitted to the hospital within 30 days.

### Dataset

Diabetes 130-US Hospitals dataset.

### Model

Logistic Regression with L2 regularization.

### Features Used

- Diagnosis codes
- Time in hospital
- Number of laboratory procedures
- Previous outpatient visits
- Previous emergency visits
- Previous inpatient visits

### Evaluation Metric

ROC-AUC

### Result

ROC-AUC: **0.634**

### Clinical Cost

False negatives are important because they represent patients who were
actually readmitted but were not identified by the model.

Missing a high-risk patient can result in delayed follow-up or additional
healthcare costs. Therefore, reducing false negatives is important in
hospital readmission prediction.
