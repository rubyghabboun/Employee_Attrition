# Employee_Attrition timeframe Prediction at IBM

Collaborators on this project:
1. Ruby Ghabboun
2. Aida Roman
3. Renato Barbosa
4. Caitlyn Myland

# In this project we will be exploring IBM's employee data set 
Uncover the factors that lead to employee attrition by exploring average monthly income, education, distance from home, job saticfaction and so many other factors and determin the timeframe of their departure to assist decision-making in the HR department by providing insights into when to initiate the hiring process and strategies to retain valuable employees.

## machine learning :
building a neural network model for predicting the timeframe until employee departure.

## Content of this project :
1. Each folder contain relevant code:
. Resources : 1. employedata set. 2. sample data set for algorithm application for new employees.
. cleaningAndTestData : 1. jupyter notebooks for cleaning , pulling, creating sample dataset, and creating dataset for visualization. 2. saved datasets outputs.
. machine_learning_models : 1. saved model. 2. model creation code. 3. model application code. 3. previous and currrent improved scores screenshots.
. tablaue viz : screenshots of tablaue visualizations of key features.
-- additional files : new data predicted csv and word doc. of model overview.

 Model Training:
•	Multiple neural network models are trained to capture different initializations and reduce variance.
•	Each model is trained for 150 epochs with a batch size of 64.
•	The mean squared error loss function is used for training, along with mean absolute error, mean squared error, and accuracy as metrics.
•	Training is performed on the scaled training data, with a validation split of 20% to monitor model performance during training.
Model Evaluation and Storage:
•	The trained models are stored in a list for further analysis and ensemble predictions.
•	Located the best evaluated model and saved for future use.
. Data balancing with RandomOverSampler. 
. Feature engineering by changing and adding relevant features.
. Used adam optimizer
. Hyperparameter optimization using grid search

# We implemented both approaches using Python and relevant libraries such as pandas, scikit-learn, and TensorFlow



# Resources : https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

