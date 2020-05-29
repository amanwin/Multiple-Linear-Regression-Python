## Multiple Linear Regression Model
In this we will see the generic steps that are required to build a multiple linear regression model. We will build this model for a housing dataset and predict the price of a house using the various potential predictor variables provided. We will first read and visualise your dataset and then prepare your data for building a linear model. This will include dealing with categorical variables, adding dummy variables, and scaling. We will then start building the model with a bottom-up approach, i.e., we will start with one variable and keep on adding more. Once all the variables have been added, you will perform a manual feature elimination and move on to the residual analysis and predictions, as usual. In the end, we will solve the same problem using RFE.

## Reading and Understanding the Data
Linear regression is used in various fields such as real estate, telecom, e-commerce, etc. to build predictive models. Let's look at one such example from the real-estate industry. Here, you will predict the price of a house on the basis of some predictor variables, such as floor area, number of bedrooms, parking space, etc.

### Problem Statement:
Consider that a real estate company has the data of real-estate prices in Delhi. The company wants to optimise the selling price of the properties, based on important factors such as area, bedrooms, parking, etc.

Essentially, the company wants:
* To identify the variables affecting house prices, e.g., area, number of rooms, bathrooms, etc.
* To create a linear model that quantitatively relates house prices with variables, such as the number of rooms, area, number of bathrooms, etc.
* To know the accuracy of the model, i.e. how well do these variables predict the house prices

Please download the dataset from below:

[Housing Dataset](Housing.csv)

[Multiple Linear Regression](MultipleLinearRegression.ipynb)
