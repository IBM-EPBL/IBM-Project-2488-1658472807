*SPRINT-2 : FUEL CONSUMPTION PREDICTION APPLICATION*

      Code Upload in github completed
      User Acceptance Testing Document for sprint-1: Completed

FOCUS ELEMENTS: 

1. Fuel prediction model using Decision tree Regression
2. Fuel prediction model using SVR
3. Fuel prediction model using Lasso Regression
4. Fuel prediction model using Random Forest Regression

Pre-process the data : 
	The dataset is downloaded from the link provided by IBM. Then, the libraries required for the given model is imported. After that, Null values are identified and removed. They are replaced by their mean values.

Splitting data into train and test:
	Initially, the independent and dependent variables are separated. Then, the dataset is split into train and test set in the ratio of 70-30.
Implementing ML algorithms:
	Various Machine Learning Regression algorithms like Support Vector Regression and Lasso Regression are implemented in order to get the accurate prediction

Model building:
	The ML model with the best regression algorithm is created and the model is trained.

Application building:
	Here, we have to import the flask module in our project. Next, a form is created using HTML to get values from the users and display the fuel consumption predicted as the output.

