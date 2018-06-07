# Evaluating_facerec
Evaluating different face recognition on real and standard datasets

The Face Recognition techniques used in this project are PCA+SVM and Convolution Neural Networks(CNN). Support Vector Machine, one
of the best known classifiers for images and state of the art Convolution Neural Networks which have currently set the benchmarks for face recognition accuracy are used here. The accuracies of the above mentioned techniques are compared on standard and real datasets. We found that CNN performs better with bigger datasets while PCA+SVM performs better for smaller datasets.

Datasets: The AtnT dataset of faces is chosen as the standard dataset. We created a dataset of our own with a smaller set of images

Files---

dlib1.ipynb- Face detection performed using HOG(Histogram of Oriented Gradient) and face alignment performed using Landmark estimation. An API of the dlib library was used.

SVM_standarD.ipynb- Feature extraction using PCA and classification using a tuned SVM model on the ATnT dataset.

working SVM real(100)1.ipynb- Feature extraction using PCA and classification using a tuned SVM on our unique dataset

CNN real 100.ipynb - Experimenting with multiple layered networks on our unique dataset

CNN standard.ipynb - Experimenting with multiple layered networks on the standard ATnT dataset

PCA dense standard-Copy1.ipynb - Experimenting with a network of only dense layers after feature extraction by PCA

Conclusion--

The comparison of accuracies of the algorithms PCA+SVM and CNN are performed on different datasets
and the resulting conclusions are stated below:

 The real dataset shows lesser accuracy because of background noise, turned faces
and different lighting
 Increasing the training set size increases the accuracy of standard dataset
 Decreasing the size of the images results in reduced accuracy
 Increasing training set size causes the real dataset to over-fit on the training data
 For larger image sizes background noise has a higher effect on the accuracy
 Optimized CNN performs better on larger datasets
 Enhanced accuracy is achieved for a dataset with more number of classes

