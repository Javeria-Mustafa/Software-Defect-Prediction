**Software Defect Prediction Using PCA Feature Selection:**
This project aims to improve the accuracy of software defect prediction models by applying Principal Component Analysis (PCA) to select the most important features before training.
By reducing redundant or less important features, we can:

Increase prediction accuracy

Reduce training time

Improve model generalization

Methodology
Load Dataset – Import software defect dataset.

Preprocessing – Normalize features for better model performance.

Feature Selection with PCA – Select top contributing features based on variance.

Model Training – Train and compare multiple ML models:

Random Forest

Logistic Regression

Linear SVM

Evaluation – Measure accuracy and compare results before and after PCA.

Tools & Technologies
Language: Python

Libraries: Pandas, Matplotlib, scikit-learn

Models: PCA, Random Forest, Logistic Regression, Linear SVM

OS: Windows

Result: Random Forest with PCA-selected features achieved the highest accuracy compared to other tested models.
