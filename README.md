# German-Credit-Risk
Done as a part of Garaje Hackathon (TCS)


## Introduction

This is a classification project that aims for predicting credit risk or in simpler terms will help the companies to predict bad loans. Predicting the credibility of a loan is very useful in the Banking business. Using machine learning will help to decide, whether to approve a loan or not by accounting for the risk value based on historical data.

The data used in this project is obtained from the Kaggle(https://www.kaggle.com/kabure/german-credit-data-with-risk), which gives detailed information about the historical data of loan approved by German banks. The data contains a feature column that provides whether the loan was good or bad.

So this Classification project aims to predict the quality of the loan approved by German banks using various Classification algorithms. The project is structured as follows: starts with the understanding of the data and an exploratory data analysis of it, then followed by feature engineering and preprocessing section, then a section which details the models applied to the data and outcome of various models. Finally concludes the reports by summarising the findings achieved from evaluation metrics of models.

## Summary and Future Insights

The main goal of this project was to predict the Risk factor of loans approved by the German Banks. For this, we had historical data of loans provided by the banks, and we cleaned and preprocessed data to make it useful for our prediction. Then we deployed, the classification algorithm such as Logical Regression with(l1 & l2) and without Regression, K nearest Neighbour method, Random Forest, Gradient Boosting, and finally stacking of Gradient Boosting with Logical regression and KNN. From the analysis of evaluation matrics of these models, we found that logical regression and Stacking of KNN with Gradient Boosting performed well, with around 71% accuracy.

I believe that this model couldn't predict the class of bank loans with 80% or more accuracy is because of the imbalance in the data. The percentage of class 0 in the data is 30%. So as the next step to this project we could try to balance the data with a different technique like Synthetic Minority Oversampling Technique (SMOTE) and Adaptive Synthetic sampling (ADASYN). Another step we can include here to improve our accuracy score by adding additional features useful for prediction. These additional features will be the time taken to return the loan, Bank Balance of the customer. Then a model could predict these classes with more accuracy.

