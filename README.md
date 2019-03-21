INTRODUCTION

According to the management consulting company Bain & Co., reducing customer churn by 5% can almost double profits. Thus, keeping churn low or loyalty high is for many companies one of the top ten KPI’s (Key Performance Indicators).

Churn analytics is seriously hard. Do you know your churn? How to calculate churn? What defines a customer being lost? What’s your customer retention? Reducing churn by 5% sounds easy? Are all customers equal? What’s our CLTV (Customer life-time value)? Does loyalty pay off for us (cohort analysis)?

In my experience, this part of the analysis is best done in Tableau. 

Customer churn prediction is where we apply Machine Learning algorithms to predict which customers might leave. With the help of an expert, I show you a trick how you can embed a binary-classification algorithm directly into Tableau. No coding skills are required. The algorithm part is challenging as well and I will make it even more challenging by integrating a Machine Learning algorithm directly into Tableau. More work, but I merge Tableau and Machine Learning together so we have an end-to-end analytics solution, which works real-time.

I will also show you some tricks in Churn Prediction: error handling in Tableau, Kaggle tricks to deal with MAR/MCAR, when to use mean and mode for imputation, how to label outliers in Pandas based on Tukey’s 1.5 IQR rule, how to deal with linear and non-linear challenges, how to avoid overfitting a Decision Tree with max_leaf_nodes and how to visualize a Decision Tree in graphviz and translate the prediction into a Tableau Calculated Field.

I’m working with one company, which aims to increases revenues by EUR 42 million per year through Churn Prediction. If their profit margin is 25% and their P/E Ratio (Price Earnings Ratio) is 20, the company creates around EUR 200 million-shareholder value.

The potential output is considerable, but so are the requirements. This is going to be technical in terms of Tableau with advanced LOD’s (Level Of Detail), Machine Learning algorithms and statistics.

Fasten your seat belts.

Franco Arda, 

Frankfurt, January 2019
