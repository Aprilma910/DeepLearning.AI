

Practical Aspects of Deep Learning

Discover and experiment with a variety of different initialization methods, apply L2 regularization and dropout to avoid model overfitting, then apply gradient checking to identify errors in a fraud detection model.
Learning Objectives

	• Give examples of how different types of initializations can lead to different results
	• Examine the importance of initialization in complex neural networks
	• Explain the difference between train/dev/test sets
	• Diagnose the bias and variance issues in your model
	• Assess the right time and place for using regularization methods such as dropout or L2 regularization
	• Explain Vanishing and Exploding gradients and how to deal with them
	• Use gradient checking to verify the accuracy of your backpropagation implementation
	• Apply zeros initialization, random initialization, and He initialization
	• Apply regularization to a deep learning model

 
make sure that the dev and test sets come from the same distribution.


does your algorithm have high bias?

use the training dev set to try to 
diagnose if you have a bias or variance problem, 
and then use that to select the appropriate subset of things to try


So w is an x-dimensional parameter vector, and b is a real number.

the norm of w squared, is just equal to 
sum from j equals 1 to nx of wj squared, or this can also be written w, 
transpose w, it's just a square Euclidean norm of the prime to vector w. 
And this is called L2 regularization.


Gradient checking is a technique that's helped me save tons of time, and 
helped me find bugs in my implementations of back propagation many times.
                                                                                                 
