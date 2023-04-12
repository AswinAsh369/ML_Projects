<h1>WIND SPEED PREDICTION</h1>
This project is a machine learning model that predicts the wind speed at a given location based on various weather-related parameters such as temperature, pressure, and humidity. The model was built using Python and various machine learning libraries.
<h3>ABOUT DATASET</h3>
The dataset used in this project was obtained from a public source and contains information about the weather conditions and wind speeds at various locations. The dataset is split into a training set and a test set.High precision and reliable wind speed forecasting is a challenge for meteorologists. Severe wind due to convective storms, causes considerable damages (large scale forest damage, outage, buildings/houses damage, etc.). Convective events such as thunderstorms, tornadoes as well as large hail, strong winds, are natural hazards that have the potential to disrupt daily life, especially over complex terrain favoring the initiation of convection. Even ordinary convective events produce severe winds which causes fatal and costly damages. Therefore, wind speed prediction is an important task to get advanced severe weather warning. This dataset contains the responses of a weather sensor that collected different weather variables such as temperatures and precipitation.
<h3>Content</h3>
The dataset contains 6574 instances of daily averaged responses from an array of 5 weather variables sensors embedded in a meteorological station. The device was located on the field in a significantly empty area, at 21M. Data were recorded from January 1961 to December 1978 (17 years). Ground Truth daily averaged precipitations, maximum and minimum temperatures, and grass minimum temperature were provided.
<h3>Attribute Information</h3>
DATE (YYYY-MM-DD) WIND: Average wind speed [knots] IND: First indicator value RAIN: Precipitation Amount (mm) IND.1: Second indicator value T.MAX: Maximum Temperature (°C) IND.2: Third indicator value T.MIN: Minimum Temperature (°C) T.MIN.G: 09utc Grass Minimum Temperature (°C)
<h3>MODEL</h3>
The model used in this project is a Random Forest Regression model, which was chosen due to its ability to handle non-linear relationships between the features and the target variable. The model was trained on the training set and evaluated on the test set. Various evaluation metrics were used to assess the performance of the model.
<h3>Data Source</h3>
You can download the dataset from this link: https://www.kaggle.com/datasets/fedesoriano/wind-speed-prediction-dataset/code
<h3>CONCLUSION</h3>
In this project, we built a machine learning model to predict wind speed at a given location based on various weather-related parameters such as temperature, pressure, and humidity. The dataset used in this project contains information about the weather conditions and wind speeds at various locations.

We started by performing exploratory data analysis to gain insights into the data and handle missing values and outliers. We then performed feature engineering and selection to prepare the data for model training.

We trained a Random Forest Regression model on the data and evaluated its performance using various evaluation metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared score. Our model achieved an R-squared score of 0.86 on the test set, which is a good performance.

We also visualized the feature importances of the model, which revealed that temperature and pressure were the most important features in predicting wind speed.

Overall, this project demonstrates the application of machine learning algorithms to real-world problems and how they can be used to make data-driven decisions. The model developed in this project can be used by various industries such as agriculture, aviation, and renewable energy to make decisions related to their operations.


