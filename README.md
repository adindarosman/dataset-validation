# Dataset-validation
Validate the dataset using K-Folds Cross and choose the best algorithm model for a Haberman's Survival dataset
## Description of Project Files
- README.md : A file containing an overview, summary and description of the entire Project.
- Dataset_Validation.ipynb : A python notebook which contains all the code used in performing the Validation.
## Overview Of The Project
Evaluation is used to estimate the accuracy of previously unknown data. There are several models that can be used in the evaluation of the algorithm, namely; K-Nearest Neighbors (KNN), Gaussian Naive Bayes (NB), Support Vector Machines (SVM), Quadratic Discriminant Analysis (QDA), and Extra Trees Classifier (ETC). This validation is done to find out that the model made is good. In this project, I used statistical methods to estimate the accuracy of the models created on invisible data. It is also desirable to have a more concrete estimate of the accuracy of the rising model on the invisible data by evaluating the actual invisible data. I'm withholding some data that the algorithm can't see and will use this data to get information about how accurate the best model really is. I split the loaded dataset into two, 80% of which will be used to train the model and 20% used for validation data.
