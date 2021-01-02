# Exam Score And Chip Test Analysis

### Objective 
1. Practice Matlab programming language
2. Machine Learning Algorithms
* Logistic Regression
* Gradient Descent
* Regularized function
3. Visualizing data


### Visualize exam score data
Suppose that you are the administrator of a university department and you want to determine each applicant's chance of admission based on their results on two exams. You have historical data from previous applicants that you can use as a training set for logistic regression. For each training example, you have the applicant's scores on two exams and the admissions decision.
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/LogisticRegression/Asset/ex2_01.png)

### Gradient Descent for Exam Score
The implementation of gradient descent and cost function for logistic regression is slightly different from linear regression. Implementation detail is included in the file *sigmoid.m*, *costFunction.m*. Then, we can use those two function result to plot decision boundaries, determine the edges of admission and rejection. 
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/LogisticRegression/Asset/ex2_02.png)

### Visualizing microchip data
you will implement regularized logistic regression to predict whether microchips from a fabrication plant passes quality assurance (QA). During QA, each microchip goes through various tests to ensure it is functioning correctly. Suppose you are the product manager of the factory and you have the test results for some microchips on two different tests. From these two tests, you would like to determine whether the microchips should be accepted or rejected. 
As we can see the plot below, the decision boundary is not linear but polynomials. 
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/LogisticRegression/Asset/ex2_03.png)

### Gradient Descent for Microchip Test
The algorithm will be similar to the exam score, however, this time we include the regularized term. Since some features will be unneccessary, if we includes them all will make our function expensive and overfit. Thus, we add regularization to re-scale it. 

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/LogisticRegression/Asset/ex2_04.png)

### References
[Certified by Machine Learning Stand Ford University](http://cs229.stanford.edu)
