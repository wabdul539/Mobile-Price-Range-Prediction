# Mobile-Price-Range-Prediction
predicting the price range for mobile based on its features.
Mobile now a days is one of the most selling and purchasing device. Every day new mobiles with new version and more features are launched. In this competitive mobile phone market, companies want to understand the sales data of the mobile phones and factors that drive the prices.

The objective is to find out some relation between features of a mobile phone (eg :- RAM, Internal Memory etc) and its selling price.
Further, based on different features of the mobile phones, develop a model that would classify each mobile into different categories of price range i.e. into categorical values of 0(low), 1(moderate), 2(high), and 3(very high).

As this was a multiclass classification problem and the data set was very well balanced across all output class, Accuracy was a good parameter to evaluate our models.
In addition to Accuracy, also calculated F1 scores across each output class to get overall picture.
Based on the evaluation metrics(Accuracy, Precision, Recall, F1 score)of the train and test data, can conclude that Logistic Regression(93%) and XGBoost(93.25%) performed well among all models whereas KNN(61.75%) performed worst. XGBoost is our goto model since it performed well and is non parametric in nature for final model selection.
Completed this exhaustive study to develop a model for mobile price ranges based on its features This model can help us in doing market research, competitive price estimates, and mobile phone’s Price vs Features comparisons. 


