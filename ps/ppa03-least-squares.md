# ML Problem Solving
# Least squares

1. Consider the following dataset, where each row is one input and the measured output is the last column.

D = [[6, 5, 1],
[5, 6, 0],
[4, 3, 1],
[3, 4, 0],
[2, 3, 0],
[3, 2, 1]]

Draw the data points from X in a coordinate system.

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

2. Now let's try to manually choose $\beta \in \mathbb{R}^3$ to minimize the Residual Sum of Squares (RSS). Choose at least 3 different values for $\beta$ and calculate the associated RSS.

$\beta_a$ = [ ___ , ___ , ___ ]

$\beta_b$ = [ ___ , ___ , ___ ]

$\beta_c$ = [ ___ , ___ , ___ ]

#
#
#

3. Draw the decision boundaries for each model defined by your $\beta$. Do it for all three values you chose.

#

\newpage

4. Calculate $\beta = (X^T X)^{-1} X^T y$
<!-- >>> X
array([[6, 5],
       [5, 6],
       [4, 3],
       [3, 4],
       [2, 3],
       [3, 2]]) -->
<!-- >>> y
array([[1],
       [2],
       [1],
       [0],
       [2],
       [1]]) -->
<!-- (X.T @ X)^{-1} = array([[ 0.16923077, -0.16410256],
       [-0.16410256,  0.16923077]]) -->
<!-- y = array([[1],
       [2],
       [1],
       [0],
       [2],
       [1]]) -->
<!-- X @ beta =
array([[1.38461538],
       [1.71794872],
       [0.82051282],
       [1.15384615],
       [0.87179487],
       [0.53846154]]) -->
<!-- beta = 
array([[-0.02564103],
       [ 0.30769231]]) -->

#


5. Considering that $RSS(\beta) = (y - X \beta)^T (y - X \beta)$, derive a closed-form $\beta$ that minimizes $RSS$. (optional)





