# Predictive Modeling for Early Heart Disease Detection
Heart disease is one of the leading causes of death in the United States. This project deals with the creation of a predictive model for early heart disease detection using the Cleveland Heart Disease dataset.
## Main
The main file that should be executed is the [Machine_learning.ipynb](https://github.com/Madhav4487/Predictive-modeling-for-early-heart-disease-detection/blob/main/Machine_learning_project.ipynb) file. This file format was chosen so that the code could be executed in subsections in a collaborative environment. 
## Dataset
The dataset that was used to trained the model is the []() dataset. This dataset contains 1024 samples, each having 14 features that deal with diagnosing heart disease:
1. Age
2. Sex
3. Chest Pain
4. Trest Blood Pressure
5. Cholesterol
6. Fasting Blood Sugar
7. Rest Electrocardiograph
8. Thalach
9. Exercised Induced Angina
10. Old Peak (ST depression induced by exercise relative to rest)
11. Slope (slope of the peak exercise ST segment)
12. CA (number of major vessels [0-3] colored by fluoroscopy)
13. Thal
14. Target

To use the `heart.csv`, make sure it resides in the directory path: `/content/drive/MyDrive/heart.csv` . This is to ensure that the code runs correctly and pulls from the correct dataset.

## Methods
In the main file, we created multiple graphs to visualize the data. Functions were called to compute F1-Scores, Precision scores, Recall scores, and Support scores. However, the bulk of the research was dedicated to determining the best classifier to use for the model. Seven different classifiers were tested to see which provided the best accuracy score. The ROC-AUC curves were calculated and graphed as well.

## Results
Here is the following average scores for the respective classifier that was investigated:
```
Model                          Accuracy (%)
----------------------------------------------------------------
Logistic Regression :          84.87
GaussianNB:                    84.87
Random Forest:                 95.12
eXtreme Gradient Boosting:     91.70
k-Nearest Neighbor:            88.29
Decision Tree:                 94.63
Support Vector Machine:        99.02
```

The Support Vector Machine was determined to be the best based on the accuracy of the model.
