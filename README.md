# Predicting Car Prices With Machine Learning Algorithm KNN

- In this project, we predicted car market price with a machine-learning algorithm: K-Nearest Neighbors.
- Our main public was car stores.
- In the EDA section, we selected the continuous values columns, handled missing values, detected outliers, and checked the correlation between the columns. After that, we preprocessed the data normalizing the columns, except for the target "price". Then, in the Modeling section, we used to train/test validation for the univariate model and got "engine_size" - RMSE = 2840.56 (K=3) as the best result. With the Multivariate model, we got "engine_size" and "horsepower" - RMSE = 2657.80 (K=2) and "engine_size" and "horsepower" - RMSE = 2949.88 (K=5) as best result. We choose the "engine_size" and "horsepower" - RMSE = 2949.88 (K=5) based on the number of neighbors (K) and the features.
