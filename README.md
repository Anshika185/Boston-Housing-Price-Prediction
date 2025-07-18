# Boston-Housing-Price-Prediction

In this project, we will evaluate the performance and predictive power of a model that has been trained and tested on data collected from homes in suburbs of Boston, Massachusetts. A model trained on this data that is seen as a good fit could then be used to make certain predictions about a home's monetary value.

The dataset for this project originates from the UCI Machine Learning Repository. The Boston housing data was collected in 1978 and each of the 506 entries represent aggregated data about 14 features for homes from various suburbs in Boston, Massachusetts.

For the purposes of this project, the following preprocessing steps have been made to the dataset:

1)16 data points have an 'MEDV' value of 50.0. These data points likely contain missing or censored values and have been removed.

2)1 data point has an 'RM' value of 8.78. This data point can be considered an outlier and has been removed.

3)The features 'RM', 'LSTAT', 'PTRATIO', and 'MEDV' are essential. The remaining non-relevant features have been excluded.

4)The feature 'MEDV' has been multiplicatively scaled to account for 35 years of market inflation
