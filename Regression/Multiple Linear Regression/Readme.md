# What Is Multiple Linear Regression (MLR)?

Multiple linear regression (MLR), also known simply as multiple regression, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. The goal of multiple linear regression (MLR) is to model the linear relationship between the explanatory (independent) variables and response (dependent) variable.

In essence, multiple regression is the extension of ordinary least-squares (OLS) regression that involves more than one explanatory variable.

# What Multiple Linear Regression (MLR) Can Tell You.

Simple linear regression is a function that allows an analyst or statistician to make predictions about one variable based on the information that is known about another variable. Linear regression can only be used when one has two continuous variables—an independent variable and a dependent variable. The independent variable is the parameter that is used to calculate the dependent variable or outcome. A multiple regression model extends to several explanatory variables.

![image](https://user-images.githubusercontent.com/55452866/88674390-618f9f00-d107-11ea-9426-8ea99f740c53.png)


The multiple regression model is based on the following assumptions:

(1)There must be a linear relationship between the outcome variable and the independent variables.  Scatterplots can show whether there is a linear or curvilinear relationship.

(2)Multivariate Normality–Multiple regression assumes that the residuals are normally distributed.

(3)No Multicollinearity—Multiple regression assumes that the independent variables are not highly correlated with each other.  This assumption is tested using Variance Inflation Factor (VIF) values.

(4)Homoscedasticity–This assumption states that the variance of error terms are similar across the values of the independent variables.  A plot of standardized residuals versus predicted values can show whether points are equally distributed across all values of the independent variables.

(5)Multiple linear regression requires at least two independent variables, which can be nominal, ordinal, or interval/ratio level variables.  A rule of thumb for the sample size is that regression analysis requires at least 20 cases per independent variable in the analysis. Learn more about sample size here.

# Steps used un the Notebook:
(1)Importing the Library.

(2)Importing and Exploring the dataset.

(3)Dividing the dataset into labels and target.

(4)Encoding the categorial label.

(5)Training the Model.

(6)Predicting the results.
