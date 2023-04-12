<h1>FLIGHT TICKET PRICE PREDICTION</h1>
The objective of the case study is to analyse the flight bookings data obtained by “Ease My Trip” website and to conduct various statistical hypothesis tests in order to get meaningful information from it. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers. Overall, I had to build a model that can precisely predict the ticket price.
<h3>ABOUT DATASET</h3>
Data is seperated in to two parts: 
One for economy class tickets and another for business class tickets.
A total of 300261 distinct flight booking options are available. And these are for 50 days, from February 11th to March 31st, 2022.
<h3>INITIAL PREPROCESSING</h3>
There was high noise in the data. So, I have done some cleaning and also drived some relevent featues from the given data

I drived new feature named class to specify in which class the ticket was booked

I drived new new feature named flight by adding ch_code and num_code of the flight

I drived new feature days left by subtracting the booking date from journey date (Booking date was 10/02/2022)

The various features of the cleaned dataset are explained below:

1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

11) Price: Target variable stores information of the ticket price.

<h3>METHEDOLOGY</h3>
In this project, we have used the following steps to predict flight ticket prices:

Data Cleaning: We have removed missing values and irrelevant columns, and performed data type conversions and feature engineering.

Exploratory Data Analysis: We have analyzed the relationships between the independent variables and the target variable using visualizations.

Feature Selection: We have selected the most important features for the model using various techniques.

Model Building: We have built a Random Forest Regression model to predict the flight ticket prices.

Model Evaluation: We have evaluated the performance of the model using metrics like Mean Absolute Error and R2 Score.

<h3>DATA SOURCE</h3>
The Flight Ticket Price Prediction dataset used in this project was obtained from Kaggle. The original source of the dataset is not mentioned, but it is a publicly available dataset on Kaggle. The dataset consists of flight ticket prices for various airlines between different cities in India. 
The dataset can be accessed from the following link: https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh

<h3>CONCLUSION</h3>
The Random Forest Regression model built for this project achieved an R2 score of 98.52 and a mean absolute error of 1095.15. This indicates that the model can predict flight ticket prices with an accuracy of 98.52%. The most important features for the model were found to be the number of stops, the duration of the flight, and the date of the journey.

Overall, this project demonstrates the effectiveness of machine learning techniques for predicting flight ticket prices, and provides a useful tool for travelers looking to find the best deals on flights between two cities.

