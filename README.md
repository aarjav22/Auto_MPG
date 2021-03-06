# Auto-MPG

## Regression model to predict the Miles Per Gallon of a car

&nbsp; &nbsp; &nbsp; &nbsp;

## Table of Contents

1.	Introduction
2.	Python libraries
3.	The problem statement
4.	Linear Regression
5.	Independent and dependent variable
6.	Multiple Linear Regression (MLR)
7.	About the dataset
8.	Exploratory data analysis
9.	Interpretation and conclusion


&nbsp; &nbsp; &nbsp; &nbsp;

## 1.	Introduction

In this notebook, I build Regression model to study the relationship between miles per gallon of a car with different continous and discrete attributes. I implemented this regression model in Python programming language using Scikit-learn,numpy,seaborn,matplotlib and model accuracy is based on cross validation result.

&nbsp; &nbsp; &nbsp; &nbsp;

## 2.	Python libraries

 •	Numpy
 
 •	Pandas

 •	Matplotlib
 
 •	Seaborn
 
 •	Scikit-Learn

&nbsp; &nbsp; &nbsp; &nbsp;

## 3.	The problem statement

The main aim of this model is to predicting the miles per gallon of a car using some continous and discrete variable data. Finding relationship or dependency of MPG on attrubutes like weight , Number of Cylinders and many more. The accuracy of the model is defined by mean squared error value and cross validation Score. The notebook contain the linear and polynomial regression model for data.

&nbsp; &nbsp; &nbsp; &nbsp;

## 4.	Linear Regression

Linear Regression is a statistical technique which is used to find the linear relationship between dependent and one or more independent variables. This technique is applicable for Supervised Learning Regression problems where we try to predict a continuous variable.
Linear Regression can be further classified into two types – Simple and Multiple Linear Regression. In this project, I employ Multiple Polynomial Regression technique where I have Multiple independent and one dependent variable.

&nbsp; &nbsp; &nbsp; &nbsp;

## 5.	Independent and Dependent Variables

### Independent variable

Independent or Input variable (X) = Feature variable = Predictor variable 

The following are the independent variable:-

    1. cylinders:     multi-valued discrete
    2. displacement:  continuous
    3. horsepower:    continuous
    4. weight:        continuous
    5. acceleration:  continuous
    6. model year:    multi-valued discrete
    7. origin:        multi-valued discrete
    8. car name:      string (unique for each instance)

### Dependent variable

Dependent or Output variable (y) = Target variable = Response variable

The following is the dependent variable:-
 
    1. mpg:           continuous

&nbsp; &nbsp; &nbsp; &nbsp;

## 6.	Multiple Linear Regression (MLR)

Multiple Linear Regression also known simply as multiple regression is a statistical technique that uses several explanatory variables to predict the outcome or the response variable.
The goal of multiple linear regression is to model the linear relationship between the explanatory variable (independent variable) and response variable.

The formula for Multiple Regression is:
	     		
		y = a0 + a1x1 + a2x2 + ...............

where
  y = dependent variable
  xi= independent variable
  a0= y-intercept
  ai= slope coefficients for each independent variable

&nbsp; &nbsp; &nbsp; &nbsp;

## 7.	About the dataset

    1. Title: Auto-Mpg Data

    2. Sources:
       (a) Origin:  This dataset was taken from the StatLib library which is
                    maintained at Carnegie Mellon University. The dataset was 
                    used in the 1983 American Statistical Association Exposition.
       (c) Date: July 7, 1993

    3. Relevant Information:
  
       This dataset is a slightly modified version of the dataset provided in
       the StatLib library.  In line with the use by Ross Quinlan (1993) in
       predicting the attribute "mpg", 8 of the original instances were removed 
       because they had unknown values for the "mpg" attribute.  The original 
       dataset is available in the file "auto-mpg.data-original".

       "The data concerns city-cycle fuel consumption in miles per gallon,
        to be predicted in terms of 3 multivalued discrete and 5 continuous
        attributes." (Quinlan, 1993)

&nbsp; &nbsp; &nbsp; &nbsp;

## 8.	Exploratory data analysis

To summarize the main characteristics of data and finding the patterns I use plots to analysed it using Data Visualization by ploting graphs of univariate, bivariate to find the distribution of particulat attribute and the relationship between the dependent and independent attribute by using plots like regression plot ,box plot ,histogrames, and distribution plot.It help me in finding the good attributes and bad attributes for training my model as graph clearly shows us the reationship between the variables. 

&nbsp; &nbsp; &nbsp; &nbsp;

## 9.	Interpretation and Conclusion

Linear Regression:
	
     MSE value: 0.1764742397827893
     
     Accuracy Score : 0.8313833993698124
     
     cross validation score: 0.5906438717928257

Polynomial Regression: 

     MSE value: 6.887827289424193
     
     Accuracy Score : 0.8317803894705068

     cross Validation score: 0.4403178468015085
     
After looking at the scores like accuracy score ,mean squared error and cross validation score we can conclude that polynomial regression has a little edge on accuracy score but cross validation score and mean squared score of linear regression are much better then that of polynomial regression so we conclude that linear regression fit the data much better as compair to polynomial regression. 

&nbsp; &nbsp; &nbsp; &nbsp;