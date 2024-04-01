# PCA

# Principal Component Analysis with Python
Principal Component Analysis is basically a statistical procedure to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables. 

Each of the principal components is chosen in such a way that it would describe most of them still available variance and all these principal components are orthogonal to each other. In all principal components, first principal component has a maximum variance.

# Uses of PCA: 

- It is used to find interrelations between variables in the data.
- It is used to interpret and visualize data.
- The number of variables is decreasing which makes further analysis simpler.
- It’s often used to visualize genetic distance and relatedness between populations.

These are basically performed on a square symmetric matrix. It can be a pure sums of squares and cross-products matrix Covariance matrix or Correlation matrix. A correlation matrix is used if the individual variance differs much.

# Principal Axis Method: 
PCA basically searches a linear combination of variables so that we can extract maximum variance from the variables. Once this process completes it removes it and searches for another linear combination that gives an explanation about the maximum proportion of remaining variance which basically leads to orthogonal factors. In this method, we analyze total variance.

# Eigenvector: 
It is a non-zero vector that stays parallel after matrix multiplication. Let’s suppose x is an eigenvector of dimension r of matrix M with dimension r*r if Mx and x are parallel. Then we need to solve Mx=Ax where both x and A are unknown to get eigenvector and eigenvalues. 
Under Eigen-Vectors, we can say that Principal components show both common and unique variance of the variable. Basically, it is variance focused approach seeking to reproduce total variance and correlation with all components. The principal components are basically the linear combinations of the original variables weighted by their contribution to explain the variance in a particular orthogonal dimension.

# Eigen Values: 
- It is basically known as characteristic roots.
- It basically measures the variance in all variables which is accounted for by that factor.
- The ratio of eigenvalues is the ratio of explanatory importance of the factors with respect to the variables.
-
-  If the factor is low then it is contributing less to the explanation of variables.
- In simple words, it measures the amount of variance in the total given database accounted by the factor.
- We can calculate the factor’s eigenvalue as the sum of its squared factor loading for all the variables.
