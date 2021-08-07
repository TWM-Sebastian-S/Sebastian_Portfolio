# Sebastian's Portfolio
Main Projects I've been working in statistics, data science and big data.
------



## [Project 1: Predicting Churn using Gradient Boosting and Logistic Regression](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/README.md)

#### Extract

* Machine Learning Project in Python created to find out the key drivers that lead to churn and predict the customer churn for a Telecom Company.
* The Company has evidence of customer churn and has provided a dataset with certain information regarding their clients.
* Engineered features from the dataset to create models using multiple algorithms on Python and Scikit Learn:
*   Logistic Regression
*   GradientBoosting
* Performed Hyper-parameter tuning.
* Compare the performance of different models using multiple metrics of ROC AUC and Precision Recall Curve.
* I came up with a gradient boosting model with only the strongest features and a solid performance against Logistic Regression.

![ROC Curve](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/ROC%20curve.JPG "ROC Curve") ![Precision Recall Curve](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/Precision%20Recall%20Curve.JPG "Precision Recall Curve")


![Key drivers of churn](https://github.com/TWM-Sebastian-S/Predicting-Churn-using-Gradient-Boosting-and-Logistic-Regression/blob/main/Key%20drivers%20of%20churn.JPG "Key drivers of Churn")



## [Project 2: Expedia Hotel Recomendations](https://github.com/TWM-Sebastian-S/Expedia-Hotel-Recomendations/blob/main/README.md)

### Extract

* Kaggle Competition where I built a Machine Learning Project created to recommend hotels to Expedia's customers.
* Create models using multiple algorithms with hyperparameter tuning.
* Compare the performance of different models using jaccard_score.
* Given that all models tried were performing quite low, I tried several algorithms.
*   Random Forests
*   Naive Bayes
*   Logistic Regression
*   KNN
*   XGBoost
*   Decission Tree
* I created a function to calculate the probability to include in a basket of 5 options and that increased significantly the percentage of accuracy.

![Model Performance Comparison](https://github.com/TWM-Sebastian-S/Expedia-Hotel-Recomendations/blob/main/Model%20Performance%20Comparison.JPG "Model Performance Comparison")



## [Project 3: Walmart Sales Forecasting - Time Series Analysis](https://github.com/TWM-Sebastian-S/Walmart-Sales-Forecast/blob/main/README.md)

### Extract

* Kaggle Competition for time series analysis.
* Machine Learning Project created to forecast sales for Walmart stores and departments using time series analysis.
* Statistical, ARIMA and Random Forest Regression models.
* Compare the performance of different models using RMSE.

![Autocorrelation](https://github.com/TWM-Sebastian-S/Walmart-Sales-Forecast/blob/main/Autocorrelation.JPG "Autocorrelation")
![Model Performance Comparison](https://github.com/TWM-Sebastian-S/Walmart-Sales-Forecast/blob/main/Comparison%20of%20different%20models.JPG "Model Performance Comparison")



## [Project 4: Deep Learning for Adult Income prediction](https://github.com/TWM-Sebastian-S/Deep-Learning-Using-H20-to-predict-Adult-Income/blob/main/README.md)

### Extract

* Deep Learning Project in Python created using H2O to find out the best model to predict if an adult will have an annual income of more or less of 50k.
* UCI Machine Learning Repository dataset. Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using certain conditions.
* Prediction task is to determine whether a person makes over 50K a year.
* I define a grid for hyperparameter that search for the best parameters between activation, epochs and different hidden layers using H2O.
* According to the hyperparameters, H20 built more than 40 different models that I listed for their F1-score descending. The best model was selected with a 0,71 F1.

![name](.JPG "name")

