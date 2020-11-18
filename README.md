# PCA-Pytorch-MNIST
Applications of PCA: Visualizations, memory saver and neural network with Pytorch framework

Dimensionality reduction is the process of reducing the dimension of the feature set while maintaining its structure and usefulness.

Reasons for dimentionality reduction:

-Most points in a high-dimensional hypercube are very close to the border and at the risk of being very sparse, making predictions much less reliable than in lower dimensions.

-Very large number of features for each training instance may make training extremely slow.

-Difficult to visualize dataset containing large number of features.

Pros:

-Less time in training the dataset.

-Easy visualization of the dataset containing 2 or 3 principle features.

-May (May not) result in higher performance.

Cons:

-Loss of information.

Projection:
Projecting high dimensional data on a low dimentional hyperplane, minimizing the variance. (PCA)

PCA - Principal Component Analysis (Vanilla PCA) 

Principal components analysis is the main method used for linear dimension reduction.
It performs a linear mapping of the data to a lower-dimensional space in such a way that the variance of the data in the low-dimensional representation is maximized, with the maximum variance, maximum information is preserved. In another words, it selects the hyperplane(s) that minimizes the mean squared distance between the original dataset and its projection onto that hyperplane(s).

The first principle component accounts for the maximum variance in the data and so on ...
All the components in lower-dimensional space are linearly uncorrelated.
Each of the new features or components created after PCA are all independent of one another.
