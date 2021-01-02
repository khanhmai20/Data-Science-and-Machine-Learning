# Spam Email Classification

### Objective 
1. Practice Matlab programming
2. Machine Learning Algorithm
* Support Vector Machine
* Gaussian Kernel
3. Visualizing Data

### Performance
*gaussianKernel.m* include the implementation for SVM used later on. The figure below illustrates output of SVM with gaussianKernel for *ex6data3.m* dataset

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/SVM/Asset/ex6_01.png)

### Spam classification

1. Preprocessing emails: 
* Lower-casing
* Stripping HTML
* Normalizing URLs
* Normalizing Email Addresses
* Normalizing Numbers
* Normalizing Dollars
* Word Stemming
* Removal of non-words

2. Extracting features from emails: You will now implement the feature extraction that converts each email into a vector in . For this exercise, you will be using words in vocabulary list. Specically, the feature for an email corresponds to whether the -th word in the dictionary occurs in the email. That is,  if the -th word is in the email and  if the -th word is not present in the email. *emailFeatures.m* to generate a feature vector for an email, given the word indices

3.Training SVM for spam classification

![alt text](https://github.com/khanhmai20/DataAnalysis/blob/main/SVM/Asset/output.png)

### References
[Certified by Machine Learning Stand Ford University](http://cs229.stanford.edu)
