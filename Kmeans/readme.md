# Image Compression Example

### Objective
1. Practice Matlab programming
2. Machine Learning Algorithms
* Kmeans 
* PCA 
3. Visualizing Image

### Kmeans on the dataset
* *findClosestCentroids.m* : This source code group all the data point to the closest centroid. 
* *computeCentroids.m* : This source code will re-compute the centroids based on the grouping above. 
* Visualizing data:

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/Kmeans/Asset/kmeans.png)
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/Kmeans/Asset/Example.png)

With the same implementation of Kmeans algorithms, applying it on real image. Finally, you can view the effects of the compression by reconstructing the image based only on the centroid assignments. Specically, you can replace each pixel location with the mean of the centroid assigned to it. Figure 3 shows the reconstruction we obtained. Even though the resulting image retains most of the characteristics of the original, we also see some compression artifacts.

### Principle Component Analysis
* *pca.m* : Source code to compute the principal components of the dataset 
* *projectData.m* : you will use the eigenvectors returned by PCA and project the example dataset into a reduced-dimensional space.
* Visualizing reduction: 

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/Kmeans/Asset/DimensionalityRed.png)
![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/Kmeans/Asset/PCA.png)

From the reconstruction, you can observe that the general structure and appearance of the face are kept while the fine details are lost. This is a remarkable reduction (more than ) in the dataset size that can help speed up your learning algorithm signicantly. For example, if you were training a neural network to perform person recognition (gven a face image, predict the identitfy of the person), you can use the dimension reduced input of only a 100 dimensions instead of the original pixels.

### References
[Certified by Machine Learning Stand Ford University](http://cs229.stanford.edu)
