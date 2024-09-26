# Gold-Price-Prediction
Overview
The Gold Price Prediction project aims to forecast future gold prices based on historical data. A Random Forest Regressor model has been used to predict the prices. The model was trained on a dataset that includes several economic indicators and factors affecting gold prices.

Dataset
The dataset used for this project contains historical data of gold prices along with features such as:

Date
Gold Price (Target)
Crude Oil Prices
US Dollar Index
Interest Rates
Stock Market Index
Please ensure the dataset is formatted properly and saved in the data folder.

Libraries Used
The following libraries were used to develop this project:

NumPy - For numerical computations
Pandas - For data manipulation and analysis
Matplotlib - For plotting and visualizations
Seaborn - For enhanced visualizations
Scikit-learn - For machine learning algorithms
Model Training
The model is trained using a RandomForestRegressor from Scikit-learn, and the following steps are involved:

Data pre-processing: Handle missing values, feature scaling, and data splitting.
Train-Test Split: The dataset is divided into a training set and a testing set.
Model Training: The Random Forest Regressor is used to train on the historical data.
Model Evaluation: Performance is evaluated using metrics such as Mean Squared Error (MSE) and R-squared score.
Evaluation
The performance of the model is evaluated using the following metrics:

Mean Squared Error (MSE): To measure the average squared difference between predicted and actual values.
R-squared (R² Score): To determine how well the predictions align with actual values.
