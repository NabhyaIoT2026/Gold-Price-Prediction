# Gold-Price-Prediction
The **Gold Price Prediction project** is designed to forecast future gold prices using historical data and various economic indicators. The project employs a **Random Forest Regressor** model, a powerful machine learning algorithm for regression tasks. The dataset used for training the model includes several key features: the **Date**, **Gold Price** (which serves as the target variable), **Crude Oil Prices**, **US Dollar Index**, **Interest Rates**, and the **Stock Market Index**. These features capture a broad range of factors that influence gold prices over time.

For developing the project, various libraries have been utilized to streamline data processing and model building. **NumPy** was used for numerical computations, while **Pandas** enabled efficient data manipulation and analysis. **Matplotlib** and **Seaborn** were employed to create insightful visualizations, and **Scikit-learn** facilitated machine learning tasks, including model implementation and evaluation.

The project involved several key steps. Initially, data pre-processing was performed, which involved handling any missing values, scaling features, and preparing the data for analysis. The dataset was then split into a training set and a testing set using a **train-test split** approach. The **Random Forest Regressor** was trained on the historical data, leveraging its ensemble learning technique to make accurate predictions.

To evaluate the model's performance, metrics like **Mean Squared Error (MSE)** and the **R-squared (R²) score** were used. MSE measures the average squared differences between the predicted and actual values, indicating the model's prediction error. The R² score helps assess how well the predictions align with the actual values, providing a sense of the model's overall fit.

Lastly, the dataset is formatted correctly and stored in the **data folder**, ensuring smooth integration into the workflow.
