# Wine-Quality-Prediction
Binary Classification and MultiClassification
Machine Learning is basically a subset of AI, where we can explicitely do programming in computers for making predictions and forecasting. Here, we are predicting the quality of wine on the basis of scale and as well as on categorical basis i.e., good or bad.
Since it is categorical problem i.e., our target variable is categorical in nature so we are using Logistic Regression,Decision Tree,Random Forest,KNN,SVM for prediction.
Data Collection: Data is collected from the kaggle database.
EDA/Preprocessing: Here, NO null value is present over there but there are outliers in the dataset and multicollinearity is also present between the independent variables.But i am not removing them because since it is a prediction problem so for quality prediction there may be some extreme value exists for prediction.
Scaling down is done because we are going to use distance based models here like Logistic Regression,KNN and SVM which are distance based model.
Splitting of data is done by using train-test-split.
Model building step is there in which we are fitting our model and find out which model is giving us best accuracy and best fit model till used.
Evaluation of model is model:So, for evaluating model we are using Accuracy score,Classification report(based on f1 score),Receiver Operating Curve,Cross-val-score(mean score of all accuracy score)
Prediction:After concluidng the best fit model,we are predicting the quality of wine with the best model.
1.Binary Classification: In binary classification we decided some threshold value on the basis of scale i.e., quality upto 6 considered as bad quality wine else it is a good quality wine.On the basis of this concept we are building our model,fitting and predicting the best fit model on the basis of it. As a conclusion it is found that Random Forest is the best classifier model among all in terms of all evaluating parameters.
2.Multiclassification: In this we are stick to the original scale giving in the dataset and wants to observed that impact of that on the accuarcy score and evaluating parameters used.Found that here also Random Forest is best classifier but the accuracy score is very low.
3.Multiclassification 2: In this what we have done inspite of creating individual category we are divding our dataset in certain group of classes and for prediction label them as very bad to premium quality scale.Here also Random Forest done the best job and all evaluating parameters are improved as compared to previously used classes.
Conclusion: Binary classification is the best approach.
            While increasing the classes in the model, the preformanceof the model decreases drastically as seen in point no.13, while putting similar ones in one category gives better performance.
            In all Models RANDOM FOREST is the best fit classifier model.
*All coding part and conclusion mentioned in jupyter notebook attached with proper explanation in each step.
