
# Predicting Customer Satisfaction of Invistico Airline

In this project, we will build a random forest model for an Airline. Here, we will train, tune, and evaluate a random forest model using data from a spreadsheet of survey responses from 129,880 customers. It includes data points such as class, flight distance, and inflight entertainment. A random forest model will predict whether a customer will be satisfied with their flight experience.


## Business Understanding

 The main aim of the project is to find important features affecting customer satisfaction. Once our model predicts these features then the stakeholders can decide on where to focus to improve customer satisfaction.

## Data Understanding 

Dataset --> [Invistico_Airline.csv](https://github.com/Sathyam-Kakodkar/Customer-Satisfaction/blob/main/Invistico_Airline.csv)

The data consists of 129880 rows and  22 columns. The target variable is named "satisfaction" which has an object datatype


## Modeling and Evaluation

Since this is a classification model we have used RandomForestClassifier to construct a model.

<pre>
Instantiate model
rf = RandomForestClassifier(random_state=0)   
</pre>

Precision_score, recall_score and accuracy_score are used as evaluation metrics for evaluating the model.

## Conclusion

A random forest model comprising 50 decision trees was used to determine feature importance for predicting customer satisfaction . The below plot shows that Inflight entertainment, Seat comfort and Ease of Online booking were the Top 3 most important factors in determining satisfaction. The overall model performed with 94.2% accuracy, recall 94.5% and 95% precision.

![Feature Importance](https://github.com/Sathyam-Kakodkar/Customer-Satisfaction/blob/main/Feature%20Importance%20for%20Customer%20Satisfaction.png)


