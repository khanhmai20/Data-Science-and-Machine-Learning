# Number Detection

### Objective 
1. Practice Matlab programming 
2. Machine Learning Algorithm
* Feed Forward
* Backward Propagation
* Gradient Descent
3. Neural Network Model Representation

### Visualizing Data
There are 5000 training examples in **ex3data1.mat**, where each training example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is represented by a floating point number indicating the grayscale intensity at that location. The 20 by 20 grid of pixels is 'unrolled' into a 400-dimensional vector. Each of these training examples becomes a single row in our data matrix X. This gives us a 5000 by 400 matrix X where every row is a training example for a handwritten digit image.

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/NeuralNetwork/Asset/Visualization.png)

### Feed Forward implementation
Initializing the hypothesis function and feed forward to the output layer. Here is the model representation of the algorithm.
* **nnCostFunction.m** (also have the regularized term): Implementation of cost fucntion.
* **sigmoid.m**: Activation function for logistic regression

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/NeuralNetwork/Asset/FeedFoward.png)

### Backward Propagation
Minimize the cost function by calculating errors, using gradient descent to minimize the cost fuction. This technique employ backpropagation. 

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/NeuralNetwork/Asset/BackwardPropagate.png)

### References
[Certified by Machine Learning Stand Ford University](http://cs229.stanford.edu)
