# Lab 2.
### Variant 1.

#### Done by Kitili Mark Mwendwa M10-414Bki-19.

In this laboratory, I solved the problem of determining the malignancy of the tumor.

I developed a pipeline responsible for preprocessing the source data
I also developed a pipeline that implements the training of various models, namely:
   logistic regression, support vector machine (SVM), KNN, naive Bayesian classifier, random forest
 Next, cross-validation was carried out in order to find the best hyperparameters, the best hyperparameters for each model were saved in the files ``<model>_params.txt ``, and the trained models themselves are in the files ``<model>.pkl``,Next, the estimates of the obtained models were compared, according to which the leading model can be considered based on the SVM method.
In the course of the work, models were built, the maximum accuracy of which is about 97%. For a model whose field of application is medicine, this accuracy is insufficient. The relatively low accuracy is mainly due to the small size of the dataset.
