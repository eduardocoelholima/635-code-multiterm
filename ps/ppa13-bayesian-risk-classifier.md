# ML Problem Solving
# MAP and Bayesian Risk Minimization Classifier

<!-- 1. (optional) This is the same dataset as in the previous PSS. Consider the following dataset, where each row is an observation. First and second columns are input features and the true output is the last column. -->

Consider the following dataset, where each row is an observation. First and second columns are input features and the true output is the last column.

$D = [[3,3,1],[1,1,1],[-1,0,1],[2,2,0],[-2,2,0],[-2,-2,0],[0,-2,0],[1,5,2],[2,4,2],[3,4,2]]$

<!-- Draw the points in a 2-D coordinate system. Label the points according to their classes.  -->

1. Estimate $P(class)$ for each class using the ratio of samples in each class with respect to the dataset size.

#
#
#

2. Estimate the $\mu$ mean vector and the $\Sigma$ covariance matrix for each subset of datapoints, according to their classes. Since this data has 3 classes, you should have a $\mu, \Sigma$ pair for each class.
<!-- In your coordinate system, sketch a mahalanobis-distance contour of 1.0 for each class. -->

#
#
#
#


3. Calculate the likelihood as the probability density of an input $X$ drawn from $P(X|class)$. You should find a density for each class. Write down your equation with only $X$ as a variable.

#
#
#
#
#
#
#
#
#
#


\newpage

4. Write down $P(class)$, $P(X|class)$ and $P(class|X)$ for test datapoints in $X_0 = [2,2]$ and $X_1 = [2,3]$. Remember that the probabilities and probability densities depend on $X$ and $class$, so we will have 15 distict probabilities/densities. What would the class prediction of the Maximum A-Posteriori classifier be for our test data points?

#
#
#
#

5. Consider the following cost table, where $\hat{\omega}$ are the predicted classes and $\omega$ are the actual classes.

|                    | $\omega = 0$ | $\omega = 1$ | $\omega = 2$ |
| ------------------ | ------------ | ------------ | ------------ |
| $\hat{\omega} = 0$ | 0.3          | 0.3          | 0.3          |
| $\hat{\omega} = 1$ | 0.3          | -0.5         | 0.3          |
| $\hat{\omega} = 2$ | 0.1          | 0.1          | -0.9         |

For each test data points $X_0$ and $X_1$ and for each class, write down the associated 
$R(\hat{\omega_i}|X) = \sum_k{C(\hat{\omega_i}|\omega_k) P(\omega_k|X)}$

#
#
#
#
#
#
#
#

6. What would the class predictions of the Bayesian Risk Minimization classifier be for our test data points $X_0$ and $X_1$?

#
#
#
#

<!-- 5. Reject option? -->

