# Gold-Price-Prediction
The **Gold Price Prediction project** is designed to forecast future gold prices using historical data and various economic indicators. The project utilizes a **Random Forest Regressor** model, a highly effective machine learning algorithm for regression tasks. The dataset used to train the model includes key features: the **Date**, **S&P 500 Index (SPX)**, **Gold Price (GLD)** (target variable), **Crude Oil Prices (USO)**, **Silver Prices (SLV)**, and the **EUR/USD exchange rate**. These features encompass a range of economic factors that influence gold prices over time.

In developing the project, multiple libraries were employed to facilitate data handling and model construction. **NumPy** was used for numerical operations, and **Pandas** helped with data manipulation and analysis. **Matplotlib** and **Seaborn** were used to create visualizations that provide insights into the data, while **Scikit-learn** supported the machine learning tasks, including model implementation and evaluation.

The project followed several important steps. The data was pre-processed by addressing missing values, scaling features, and preparing the dataset for analysis. A **train-test split** was applied to divide the dataset into training and testing sets. The **Random Forest Regressor** was then trained on the historical data, taking advantage of its ensemble learning method to generate accurate predictions.

Model performance was evaluated using metrics such as **Mean Squared Error (MSE)** and **R-squared (R²) score**. MSE helps in measuring the average squared differences between predicted and actual values, providing an indicator of prediction error. The R² score assesses how well the predictions match the actual values, giving insight into the model's overall performance.

Finally, the dataset is correctly formatted and saved in the **data folder**, ensuring seamless integration with the project pipeline.
