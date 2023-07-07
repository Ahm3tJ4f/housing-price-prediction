# housing-price-prediction

## Dataset
The dataset used in this project is the California housing dataset, which provides various attributes of houses in different districts of California. The dataset contains information such as the median income, average number of rooms, population, and median house value.

The dataset is automatically downloaded and extracted within the code.

## Implementation
The code performs the following steps:

Fetches the housing dataset from an online source.
Loads and explores the dataset, including visualizing the data distribution.
Divides the dataset into training and testing sets, considering stratified sampling based on the income category.
Prepares the data for model training by applying feature scaling, handling missing values, and creating additional relevant attributes.
Defines a pipeline for data preprocessing and transformation.
Trains and evaluates various regression models, including Linear Regression, Decision Tree Regression, and Random Forest Regression.
Conducts cross-validation to assess model performance.
Performs hyperparameter tuning using grid search or randomized search to find the optimal model.
Evaluates the final model on the test set and calculates the root mean squared error (RMSE) as the performance metric.
Feel free to modify the code and experiment with different models and techniques to further improve the predictions.

## Acknowledgments
This project is based on the "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" book by Aurélien Géron.
