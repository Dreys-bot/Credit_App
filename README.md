# Credit_App
In this repository, we will try to build a simulation credit prediction model based on the Convolutional Neural Networks architecture.
The dataset were dowloaded on kaggle website.

## Preparing the datasets
Our goal was to predict whether a third party's credit application will be accepted by the bank based on that person's data.

For that, we must prepare the data before using it.

First download the train dataset from [ here ](https://github.com/Dreys-bot/Credit_App) and unpack it.

In order to process your data properly, it is necessary to separate categorical data from numerical data.

This separation will allow us to recover all the missing values. Because of the high number of missing data, we cannot delete them. Thus, the missing data among the non-numeric ones will be replaced by the data that has the most occurrences of the column and the numeric ones will be replaced by the value that precedes them.

In order to do this cleaning, we normalize our data by replacing the categorical data with 0 or 1.

In our case we have:

Married: 
-yes: 0

-No: 1

Education:
 -Graduated: 0
 
 -Not graduated:1

Credit_History:
  -Yes: 1
  
  -No: 0 

# Exploratory Analysis

The aim here is to observe the data that influence the result by visualizing them.
We use some python libraries like matplotlib, seaborn.

![image](https://github.com/Dreys-bot/Credit_App/blob/master/viz_data1.png)


![image](https://github.com/Dreys-bot/Credit_App/blob/master/viz_data2.png)

# Training and deployment of model

The aim is to create our model.

At first, we use three model to see the performance of each.

In relation to the skills, we notice that the regression model is the most efficient.

For this reason, we have continued the trainings based on the regression model.

![image](https://github.com/Dreys-bot/Credit_App/blob/master/model.png)


For the deployment, we created our application on pycharm using html, css, flask.

We also imported our model in the application in order to obtain the results.

![image](https://github.com/Dreys-bot/Credit_App/blob/master/app.png)




