# Employee_Attrition Timeframe Prediction at IBM
## Overview
This project aims to predict the attrition and departure time frame of employees within an organization using machine learning. By analyzing various factors such as age, job role, job satisfaction, and several others, we've developed a model capable of forecasting how long employees are likely to stay. This initiative addresses the challenge of managing workforce stability and planning for future resource needs effectively.

Collaborators:
1. Ruby Ghabboun
2. Aida Roman
3. Renato Barbosa
4. Caitlyn Myland

## Content of this project repository :
# Each folder contain relevant code:
. Resources : 1. employee dataset. 2. sample data set for algorithm application for new employees.

. cleaningAndTestData : 1. jupyter notebooks for cleaning , pulling, creating sample dataset, and creating 
dataset for visualization. 2. saved datasets outputs.

. machine_learning_models : 1. saved model. 2. model creation code. 3. model application code. 3. previous and currrent improved scores screenshots.

. tablaue viz : screenshots of tablaue visualizations of key features.

-- additional files : new data predicted csv and word doc. of model overview.
   
## Features and Highlights
* Data Model Implementation: Our Python script leverages PySpark to handle data processing, cleaning, normalization, and standardization efficiently, ensuring the model operates on high-quality data. This approach highlights our capability to manage and analyze big data, setting the groundwork for accurate predictive modeling.
* Data source: The model capitalizes on data retrieved from an AWS S3 bucket using Spark, demonstrating our project's integration with cloud storage and distributed data processing platforms. This feature underscores the model's adaptability and scalability in handling large datasets.
* Predictive Power: With a rigorous training and validation process, our model achieves an R-squared value of 0.852, showcasing its strong predictive power. This achievement indicates our model's effectiveness in capturing the nuances of employee tenure based on the dataset provided.
  
## Getting Started
### Prerequisites
* Python 3.6+
* Pandas
* Scikit-learn
* Keras
* TensorFlow
* Matplotlib
  
## Data Model Optimization
The optimization of our neural network model involved iterative experimentation with various architectures, hyperparameters, and training strategies. This process was critical for enhancing the model's predictive accuracy and generalization capability.
* Grid Search: We employed grid search techniques to systematically explore combinations of batch sizes and epochs, leading to the identification of optimal values that minimized prediction error and improved model performance.
* Architecture Tuning: Experimentation with different numbers of layers and neurons helped refine the model's complexity to fit the data adequately without overfitting.
* Regularization: Techniques such as dropout were applied to prevent overfitting, ensuring that our model remains robust when exposed to new, unseen data.
  
## Results
The model demonstrates strong predictive capabilities, with key performance metrics including:
* R-squared: 0.852, indicating high model accuracy.
* MAE: 1.27, showcasing the model's precision.
* RMSE: 2.41, highlighting the model's reliability in prediction.
  
Areas for improvement include reducing the model's complexity to improve speed without significantly impacting accuracy and exploring more advanced regularization techniques to further mitigate overfitting.

## Contributing
Contributions to this project are welcome. Please adhere to the following guidelines:
* Fork the repository.
* Create a new branch for each feature or improvement.
* Submit a pull request with a clear description of the changes.
  
## Acknowledgements
* We extend our gratitude to IBM for providing the comprehensive HR Analytics Employee Attrition & Performance dataset, which served as the foundation for our predictive modeling. The dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).
* Special thanks to the open-source community for offering invaluable resources and tools that facilitated this project.

