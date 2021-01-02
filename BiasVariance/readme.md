# Bias vs Variance

### Objective
1. Evaluating performance of algorithms
2. What is bias (underfit) and variance (overfit)
3. Taking initiatives


### Visualizing Data
We will begin by visualizing the dataset containing historical records on the change in the water level, , and the amount of water flowing out of the dam, . This dataset is divided into three parts:
* A training set that your model will learn on: X, y
* A cross validation set for determining the regularization parameter: Xval, yval
* A test set for evaluating performance. These are 'unseen' examples which your model did not see during training: Xtest, ytest

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/BiasVariance/Asset/ex5_01.png)


### Fiting Linear Regression (Bias)
Fiting regularized linear regression cost function to data above. As we expect, the algorithm will underfit the data because it's not complex enough. you can observe that both the train error and cross validation error are high when the number of training examples is increased.

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/BiasVariance/Asset/linearReg.png)
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/BiasVariance/Asset/linearError.png)


### Fitting Polynomial Regression (Variance)
Fitting polynomial regression cost function to the data above, this time regularized term is 0. You should see that the polynomial fit is able to follow the datapoints very well - thus, obtaining a low training error. However, the polynomial fit is very complex and even drops off at the extremes. This is an indicator that the polynomial regression model is overfitting the training data and will not generalize well.

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/BiasVariance/Asset/Polynomial.png)

### References
[Certified by Machine Learning Stand Ford University](http://cs229.stanford.edu)
