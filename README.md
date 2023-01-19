# Heart_Disease_Prediction
This project uses a logistic regression model to predict the presence of heart disease in a patient based on various attributes. The model is trained and tested on a dataset containing information about heart disease patients. The dataset is read in using pandas and processed for missing values and statistical measures. The model is trained on 80% of the data and tested on the remaining 20%. The accuracy of the model on both the training and testing data is also calculated.

# Dependencies
numpy
pandas
sklearn

# Data Collection and Processing
The heart disease dataset is loaded using pandas' read_csv function
The first and last five rows, information, shape, missing values and statistical measures of the data are all printed to better understand the dataset
The target value (presence of heart disease) is also checked for distribution
The dataset is then split into features (X) and target (Y)
Model Training and Evaluation
A logistic regression model is trained on 80% of the data using sklearn's train_test_split function
The accuracy of the model is calculated on both the training and testing data using sklearn's accuracy_score function
Predictive System for an individual
A sample input for an individual's attributes is taken and passed through the trained model to predict the presence of heart disease

#Running the code
Run the code using a Python interpreter
The input data for the predictive system can be changed as desired
The final output will be a binary prediction of whether or not the individual has heart disease.
