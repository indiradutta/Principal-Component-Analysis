# Principal Component Analysis
Principal Component Ananlysis is a process of computing the "Principal Components" and using them to perform changes in the data. It is a very popular algorithm that is often used in unsupervised learning for dimensionality reduction.
For example :- Suppose I have a a dataset with 'm' data points that are of 'n' dimensions. Dimensionality reduction implies transforming those data points in such a way that they now have a reduced dimension of 'k' for all k<n, without any significant loss of valuable information. 
It can also be defined as projecting the data-points from an n-dimensional data space into a k-dimensional data space without loosing the information they contain.
This can be achieved through PCA.

# What are principal components?
Principal Components can be defined as vectors representing the directions along which the variances of the projected data are maximised. Principal components can be found out through eigendecomposition which will be discussed shortly.

# Step by Step Explanation of PCA
## The following steps are done in PCA
Suppose we have a dataset X consisting of m examples and n features or we can say it as, we have m data points that are of n dimensions.
### * Step 1 : Computing the Covariance Matrix of X
** For this we first need to compute the mean along each coloumn that is the mean for every feature :-
   here j is the feature number and i is the example number.
** Then we compute the deviations of my data points from the mean :-

** Then we find out the covariance matrix from the followiing formula :-

   in our code we have used the Standard Scaler function to convert the data into a Standard Normal Distribution by reducing the mean to 0 and the standard deviation to 1. This      helps us reduce the computation time and increses the computation efficiency. 
   
