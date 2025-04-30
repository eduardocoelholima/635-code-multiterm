# ML Problem Solving
# Binary Perceptron Learning Algorithm



1. Consider the following dataset, where each row is one input image and the measured output is the last column.

D = [[255, 128, 128, 0, 0], [55, 128, 128, 128, 0], [192, 128, 128, 0, 0],

[100, 128, 128, 100, 1], [30, 64, 128, 30, 1], [20, 64, 128, 0, 1]]


Assuming the sequence of $b_{row,column}$ bytes are $[b_{0,0}, b_{0,1}, b_{1,0}, b_{1,1}]$, draw the images.

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


2. Normalize the input features to the [0,1] range.



\newpage


Perceptron Learning Algorithm:

a. Set $b$ and all $w$'s to 0.

b. for N iterations (or until the weights do not change):

    - for each sample $x^k$ with answer $a^k$:
        - if $a^k - f(x^k) \neq 0$:        
        
        $\Delta w_i = (a^k - f(x^k)) x_i$


3. Calculate the weight and bias updates for each sample in D in a single iteration (full pass of the training dataset), according to the perceptron learning algorithm. Follow the sequence of samples provided in the dataset. Calculate the updates for all samples.

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
#
#

4. For each update from previous question, report the accuracy of the updated model on the whole dataset.

#
#
#
#

