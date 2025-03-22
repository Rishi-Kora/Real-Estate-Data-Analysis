# Real-Estate-Data-Analysis
This project aims to predict the house price per unit area using a linear regression model. The project utilizes a real estate dataset containing features such as transaction date, house age, distance to the nearest MRT station, number of convenience stores, latitude, and longitude.<br>


1. Data Loading and Preprocessing:

The real estate dataset is loaded into a Pandas DataFrame.<br>

The transaction date is converted to a datetime format.<br>

Data is checked for missing values and duplicates.<br>

Outliers are identified and removed using the z-score method.<br>

The transaction date is converted to an ordinal value.<br>

2. Exploratory Data Analysis:

Descriptive statistics of the dataset are examined.<br>

Data distribution is visualized using histograms and box plots.<br>

Feature correlations are explored using a heatmap.<br>

3.Model Building and Evaluation:

The dataset is split into training and testing sets.<br>

Features are scaled using StandardScaler.<br>

A linear regression model is trained on the scaled training data.<br>

Model performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).<br>

4. Model Deployment:

The trained model and scaler are saved using pickle for future use.<br>

A new data point is used to demonstrate how to make predictions using the loaded model and scaler.<br>

Feel free to download the code and data.
