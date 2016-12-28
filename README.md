#AnomalyDetection

This repository implements an anomaly detection algorithm using multivariate normal distribution and applies to a computer server data set.

Step 1: Data visualization --- we need to make sure each feature is nearly distributed as a Gaussian distribution, if not we need to perform some transformation so that the transformed feature is nearly Gaussian.

Step 2: Gaussian distribution parameter estimation --- Learn the parameters from the training set.

Step 3: Decision threshold parameter selection --- Select the parameter which gives the best performance on the validation set.

Step 4: Deploy the algorithm on new data.
