# PIMA_Indian_Diabetes_DataSet

In this particular project, a number of models was optimized using grid searching to arrive at an optimal result.
The models used are SVM, Adaboost and RandomForest.
Although the approach used was  time consuming (to test all the possible hyperparameter combinations) to find the best models, it did optimize well.

Because of data imbalance, f1 score was used as performance metric. Adaboost performed best. I was able to see that Glucose level BMI and Age had strong correlations to having diabetes, unsurprisingly.
There 768 observations and only 35% had diabetes.