# Taxi-Trips-NYC-Analysis
Analyzing Yellow Taxi Trips in NYC: Clustering and Fare Prediction

About the project:

This project focuses on analyzing trip record data from the New York City Taxi and Limousine Commission, specifically the Yellow Taxi trips in January 2020. The dataset includes various features such as pickup and dropoff times, locations, trip duration, distance, and fare details for each taxi ride.

Steps involved:

- Data Reading and Cleaning: Read and preprocess the Yellow Taxi trip record data, ensuring it is in a suitable format for analysis.
- Extracting Latitude and Longitude: Extract the latitude and longitude coordinates from the data, which will be useful for clustering the data points.
- kMeans Clustering: Apply the kMeans clustering algorithm to create five clusters representing the boroughs of New York City. This step helps in grouping similar data points together based on their geographical coordinates.
- Incorporating Clusters: Integrate the clusters back into the original data, creating a new data frame that includes the cluster assignment, trip duration, and distance. This will be used to predict the total fare.

Conclusion:

Through data exploration, preprocessing, and clustering analysis, this project aims to gain insights into the Yellow Taxi trips in NYC. By utilizing kMeans clustering, the project identifies distinct clusters representing the five boroughs of NYC. The clustered data is then used to build a predictive model to estimate the total fare based on trip duration and distance. This project provides an opportunity to showcase data analysis, machine learning, and problem-solving skills in a real-world context.
